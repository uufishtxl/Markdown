# demo4

## 混合强调样式

基本强调样式

- **加粗**  
- *倾斜*  
- ~~删除~~  

混合强调样式  

- ***加粗倾斜***  
- **~~加粗删除~~**  
- ~~*倾斜删除*~~
- ~~***加粗倾斜删除***~~    

## 图片链接

基本文本链接：  

    [链接文字](URL)

[百度](http://www.baidu.com)

基本图片：

    ![alt](URL text)
    
![baidu](https://www.baidu.com/img/bd_logo1.png?where=super "百度网站")

图片链接

[![baidu][baidu_logo]][baidu]

## 引用链接的问题

基本引用链接的用法：  

good：  
[百度][baidu]  
[百度网站][baidu]

not good（自引用）：  
[百度]  
[百度网站]

## 多级列表

- 问题1：如何打断：空行不行，需要文字段落才能打断

1. item1  
    1. item 1.1  
    2. item 1.2  
2. item2  

打断列表，下面从1开始进行编号：

3. item3  

- 问题2：打断的列表如何继续编号（利用4个空格的缩进，让文本段落变成缩进段落）

1. item1  
    1. item 1.1  
    2. item 1.2  
2. item2  

    不打断列表，继续编号：

3. item3  


<! -- 以下是本文中的链接 -->
[baidu]: http://www.baidu.com
[baidu_logo]: https://www.baidu.com/img/bd_logo1.png?where=super)
[百度]: http://www.baidu.com
[百度网站]: http://www.baidu.com