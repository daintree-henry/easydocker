FROM node:14
WORKDIR app
ENV COLOR=red
COPY ./ /app/
RUN npm install 
USER node
EXPOSE 3000
CMD ["npm", "start"]