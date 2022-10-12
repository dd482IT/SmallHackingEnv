FROM ubuntu:latest

#Install updates/upgrads. 
USER root
RUN apt-get update -y
RUN apt-get upgrade -y
RUN apt-get install bash -y 
RUN apt-get install git -y 
RUN apt-get install vim -y 
RUN apt-get install wget

#Installing gdb dependcies 
#RUN apt-get install --no-cache make
#RUN apt-get install --no-cache linux-headers
#RUN apt-get install --no-cache texinfo
#RUN apt-get install --no-cache gcc
#RUN apt-get install --no-cache g++ 

#Installing gdw-pwndbg modified script 
RUN git clone https://github.com/dd482IT/gdb-peda-pwndbg-gef-Docker.git
RUN chmod +x gdb-peda-pwndbg-gef-Docker/*
RUN cd gdb-peda-pwndbg-gef-Docker ;\
    sh install.sh ;\
    sh update.sh


#Setup bash shell 


#RUN lchsh root /bin/bash

 