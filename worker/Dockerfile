FROM node:15-alpine
WORKDIR /home/app
COPY ./package.json ./
RUN npm install
COPY . .
#Production command
CMD ["npm", "run", "start"]