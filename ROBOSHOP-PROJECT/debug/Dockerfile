FROM almalinux:8
RUN dnf install -y \
    net-tools \
    telnet \
    iputils \
&& dnf clean all
RUN useradd roboshop
USER roboshop
CMD ["sleep", "1000000"]