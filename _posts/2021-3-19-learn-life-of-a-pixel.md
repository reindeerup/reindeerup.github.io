---
layout: mypost
title: Life of a pixel
categories: [前端] 
---

> 视频https://www.bilibili.com/video/BV12b411w78Y?from=search&seid=11322012851134768773
>
> 文字https://segmentfault.com/a/1190000016335571

## WHY READ IT

浏览器渲染页面可以分为哪些阶段性过程？

了解HTML,CSS,JS分别在哪个部分起了作用，浏览器是以怎样的逻辑解析并渲染出画面的？

浏览器是怎么样实现对用户的操作的响应的？



### web content的基本内容

HTML CSS JS

webcontents 

渲染引擎 blink

![image-20210320143425531](C:\Users\Admin\AppData\Roaming\Typora\typora-user-images\image-20210320143425531.png)



目标：1.将HTML  CSS JS 转化为正确的openGL 调用

2.响应

 

![image-20210320235621024](C:\Users\Admin\AppData\Roaming\Typora\typora-user-images\image-20210320235621024.png)





HTMLdocument parser

·解析html文件的标签，依据结构生成对象模型（即DOM） 

​	dom完成的任务包括1页面的内部表示，2为js提供查询或修改渲染的API 



css选择的相应的dom





layout tree

![image-20210321001356798](C:\Users\Admin\AppData\Roaming\Typora\typora-user-images\image-20210321001356798.png)

layout tree的update



绘制的顺序





raster

GPU 





  change

