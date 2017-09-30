# 修饰符
1.	.lazy ：当鼠标离开input框的时候触发
2. .number：输入的数字转成字符串
3. .trim:去除首尾空格
#v-test & v-html

* v-test :写入元素的内容，对HTML标签会做解析
* v-html :写入元素的内容，不会对HTML标签做解析

# v-on
* v-on :绑定事件监听器，写法v-on:click,简写@click

# v-model

* 	v-model :数据和页面双向绑定

# v-bind
* 给元素绑定属性，例如给a标签的src绑定图片路径，
* 实例：
```
<body>
    <div id="app">
        <img v-bind:src="imageSrc">
    </div>
</body>
<script type="text/javascript">
    var app = new Vue({
        el:"#app",
        data:{
            imageSrc:"https://ss0.baidu.com/6ONWsjip0QIZ8tyhnq/it/u=2959797186,2426236074&fm=173&s=B48340B64828B45B52775F900300608D&w=500&h=344&img.JPEG"
        },
    })
</script>
```
简写 :src

