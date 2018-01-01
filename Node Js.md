#Node Reference
https://github.com/nodejs/help/issues/579

#Node Installation under Linux
$ axel -n 10 https://nodejs.org/dist/v8.9.3/node-v8.9.3-linux-x64.tar.gz
$ tar -xf node-v8.9.3-linux-x64.tar.gz
$ cp ..bin/node /usr/local/bin/
$ sudo ln -s /home/geofferyhood/Software/node-v8.9.3-linux-x64/lib/node_modules/npm/bin/npm-cli.js /usr/local/bin/npm
$ sudo ln -s /home/geofferyhood/Software/node-v8.9.3-linux-x64/lib/node_modules/npm/bin/npm-cli.js /usr/local/bin/npx

#Node Command
$ node -v
$ npm -v