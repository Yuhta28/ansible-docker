FROM node:latest
ENV NUXT_HOST=0.0.0.0
ENV NUXT_TELEMETRY_DISABLED=1
WORKDIR /app

COPY ./app/package.json ./app/yarn.lock ./
RUN yarn install

COPY ./app .

CMD ["yarn", "run", "dev"]
