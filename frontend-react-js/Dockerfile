FROM node:16.18

ENV PROT=3000

COPY . /frontend-react-js
WORKDIR /frontend-react-js
RUN npm install
EXPOSE  ${PORT}
CMD ["npm","start" ]
