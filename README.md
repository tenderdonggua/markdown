# markdown
该文件用来测试和展示书写README的各种markdown语法。GitHub的markdown语法在标准的markdown语法基础上做了扩充，称之为`GitHub Flavored Markdown`。简称`GFM`，GFM在GitHub上有广泛应用，除了README文件外，issues和wiki均支持markdown语法。

---
| Author | chennanqiudong |
| --- | --- |
| E-mail | 694393133@qq.com | 
---

# 目录
- [横线](#横线)
- [标题](#标题)
- [文本](#文本)
    - 普通文本
    - 单行文本
    - 多行文本
    - 文字高亮
    - 换行
    - 斜体
    - 粗体
    - 删除线
- [图片](#图片)
    - 来源于网络的图片
    - GitHub仓库中的图片
- [链接](#链接)
    - 文字超链接
        - 链接外部URL
        - 链接本仓库里的URL
    - 锚点
    - 图片链接
- [列表](#列表)
    - 无序列表
    - 有序列表
    - 复选框列表
- [块引用](#块引用)
- [代码高亮](#代码高亮)
- [表格](#表格)
- [表情](#表情)
- [diff语法](#diff语法)

# 横线
---
***、---、___可以显示横线效果

# 标题
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题

# 文本
### 普通文本
这是普通文本
### 单行文本
    在一行开头加入1个Tab或者4个空格。
### 多行文本
    在连续几行的文本开头加入1个Tab或者4个空格。
    在连续几行的文本开头加入1个Tab或者4个空格。
    在连续几行的文本开头加入1个Tab或者4个空格。
```
使用一对各三个的反引号
使用一对各三个的反引号
使用一对各三个的反引号
```
### 文字高亮
文字高亮功能能使行内部分`文字高亮`，使用一对反引号。  
```
    `海底捞` `小龙坎` `蜀大侠`
```
### 换行
直接回车不能换行，  
可以在上一行文本后面补两个空格，  
这样下一行的文本就换行了。  

或者就是在两行文本直接加一个空行。

也能实现换行效果，不过这个行间距有点大。
#### 斜体、粗体、删除线
|语法|效果|
|----|-----|
|`*斜体1*`|*斜体1*|
|`_斜体2_`| _斜体2_|
|`**粗体1**`|**粗体1**|
|`__粗体2__`|__粗体2__|
|`这是一个 ~~删除线~~`|这是一个 ~~删除线~~|
|`***斜粗体1***`|***斜粗体1***|
|`___斜粗体2___`|___斜粗体2___|
|`***~~斜粗体删除线1~~***`|***~~斜粗体删除线1~~***|
|`~~***斜粗体删除线2***~~`|~~***斜粗体删除线2***~~|
    斜体、粗体、删除线可混合使用
    
# 图片
基本格式：    

    ![alt](URL title)
    
alt和title即对应HTML中的alt和title属性（都可省略）：
- alt表示图片显示失败时的替换文本
- title表示鼠标悬停在图片时的显示文本（注意这里要加引号）   

URL即图片的url地址，如果引用本仓库中的图片，直接使用相对路径就可了，如果引用其他github仓库中的图片要注意格式，即：仓库地址/raw/分支名/图片路径，如：

    https://github.com/tenderdonggua/markdown/master/flower.JPG
    
| # | 语法 | 效果 |
|---|---|---|
|1|`![baidu](http://www.baidu.com/img/bdlogo.gif "百度logo")`|![baidu](http://www.baidu.com/img/bdlogo.gif "百度logo")|
|2|`![][flower]`|![][flower]|

    [flower]:https://github.com/tenderdonggua/markdown/blob/master/flower.JPG

[flower]:https://github.com/tenderdonggua/markdown/blob/master/flower.JPG








