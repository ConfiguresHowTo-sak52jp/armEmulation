# (e.g.) docker build --tag user/arm64v8/ubuntu:ver001 .
FROM arm64v8/ubuntu:18.04
COPY qemu-aarch64-static /usr/bin
# COPY apt.conf /etc/apt/ #-- Required when using proxy. --
RUN apt-get update && apt-get upgrade -y
RUN apt-get install -y build-essential python perl git emacs25 gdb
