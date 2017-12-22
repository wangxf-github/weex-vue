# weex-vue
vue的移动开发平台weex

环境搭建：需要node环境
官方地址：http://weex.apache.org/cn/guide/set-up-env.html

brew install node

//打包工具
npm install -g weexpack

//项目管理工具
npm install -g weex-toolkit


1.初始化项目
git clone https://github.com/wangxf-github/weex-vue.git

2.通过npm安装依赖包
cd  weex-demo&npm install

3.添加平台android or ios
weex platform add android

4.cd platform/android
weexpack weexplugin platform android

5.weex run android