#use the offical node.js image
FROM node:18

#set the working directory in the container
WORKDIR /usr/src/app

#install dependencies
COPY package.json ./
RUN npm install

#Copy the rest of the application code
COPY . .

#Expose the backend port
EXPOSE 5000

CMD ["npm", "start"]
