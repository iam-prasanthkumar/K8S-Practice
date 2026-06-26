FROM almalinux:8
RUN apt-get update -y && apt-get install net-tools telnet iputils-ping -y
RUN useradd roboshop
USER roboshop
CMD ["sleep", "1000000"]