FROM node:19.2-alpine
RUN addgroup -S appgroup && adduser -S nodeapp -G appgroup
USER nodeapp
WORKDIR /home/nodeapp
COPY ./src/* /home/nodeapp
RUN npm install
CMD ["index.js"]