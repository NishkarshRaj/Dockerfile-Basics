FROM ubuntu

RUN apt-get update

ADD ./Basic.tar /root/

CMD if test -d "/root/Basic"; then echo "Folder extracted Successfully"; fi 
