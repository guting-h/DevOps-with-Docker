# Prerequisite
FROM node:16

# switched to port 5001 since 5000 isn's available
EXPOSE 5001

WORKDIR /usr/src/app

# Copy the files required for dependencies to be installed
COPY package* ./

RUN npm install

# to run the project
COPY . .

ENV REACT_APP_BACKEND_URL="http://localhost:8080"

RUN npm run build

RUN npm install -g serve

# switched to port 5001 since 5000 isn's available
CMD ["serve", "-s", "-l", "5001", "build"]
