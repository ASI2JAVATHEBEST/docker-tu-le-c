ARG REACT_NODE_VERSION
FROM node:${REACT_NODE_VERSION}-alpine

# set working directory
WORKDIR /app

RUN npm install react-scripts@4.0.0 -g --silent

RUN pwd
RUN ls -al

# start app
CMD ["npm", "start"]
