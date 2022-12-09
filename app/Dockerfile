# Current version of image(node)
FROM node:17


# Copies layers to new path 
WORKDIR /app


# Adds additional layers to image
COPY . .


# Installs dependecies needed to run in image 
RUN npm install 


# port 
EXPOSE 4001 


# Makes the image after copying and running node
CMD ["node", "server.js"]

