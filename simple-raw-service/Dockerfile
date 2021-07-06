FROM node:12-stretch

RUN echo "Europe/Athens" > /etc/timezone && dpkg-reconfigure -f noninteractive tzdata

COPY package.json /tmp/package.json

WORKDIR /tmp

RUN npm install && mkdir -p /opt/app && cp -a /tmp/node_modules /opt/app/

WORKDIR /opt/app

COPY . /opt/app

EXPOSE 3000

CMD ["npm", "start"]
