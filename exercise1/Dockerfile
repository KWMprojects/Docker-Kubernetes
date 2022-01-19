#Add the hello world file and excute upon container launch

FROM ubuntu

MAINTAINER Kevin Maguire

RUN apt-get update
RUN apt-get install -y python3 python3-pip 
RUN pip install --upgrade pip

ADD msg.py /home/me/Projects/Docker_Kubernetes_Fun/exercise1/msg.py

WORKDIR //home/me/Projects/Docker_Kubernetes_Fun/exercise1

CMD python3 msg.py