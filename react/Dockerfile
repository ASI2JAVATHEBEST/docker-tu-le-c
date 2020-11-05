ARG REACT_NODE_VERSION
FROM node:${REACT_NODE_VERSION}-alpine

# set working directory
WORKDIR /app

RUN npm install react-scripts@3.4.1 -g

# start app
CMD ["npm", "start"]
