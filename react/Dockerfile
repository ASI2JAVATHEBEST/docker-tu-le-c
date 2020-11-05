ARG REACT_NODE_VERSION
FROM node:${REACT_NODE_VERSION}-alpine

# set working directory
WORKDIR /app

# install app dependencies
RUN npm install --silent
RUN npm install react-scripts@4.0.0 -g --silent

# start app
CMD ["npm", "start"]
