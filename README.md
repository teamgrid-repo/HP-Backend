# NodeJs-MongoDB-Mongoose-Express-SocketIO-Boilerplate
## _with CICD_


## Installation

This boilerplate requires [Node.js](https://nodejs.org/) v12+ to run.

Install the dependencies and devDependencies and start the server.

```sh
cd NodeJs-MongoDB-Mongoose-Express-SocketIO-Boilerplate
nano .env [add required variables -> I have added .env.local for example]
npm i
npm start
```

How to manage in production mode? [Run, Delete, View Logs etc.]

```sh
npm i pm2 -g
pm2 start production.config.json
pm2 startup systemd
pm2 save
pm2 logs [to check all logs]
pm2 delete all [to delete all processes attached with pm2]
```

#
# Thank you :)
#
## Feel free to connect with me on: