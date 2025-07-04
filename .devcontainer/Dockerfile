FROM centos:7

# Install base tools
RUN yum install -y sudo python3 python3-pip vim curl iproute && \
    useradd -m dev && echo "dev ALL=(ALL) NOPASSWD:ALL" >> /etc/sudoers

USER dev
WORKDIR /home/dev

