FROM node:12-stretch

RUN echo "Europe/Athens" > /etc/timezone
RUN dpkg-reconfigure -f noninteractive tzdata

COPY . /app

WORKDIR /app

CMD ["npm", "start"]
