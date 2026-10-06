FROM node:20 
WORKDIR /app 
COPY package*.json ./ 
RUN npm install 
COPY . . 
EXPOSE 1337 
CMD ["npm", "run", "develop", "--", "--host", "0.0.0.0"]