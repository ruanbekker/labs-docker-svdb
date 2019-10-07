FROM ubuntu
RUN apt update && apt install wget curl -y 
ADD uuids.txt /uuids.txt
CMD ["wc", "-l", "/uuids.txt"]
