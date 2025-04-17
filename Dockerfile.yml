FROM node:18
Workdir app/
copy package*.json ./

RUN npm install 

copy . .
Expose 3000
CMD ["npm","start"]
