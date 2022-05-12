FROM node:16.15.0

RUN apt-get install net-tools
WORKDIR /var/www/app
COPY ./license-plate /var/www/app
RUN npm install
# expose ports
EXPOSE 3000
EXPOSE 3009
CMD ["npm", "start"]