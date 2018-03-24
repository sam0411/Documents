## Node Reference
https://github.com/nodejs/help/issues/579

## Node Installation under Linux
axel -n 10 https://nodejs.org/dist/v8.9.3/node-v8.9.3-linux-x64.tar.gz

tar -xf node-v8.9.3-linux-x64.tar.gz

cp ./bin/node /usr/local/bin/

sudo ln -s /home/geofferyhood/Software/node-v8.6.0-linux-x64/lib/node_modules/npm/bin/npm-cli.js /usr/local/bin/npm

sudo ln -s /home/geofferyhood/Software/node-v8.6.0-linux-x64/lib/node_modules/npm/bin/npx-cli.js /usr/local/bin/npx


## Node Command
node -v

npm -v


## npm command
npm init

npm list -g

npm uninstall webpack -g

npm install webpack@3.5.1 -g

[//]: # 'npm的start命令是一个特殊的脚本名称，其特殊性表现在，在命令行中使用npm start就可以执行其对于的命令，如果对应的此脚本名称不是start，想要在命令行中运行时，需要这样用npm run {script name}如npm run build.'
npm start

