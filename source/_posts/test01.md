---
title: 有道云MarkDown功能测试体验
date: 2018-01-27 21:23:33
tags: 产品体验
---
# MarkDown体验测试


##### 公司说要整理一个自己的wiki知识库,想法很好.但是要自己开发一个?听说有道云markdown功能很好用,那我们来试试吧.

---
**先试试粗体吧**

*斜体字,可以的...*

~~下滑线,划重点就要用到它了~~

==标注功能,颜色默认黄色.诶...不可以改?我不喜欢黄黄黄的东西...这个希望可以改进...==

> 这是引用

> 恩,OK成功解析了.


- [x] 哇,还有复选列表
- [x] 看来我github的MD可以用这个了


- 无序列表.
- 没毛病儿!!!

1. 有序列表也少不了
2. 二
3. 三

- [ 括号列表] 
- [可以的 ] 


<html>
<!--什么?还支持html???-->
<div>什么?还支持html???路转粉啊</div>
</html>


[链接功能同样不能少](http://note.youdao.com/)

贴一个logo
![image](http://note.youdao.com/favicon.ico)


```
代码块功能,那就放点代码试试呗

const txt='are u ok!'


const what's up = (txt) => {
    alert("hello son ...")
}

要是能支持代码高亮就好了,后头研究有木有办法
```



header 1 | header 2
---|---
row 1 col 1 | row 1 col 2
row 2 col 1 | row 2 col 2

### 支持表格,耐思



```math
E = mc^2
```
### 支持数学公式,好想插一张爱因斯坦的大头



```
graph LR
哪里来的-->哪里去
```

```
sequenceDiagram
A->>B: How are you?
B->>A: Great!
```
## 一个志:完美!


```
gantt
dateFormat YYYY-MM-DD
section S1
T1: 2014-01-01, 9d
section S2
T2: 2014-01-11, 9d
section S3
T3: 2014-01-02, 9d
```


## 还有甘特图,锤子便签弱爆了


**缺陷总结:**
1. Mark功能不支持改颜色
2. 不能上传本地图片
3. 代码块功能不支持语法高亮

#### 总结完毕!