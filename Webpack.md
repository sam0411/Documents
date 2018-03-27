## Webpack Reference
https://www.jianshu.com/p/42e11515c10f
https://github.com/vikingmute/webpack-for-fools
https://vikingmute.gitbooks.io/webpack-for-fools/content/


## webpack简单点来说就就是一个配置文件，所有的魔力都是在这一个文件中发生的。 这个配置文件主要分为三大块  
1、entry 入口文件 让webpack用哪个文件作为项目的入口  
2、output 出口 让webpack把处理完成的文件放在哪里  
3、module 模块 要用什么不同的模块来处理各种类型的文件  


## webpack有几个比较基本的概念：
1、loaders：通过不同的loaders，webpack可以处理各式各样的文件，然后打包到一个文件中（比如bundle.js)； 
2、plugins：plugins是为了拓展webpack的功能的，和loaders不同的是，loader是用来处理单个文件的(比如json-loader处理.json,sass-loader处理.scss)，但是plugins是直接对整个构建过程进行处理（比如自动生成html文件的html-webpack-plugin）； 
3、others: 这些我也不知道要归到哪里去，但是在配置中也是必不可少，包括webpack-dev-server/source-map等等，后面会具体说； 
4、配置文件：我这个小项目包括的文件有.babelrc(用来处理babel)，webpack.config.js(webpack项目基础配置文件)，package.json(这个文件会记录所有的devDependencies）。  


## Command
npm install webpack -g  
npm install webpack --save-dev  
npm install webpack-cli -g  
npm install webpack-cli --save-dev  
npm install webpack-dev-server --save-dev  

<font color=#0099ff>run package.json -> script -> server</font>   
npm run server