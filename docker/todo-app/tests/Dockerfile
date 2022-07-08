FROM mjgargani/puppeteer:trybe1.0 as todotests
WORKDIR /
COPY . .
ADD node_modules.tar.gz .
CMD ["npm", "test"]
