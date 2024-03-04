# Stage 1: Build
# Use an official Node.js runtime as a parent image
FROM node:20

COPY . /app/
WORKDIR /app
RUN npm install
ENV PORT=3000
ENV REACT_APP_BACKEND_URL=http://localhost:8000
CMD ["npm", "start"]
