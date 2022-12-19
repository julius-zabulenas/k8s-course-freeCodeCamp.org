FROM node:alpine

WORKDIR /app

EXPOSE 3000

COPY package.json package-lock.json index.mjs ./

RUN npm install

#Not sure why I need this line, so I just added the index.jms
#to the copy satement above
#COPY . ./

CMD ["npm", "start"]