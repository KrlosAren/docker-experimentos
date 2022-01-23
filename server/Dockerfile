FROM node:12.16-alpine


RUN mkdir -p /app
COPY . ./app
WORKDIR /app

RUN npm install 

EXPOSE 5000
CMD ["npm", "run", "start"]