# 清欢的html入门笔记1
## html的作者是Tim Berners-Lee
## html的起手:!+tab
````
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <mate http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
</head>
<body>   
</body>
</html>
````
## 章节标签
   h1~h6:标题  
   section：章节  
   article：文章   
   p：段落  
   header：头部  
   footer：脚部  
   main：主要内容  
   aside：旁支内容  
   div：划分区域
##  全局属性
   Class：标签分类，更多时候是一个标 记  
   Contenteditable：用户可编辑，直接编辑页面  
   Hidden：看不见  
   Id：标记，全页面唯一的用id，非特殊情况不用id用class  
   Style：样式，优先级比CSS高，JS可以覆盖HTML  
   Tabindex：控制tab的顺序，如果=0的话，是最后一个，-1是永远访问不到  
   Title：显示鼠标放上去，未点击的时候所显示的提示内容
##  内容标签
   ol+li:有序列表  
   ul+li:无序列表  
   dl+dt+dd：描述列表，dt被描述的对象，dd描述的内容  
   pre：保留所有html 空格，回车，tab  
   code：code里面的字是等宽的，一般用来写代码  
   hr：水平分割线  
   br：换行  
   a：超链接，默认当前页面打开，target=“-blank”就是新页面打开  
   em：语气上强调很重要  
   strong：内容本身很重要     
   quote：引用  
   blockquote：换行引用  

