FROM node:20
WORKDIR /opt/backend
COPY package.json .
COPY *.js .
RUN npm install 
ENV DB_HOST="local host"
CMD ["node", "index.js"]
