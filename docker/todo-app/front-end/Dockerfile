FROM node:14-alpine as todofrontend
WORKDIR /
COPY . .
EXPOSE 3000
ADD node_modules.tar.gz .
CMD ["npm", "start"]
