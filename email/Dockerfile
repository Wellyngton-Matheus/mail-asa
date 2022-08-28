FROM ubuntu:20.04

RUN apt update

RUN apt upgrade -y

RUN apt install postfix dovecot-core dovecot-imapd vim dnsutils iputils-ping -y

COPY postfix/main.cf /etc/postfix



