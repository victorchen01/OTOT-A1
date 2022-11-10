FROM node:lts-alpine
ENV NODE_ENV=production
WORKDIR /usr/src/nginx-sample/nginx-1.23.2
COPY . .
EXPOSE 85
RUN chown -R node /usr/src/nginx-sample/nginx-1.23.2
USER node
CMD ["npm", "start"]