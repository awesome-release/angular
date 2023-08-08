FROM node:18

RUN mkdir /project
WORKDIR /project

RUN npm install -g npm@latest
RUN npm install --location=global @angular/cli

COPY . .

RUN npm install
CMD ["ng", "serve", "--disable-host-check", "true", "--host", "0.0.0.0"]
