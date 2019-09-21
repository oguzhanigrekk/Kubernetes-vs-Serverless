FROM node:carbon-alpine
CMD ['npm','start']
WORKDIR /app
EXPOSE 80
COP package.json ./
RUN npm install
COPY . .
