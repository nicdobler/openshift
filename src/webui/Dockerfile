FROM node:4-slim
RUN npm install express && npm install redis@3.1.2
COPY files files
COPY webui.js .
CMD node webui.js
