FROM node:10

RUN npm install -g @vue/cli; \
  sed -i 's/subscriptionsPath/host: "0.0.0.0", subscriptionsPath/' /usr/local/lib/node_modules/@vue/cli/lib/ui.js

