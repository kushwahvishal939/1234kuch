FROM node:latest
RUN git clone https://github.com/kushwahvishal939/Pizza-Shop.git
WORKDIR Pizza-Shop/backend/
RUN npm install && npm install -g nodemon
ENTRYPOINT pm2 start npm --name "backend" -- start
