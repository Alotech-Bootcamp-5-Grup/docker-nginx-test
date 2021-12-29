FROM node:lts
WORKDIR /sso-server
COPY package*.json ./
RUN npm install
COPY . .
CMD ["npm", "start"]
