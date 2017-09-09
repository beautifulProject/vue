# vue安装
1.  安装最新的node.js
2.  进入[vue官网][1]下载，有2个版本
*	开发版本：包含完整的警告和调试模式（非压缩）
*	生产版本：压缩，并且删除了警告

## 创建项目
1.  新建一个目录
2.  在目录里新建assets(放css和js文件)
3.  在目录里新建example(放写代码的文件)
4.  在目录里新建index.html

## 生成项目 npm install -g live-server(项目名称)
## 生成好后执行 live-server(项目名称) 启动

## v-if  v-else（判断条件）
## v-show (显示或者隐藏，v-show是改变元素的disabled)
```
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>v-if，v-show实例</title>
    <script type="text/javascript" src="../assets/js/vue.js"></script>

</head>
<body>
<div id="app">
    <div v-if="isLogin">已经登录</div>
    <div v-else>未登录</div>
    <div v-show="vShow">需要隐藏或者显示的元素</div>
</div>
<script type="text/javascript">
    var app = new Vue({
        el:"#app",
        data:{
            isLogin:true,
            vShow:true
        }
    });
</script>
</body>
</html>
```
* el: 实例提供挂载元素(通俗的说就是操作区域元素)
* data: Vue实例的数据对象 





[1]:	https://cn.vuejs.org/v2/guide/installation.html