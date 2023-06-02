FROM node:19

WORKDIR /usr/src/app

# Copy the files required for dependencies to be installed
COPY package* ./

COPY . .

RUN npm install

EXPOSE 3000

CMD  ["npm", "start"]