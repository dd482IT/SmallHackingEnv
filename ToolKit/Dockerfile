FROM alpine:latest

#Install updates/upgrads. 
RUN apk update
RUN apk add --upgrade apk-tools
RUN apk upgrade --available 
RUN apk add bash

#Setup bash shell 

RUN apk add libuser
RUN touch /etc/login.defs
RUN mkdir /etc/default
RUN touch /etc/default/useradd
#RUN lchsh root /bin/bash
