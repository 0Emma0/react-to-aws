FROM node:14-alpine
ENV NODE_ENV=production
WORKDIR /app
COPY . .
RUN npm install
EXPOSE 3000
CMD ["npm", "start"]
