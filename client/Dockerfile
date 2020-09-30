FROM node:alpine # image and tag from dockerhub

WORKDIR /app ## where to save all files, here is directory called app

COPY package.json ./ # copy package.json so we cam run all depencies

RUN npm install # install depencies from package.json that we copied

COPY ./ ./ ## copy everything from this directory to app directory

CMD ["npm", "start"] # start the app