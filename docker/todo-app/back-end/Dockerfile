FROM node:14-alpine as todobackend
COPY . .
WORKDIR /
EXPOSE 3001
ADD node_modules.tar.gz .
CMD ["npm", "start"]