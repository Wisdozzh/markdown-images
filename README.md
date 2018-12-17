# 爱医 Android和iOS支持的html标签

Android使用的是 github上 zzhoujay/RichText（2.6k stars）
链接地址：https://github.com/zzhoujay/RichText

iOS使用的是 github上 Cocoanetics/DTCoreText（5.6k stars）
链接地址：https://github.com/Cocoanetics/DTCoreText

### 值支持的所有的CSS
style里面支持的属性
- text-align(left right center)
- color
- background
- text-decoration
- text-indent
- font-size

### 支持的HTML标签

- br标签

```

```

Android | iOS
---|---
row 1 col 1 | row 1 col 2
row 2 col 1 | row 2 col 2



- p标签 支持style（上面的style都支持）
- ul标签 支持style（上面的style都支持）
- li标签 支持style（上面的style都支持）
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
- u标签
- del标签
- s标签
- strike标签
- sup标签
- sub标签
- h1-h6标签 支持style（text-align、text-indent）
- img标签 支持width height
- code标签
- pre标签 换行
- test标签 支持style（text-align、text-indent）
- 整体的例子

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
row 2 col 1 | row 2 col 2


