FROM node:14

COPY ./material-applications/example-frontend .

RUN \
  npm install &&\
  npm run build &&\
  npm install -g serve

EXPOSE 5000

CMD ["npx", "serve", "-s", "-l", "5000", "build"]
