FROM gliderlabs/alpine:3.2
RUN apk --update add nodejs
RUN npm install -g express
RUN npm install -g forever
RUN npm install -g pg
RUN npm install -g nodeunit
ENV NODE_PATH /usr/lib/node_modules
EXPOSE 3000
ENTRYPOINT ["forever", "--watch", "--watchDirectory", "/app", "/app/server.js"]
