FROM node:14.16.1
WORKDIR /app
COPY package*.json ./
RUN apt-get update -y
RUN apt install yarn -y
COPY . .
RUN yarn
EXPOSE 3000
CMD [ "yarn", "start"] 