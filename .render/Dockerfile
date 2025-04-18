FROM node:18.17.0

WORKDIR /app

COPY . .

RUN npm install && npm run build

CMD ["npx", "n8n"]
