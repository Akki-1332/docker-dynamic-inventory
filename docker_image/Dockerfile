FROM centos
RUN yum install net-tools openssh-server passwd -y && ssh-keygen -A &&  echo redhat | passwd root --stdin
CMD [ "/usr/sbin/sshd", "-D"]



