# 搜狗emoji自定义词库

## emoji

网站 Emojipedia 创始人 Jeremy Burge 曾经这样说过，“ emoji 能让我们的个性在文字对话中得以表达”。是的，没有什么文字比图片来得更加直接了。

emoji 从日本开创，美国发展，已经能被大多数现代计算机系统所兼容的Unicode编码采纳，比如在 Typora 可以简单地用 `:smile:` 来表达 emoji，一般情况 emoji 都是英文检索

那么问题在于怎样在电脑上用**中文输入**emoji表情

简单搜索后发现，输入 emoji 的方式有：

1. win10 及以上自带的 `win + .` 或者 `win + ;` 
2. 从 emoji 站（像 [EmojiAll中文](https://www.emojiall.com/zh-hans) ）复制粘贴
3. uTools 里的emoji插件

## 思路

但是使用后感觉还是不够便捷，于是想到个办法：把常用的 emoji 作为自定义短语配置到搜狗输入法中

这样一来符合自己的输入法习惯，二来还能根据需要自由定制触发词

搜狗输入法`自定义短语设置`加入已设定好 emoji，可行！

## 设置

先从 [一把刀《中文字典》📕 ](https://zhongwenzidian.18dao.cn/emoji) 拷贝带有中文释义的 emoji 

进行筛选得到常用的表情和简化的释义

然后把中文转拼音方便中文检索，调整成自定义短语设置的格式

比如 `🍗:家禽的腿` 不太符合日常习惯，把这改为 `鸡腿` ，最终转为 `jitui,3=🍗` ，这样在我们输入`jitui` 时候选框中就会出现🍗

最后只要在搜狗输入法中设置好，就能开始用啦

![image-20220119142813755](https://gitee.com/u1805/pic-md1/raw/master/202201191428809.png)

![image-20220119142844755](https://gitee.com/u1805/pic-md1/raw/master/202201191428794.png)

打开后在最下面复制粘贴好，保存
