FROM python:3.11.2-buster

USER root
WORKDIR /home

RUN apt-get update && apt-get -y upgrade

COPY build ./build
RUN chmod +x /home/build/bowtie-analysis-api

RUN mkdir /home/projects

EXPOSE 8000

CMD ["/home/build/bowtie-analysis-api"]