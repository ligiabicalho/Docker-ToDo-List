FROM mjgargani/puppeteer:trybe1.0
WORKDIR /usr/src/app
ADD node_modules.tar.gz /usr/src/app
COPY . /usr/src/app
ENTRYPOINT [ "npm", "test" ]

