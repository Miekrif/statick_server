
# Dockerfile for static server test environment
FROM ubuntu:24.04
RUN apt-get update && apt-get install -y openssh-server && mkdir /var/run/sshd
CMD ["/usr/sbin/sshd", "-D"]
