FROM node:14-alpine as todofrontend
WORKDIR /
COPY . .
ADD node_modules.tar.gz .
CMD ["npm", "start"]
