FROM node:latest
WORKDIR /app
COPY . .
RUN cd puppeteer-recorder && npm i && npm run dev
ENTRYPOINT npm run dev