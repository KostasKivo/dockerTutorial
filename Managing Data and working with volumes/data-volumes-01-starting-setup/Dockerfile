FROM node:14

WORKDIR /app

COPY package.json /app

RUN npm install

COPY . .

ENV PORT 80

EXPOSE $PORT

# VOLUME ["/app/feedback"]

# We named the start script in the package.json file
CMD ["npm","start"]
