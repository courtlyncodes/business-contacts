FROM node
WORKDIR /app
COPY . .
RUN npm install ci && npm run build
EXPOSE 1234
CMD ["node", "server.js"]