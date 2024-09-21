FROM node:20-bullseye-slim
WORKDIR /app
COPY ./package.json .
COPY ./package-lock.json .
RUN npm install
COPY . .
EXPOSE 8090:8090
CMD ["npm","run", "dev"]