FROM ubuntu:latest
RUN apt-get -y update
RUN apt-get -y upgrade
RUN apt-get -y install python3 python3-pip
RUN pip3 install Flask
RUN pip3 install Flask-cors
WORKDIR /app
COPY api.py /app/api.py
EXPOSE 5252
CMD [ "python3", "api.py"]
