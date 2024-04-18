FROM node:14.14.0-alpine
WORKDIR /app
COPY ./package.json ./
RUN npm install --no-audit
COPY . .
CMD ["npm","run","start"]