FROM node:14

# WORKDIR /home/adrienm/cours/M1/MicroService/exam
WORKDIR /usr/src/exam_docker
COPY . .

RUN npm install


EXPOSE 8080

CMD ["node", "./src/count-server.js"]




