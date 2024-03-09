+++
title = "自用短代码汇总"
date = "2024-03-09"
description = "写文章可能会用到的短代码。"
tags = [
    "装修",
]
categories = [
    "搭建日记",
]
series = ["Themes Guide"]
aliases = ["migrate-from-jekyl"]
image = "pawel-czerwinski-8uZPynIu-rQ-unsplash.jpg"
+++

## 小标题

# H1
## H2
### H3
#### H4
##### H5
###### H6

## 零碎的格式

`小方块`

**加粗**

<mark>高光笔</mark>


 — <cite>带注释的文字[^1]</cite> 

[^1]: 脚注内容

<abbr title="Graphics Interchange Format">下方带虚线</abbr>

{{< underline color="#ffdd00" content="彩色下划线" >}}


上角标下角标： H<sub>2</sub>O，X<sup>n</sup>


## 表格

   Name | Age
--------|------
    kaede | 16
  Akira | 17

#### 更多表格

| 斜体   | 加粗     | 引用框   |
| --------  | -------- | ------ |
| *斜体* | **加粗** | `引用框` |

| A                                                        | B                                                                                                             | C                                                                                                                                    | D                                                 | E                                                          | F                                                                    |
|----------------------------------------------------------|---------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------|------------------------------------------------------------|----------------------------------------------------------------------|
| 我也不知道 | 什么情况下 | 会用到这种 | 电子表格 | 总之 | 先攒着吧 |

## 插入代码

#### 自带高亮 

{{< highlight html >}}
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Example HTML5 Document</title>
</head>
<body>
  <p>Test</p>
</body>
</html>
{{< /highlight >}}

#### 引号引用
{{< quote >}} 三月，因久旱不雨，苏轼赴郿，祈雨于太白山之上清宫。数日后，虽有微雨，父老以为不足，于是，再陪宋太守亲往祭祷，回程路上，便见道中有云气自山中来，如群马奔突而至车座左右，苏轼一时好奇心起，开笼收云归家，作《攓云篇》。 {{< /quote >}} 

#### 彩色标签块

{{< notice notice-warning >}}
Warning：红色warning
{{< /notice >}}

{{< notice notice-info >}}
info：黄色notice
{{< /notice >}}

{{< notice notice-note >}}
note：蓝色notice
{{< /notice >}}

{{< notice notice-tip >}}
tip：绿色tip
{{< /notice >}}



## 列表

#### 数字列表

1. First item
2. Second item
3. Third item

#### 圆点列表

* Fruit
  * Apple
  * Orange
  * Banana
* Dairy
  * Milk
  * Cheese
