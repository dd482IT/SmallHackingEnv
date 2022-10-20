FROM ubuntu:latest

#Install updates/upgrads. 
USER root
RUN apt-get update -y
RUN apt-get upgrade -y
RUN apt-get install bash -y 
RUN apt-get install git -y 
RUN apt-get install vim -y 
RUN apt-get install wget
RUN apt install gobuster -y
RUN apt install -y net-tools
RUN apt install -y nmap

#Installing gdw-pwndbg modified script 
RUN git clone https://github.com/dd482IT/gdb-peda-pwndbg-gef-Docker.git
RUN chmod +x gdb-peda-pwndbg-gef-Docker/*
RUN cd gdb-peda-pwndbg-gef-Docker ;\
    sh install.sh ;\
    sh update.sh





 