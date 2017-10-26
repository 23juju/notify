# notify

## 功能说明
### 加入关闭与打开通知功能，并对container的样式做了改变

## 方法

### 关闭通知

+ 采用“button”键，点击“关闭”键

    onclick="document.getElementById   ('notify-container')
     .style.display='none'"


+ 20秒后自动关闭

+ 在container的页脚点击“我知道了”，也可关闭

     在container中增加footer，然后利用JQuery写法
        $(document).ready(function(){  
         $("#notify-footer").click(function(){
            $("#notify-container").hide();
          })
      })
     

### 打开通知

+ 点击“通知”键盘

    onclick="document.getElementById('notify-container')
        .style.display='block'"

### 样式改变
   
+ 设置背景颜色
+ 设置滚动
+ 放置鼠标改变背景色、字体大小