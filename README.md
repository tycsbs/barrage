# barrage 运行飞快的弹幕插件 v-1.0.0
> barrage 是一款基于Jquery的弹幕插件，插件融合CSS3 动画效果，有效提高了弹幕的运行效果，流畅并且高效！
### 插件引入
```
<script src="js/jquery.js"></script>
<script src="js/barrage.js"></script>
```
### 使用方法
```
<script>
    $(function(){
        var barrage_box = $("body")
        setInterval(function(){
            barrage_box.barrage()
        },1000)
    })
</script>
```
### 参数配置
barrage 默认提供对象型配置参数
```
 var option = {
        avatar: "../image/avatar@24.png",//头像路径
        msg: "Hello World",//弹幕文字信息
        close: false,//是否显示关闭按钮
        time:8//流动时间,不设置则默认随机时间 5-10s 范围
    }

     barrage_box.barrage(option)
```

