FROM node:9.6.1-slim@sha256:8bec42e19402dcb8830f4d4ddc794362bb3700b4160bb49644003edddd452ea5
WORKDIR /app
RUN npm install sqlite3 --save
COPY pkg/server-linux .
RUN ls
CMD ./server-linux
ENV PORT=4000
EXPOSE $PORT
CMD ./server-linux
