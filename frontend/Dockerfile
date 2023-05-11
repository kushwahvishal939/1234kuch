FROM node:latest
RUN git clone https://github.com/kushwahvishal939/Pizza-Shop.git
WORKDIR Pizza-Shop/frontend/
RUN npm install && npm install -g pm2
ENTRYPOINT pm2 start npm --name "frontend" -- start
