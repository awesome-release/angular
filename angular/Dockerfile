FROM node:18

RUN mkdir /project
WORKDIR /project

RUN npm install --location=global @angular/cli

COPY . .

RUN npm install
CMD ["ng", "serve", "--disableHostCheck", "true", "--host", "0.0.0.0"]
