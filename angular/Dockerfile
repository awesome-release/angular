FROM node:16

RUN mkdir /project
WORKDIR /project

COPY . .

RUN npm install --location=global @angular/cli
RUN yarn install
CMD ["ng", "serve", "--disableHostCheck", "true", "--host", "0.0.0.0"]
