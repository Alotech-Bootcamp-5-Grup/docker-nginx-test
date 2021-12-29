FROM node:lts
WORKDIR /sso-client
COPY package*.json ./
RUN npm install
COPY . .
CMD ["npm", "start"]
