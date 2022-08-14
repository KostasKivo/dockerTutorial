FROM node

WORKDIR /backend

COPY package.json /backend

RUN npm install

COPY . .

EXPOSE 80

ENV MONGODB_USERNAME=root
ENV MONGODB_PASSWORD=secret

CMD ["node","app.js"]
