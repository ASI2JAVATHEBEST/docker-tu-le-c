ARG REACT_NODE_VERSION
FROM node:${REACT_NODE_VERSION}-alpine

WORKDIR /var

RUN npm install --silent
RUN npm install react-scripts@4.0.0 -g --silent

# set working directory
WORKDIR /app

# start app
CMD ["npm", "start"]
