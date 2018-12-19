# 爱医 Android和iOS支持的html标签

Android使用的是 github上 zzhoujay/RichText（2.6k stars）
链接地址：https://github.com/zzhoujay/RichText

iOS使用的是 github上 Cocoanetics/DTCoreText（5.6k stars）
链接地址：https://github.com/Cocoanetics/DTCoreText

### 值支持的所有的CSS
style里面支持的属性
- text-align(left right center)
- color （Android 不支持red、green、black等预定好的颜色）
- background
- text-decoration
- text-indent
- font-size

### 支持的HTML标签

- br标签

```
你好<br/>我是br标签
```

Android | iOS
---|---
![image](https://github.com/Wisdozzh/markdown-images/blob/master/Html%20parser/Android/br.jpg)  | ![image](https://github.com/Wisdozzh/markdown-images/blob/master/Html%20parser/iOS/br.png) 

- p标签 支持style（上面的style都支持 并测试了color和font-size两个 CSS属性）
```
<p style=\"color:#000000; font-size:20px;\">这是一个段落。</p><p>这是另外一个段落。</p>
```

Android | iOS
---|---
![image](https://github.com/Wisdozzh/markdown-images/blob/master/Html%20parser/Android/p.jpg)  | ![image](https://github.com/Wisdozzh/markdown-images/blob/master/Html%20parser/iOS/p.png) 

- ul标签 支持style（上面的style都支持）
- li标签 支持style（上面的style都支持）

```
"<ul><li style=\"font-size:20px\">Coffee</li><li>Milk</li></ul> <ol><li>Coffee</li><li>Milk</li></ol> "
```

Android | iOS
---|---
![image](https://github.com/Wisdozzh/markdown-images/blob/master/Html%20parser/Android/ul_ol_li.jpg)  | ![image](https://github.com/Wisdozzh/markdown-images/blob/master/Html%20parser/iOS/ul_ol_li.png) 

- div标签 支持style（上面的style都支持）
- span标签 支持style(color、background、text-decoration、font-size)
- strong标签
- b标签
- em标签
- cite标签
- dfn标签
- i标签
- big标签
- small标签
- font标签 支持color、face
- blockquote标签 支持style（text-align、text-indent）
- t标签
- a标签
```
<a href="http://www.w3cschool.cn">这是一个链接</a>
```

Android | iOS
---|---
![image](https://github.com/Wisdozzh/markdown-images/blob/master/Html%20parser/Android/a.jpg)  | ![image](https://github.com/Wisdozzh/markdown-images/blob/master/Html%20parser/iOS/a.png) 

- u标签
- del标签
- s标签
- strike标签
- sup标签
- sub标签
- h1-h6标签 支持style（text-align、text-indent）
```
<h1>这是一个h1标题</h1><h2>这是一个h2标题</h2><h3>这是一个h3标题</h3><h4>这是一个h4标题</h4><h5>这是一个h5标题</h5><h6>这是一个h6标题</h6>
```

Android | iOS
---|---
![image](https://github.com/Wisdozzh/markdown-images/blob/master/Html%20parser/Android/h1_h6.jpg)  | ![image](https://github.com/Wisdozzh/markdown-images/blob/master/Html%20parser/iOS/h1_h6.png) 

- img标签 支持width height
```
<img src="https://desk-fd.zol-img.com.cn/t_s640x530c5/g5/M00/02/05/ChMkJlbKyaGIGGNjABT85XemdQ8AALIQQI-6pcAFPz9490.jpg" width="104" height="142">
```

Android | iOS
---|---
![image](https://github.com/Wisdozzh/markdown-images/blob/master/Html%20parser/Android/img.jpg)  | ![image](https://github.com/Wisdozzh/markdown-images/blob/master/Html%20parser/iOS/img.png) 

- code标签
- pre标签 换行
- test标签 支持style（text-align、text-indent）
- 整体的例子1

```
<span style="font-size:18px">微信支付凭证</span><br/>
<div style="text-align:center">
    <span style="font-size:14px; color:grey">付款金额</span><br/>
<strong><span style="text-align:center; font-size:22px; text-align:center;">¥16.94</span></strong></div><br/>
<span style="color:grey; font-size:14px">收款方　　</span> 
<span style="font-size:16px"></span>丁少波<br/>
<span style="color:grey; font-size:14px">交易状态　</span> 
<span style="font-size:16px"></span>支付成功，对方已首款<br/><br/>
查看账单详情<br/>
```
Android | iOS
---|---
![image](https://github.com/Wisdozzh/markdown-images/blob/master/Html%20parser/Android/demo1.jpg) | ![image](https://github.com/Wisdozzh/markdown-images/blob/master/Html%20parser/iOS/demo1.png)




