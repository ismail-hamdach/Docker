# This image based on node environement 
FROM node

# Specify workdirectory for the app, where all the following command will get executed
WORKDIR /app

# Copy all folders, sub folders and files in the current directory on the host to the image, /app. 
COPY . ./

# This command will install the package in workdirectory /app 
# This command get executed only during the build of the image
RUN npm install

# Open the port 80 in the machine
EXPOSE 80

# This commad get executed everytime the container is get started
CMD [ "node", "server.js" ] 
