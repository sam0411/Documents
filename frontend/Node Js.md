## Node Reference
https://github.com/nodejs/help/issues/579

## Node Installation under Linux
axel -n 10 https://nodejs.org/dist/v8.9.3/node-v8.9.3-linux-x64.tar.gz  
tar -xf node-v8.9.3-linux-x64.tar.gz  
cp ./bin/node /usr/local/bin/  
sudo ln -s /home/geofferyhood/Software/node-v8.6.0-linux-x64/lib/node_modules/npm/bin/npm-cli.js /usr/local/bin/npm  
sudo ln -s /home/geofferyhood/Software/node-v8.6.0-linux-x64/lib/node_modules/npm/bin/npx-cli.js /usr/local/bin/npx  


## CNPM
npm install cnpm -g --registry=https://registry.npm.taobao.org  

npm config set registry http://registry.npmjs.org   
npm config set registry https://registry.npm.taobao.org  
npm info underscore  


## Node Command
node -v  
npm -v  


## npm command
sass_binary_site=https://npm.taobao.org/mirrors/node-sass/  
phantomjs_cdnurl=https://npm.taobao.org/mirrors/phantomjs/  
electron_mirror=https://npm.taobao.org/mirrors/electron/  
registry=https://registry.npm.taobao.org  

npm init  
npm list -g  
npm uninstall webpack -g  
npm install webpack@3.5.1 -g  

<font color=#0099ff>npm的start命令是一个特殊的脚本名称，其特殊性表现在，在命令行中使用npm start就可以执行其对于的命令，如果对应的此脚本名称不是start，想要在命令行中运行时，需要这样用npm run {script name}如npm run build.</font>   
npm start  


## node components
path - Handle absolute / relevant path  

process - Node process information, for example, process.env