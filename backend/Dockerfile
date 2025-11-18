FROM node:20
WORKDIR /opt/server
COPY *.js /opt/server/
COPY package.json /opt/server/
COPY schema/* /opt/server/
RUN npm install
ENV DB_HOST="database"
CMD ["node", "index.js"]