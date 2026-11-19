FROM ubuntu:24.04

WORKDIR /usr/src/app

RUN apt-get update && apt-get install -y curl

COPY script.sh .

# Make the script executable
RUN chmod +x script.sh

CMD ["./script.sh"]
