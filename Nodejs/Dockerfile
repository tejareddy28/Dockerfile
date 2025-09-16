From node:16
WORKDIR /appjs '''for node/python images we dont have specific path so we create own path to store the code'''
COPY package*.json ./
RUN npm install ''' node package manager npm is used in node to install the dependenices'''
COPY ..
EXPOSE 80
CMD ["node", "index.js"]
