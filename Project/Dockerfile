FROM node:14.20.1 as builder

WORKDIR /app
COPY . .
ENV PORT=3000
RUN npm install
EXPOSE 3000
ENTRYPOINT ["node", "app.js"]