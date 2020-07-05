FROM node:12.13.1-alpine

WORKDIR /app

RUN apk update && npm install -g npm
RUN npm init -y
RUN npm install -D webpack webpack-cli babel-loader @babel/core @babel/preset-env @vue/cli

EXPOSE 9050

# CMD ["/bin/sh"]

CMD ["npm", "run", "watch"]


