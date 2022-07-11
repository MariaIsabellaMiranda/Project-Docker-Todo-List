FROM node:14-alpine
WORKDIR /app
EXPOSE 3000
ADD ./node_modules.tar.gz .
COPY ./ .
COPY ./.env .
ENV REACT_APP_API_HOST=todobackend
ENV REACT_APP_API_PORT=3001
ENTRYPOINT [ "npm", "start" ]