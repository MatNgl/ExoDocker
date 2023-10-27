FROM node:21-alpine3.17
WORKDIR /app
COPY ./mosters /app/
COPY ./posters /app/poster

EXPOSE 8080
ENV POSTER_DIR=/poster

CMD ["npm", "start"]