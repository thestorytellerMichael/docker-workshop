FROM node:20

COPY . /app/
WORKDIR /app
RUN npm install
ENV PORT=8000
CMD ["node", "index.js"]
