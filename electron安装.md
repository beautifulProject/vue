
# electron安装

> * 项目地址 https://github.com/SimulatedGREG/electron-vue

1. npm install -g vue-cli (安装vue脚手架)
2. vue init simulatedgreg/electron-vue my-project

* Application Name【填应用名称】
* Project description 【应用描述】
* Select which Vue plugins to install  【选择要安装的Vue插件。直接回车】
* Use linting with ESLint       【选n】
* Which eslint config would you like to use  【您要使用哪种eslint配置】
	 <p>Standard 标准的 （一般选这个）</p> 
	 <p>AirBNB </p>
	 <p>none 自行配置</p>
* Setup unit testing with Karma + Mocha? 【选N】
* Setup end-to-end testing with Spectron + Mocha?【选N】
* electron-builder  【选第一个】
* electron-packager 
* author 【作者】

#安装淘宝镜像
* 进入项目
* npm install  --registry=https://registry.npm.taobao.org
##自动构建
1. 项目地址 https://github.com/electron/electron-rebuild
2. npm install --save-dev electron-rebuild
3. ./node_modules/.bin/electron-rebuild
4. npm run dev
 