FROM node:16

# switched to port 5001 since 5000 isn's available
EXPOSE 5001

WORKDIR /usr/src/app

COPY package* ./

RUN npm install

COPY . .

# Changed to http://localhost/api
ENV REACT_APP_BACKEND_URL="http://localhost/api"

RUN npm run build

RUN npm install -g serve

CMD ["serve", "-s", "-l", "5001", "build"]
