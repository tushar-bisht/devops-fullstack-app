FROM ubuntu:20.04
RUN apt-get update
RUN apt-get install -y curl
RUN curl -sL https://deb.nodesource.com/setup_14.x | bash -
RUN apt-get update
RUN apt-get install -y nodejs
WORKDIR /app/
COPY . .
RUN npm install
EXPOSE 3000
ENTRYPOINT ["npm","start"]
