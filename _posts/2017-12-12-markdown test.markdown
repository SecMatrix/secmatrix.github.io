---
layout:     post
title:      "Markdown 测试"
subtitle:   "markdown"
date:       2017-12-12 17:57:18
author:     "Zihoo"
header-img: "img/post-bg-2017.jpg"
catalog: true
tags:
    - Markdown
---

> “第二篇Test ”



## 流程图

```flow
st=>start: Start
op=>operation: Your Operation
cond=>condition: Yes or No?
e=>end

st->op->cond
cond(yes)->e
cond(no)->op
```

## 甘特图

```gantt
    title gantt
    section one
        A       :a1, 2016-06-22, 3d
        B     :after a1, 5d
        C       : 5d
    section two
        D      :2016-07-05  , 5d
        E      :2016-07-08, 10d
        F          :2016-07-15, 10d
        D          :2016-07-22, 5d
```

## 表格

| 项目        | 价格   |  数量  |
| --------   | -----:  | :----:  |
| 计算机     | \$1600 |   5     |
| 手机        |   \$12   |   12   |
| 管线        |    \$1    |  234  |

## LaTex
![](http://latex.codecogs.com/gif.latex?E=mc^2)

## 高亮代码

```python
if __name__ == '__main__':
    # A comment
    print 'hello world'
```
```c
int main()
{
  printf("%d\n",13);
  return 0;
}
```

## 图片

![这真的是图片](http://imgsrc.baidu.com/imgad/pic/item/267f9e2f07082838f76cce1db299a9014c08f152.jpg "这是图片")
---
