---
title: 主题样式 Demo
date: 2022-10-02 19:07:05
tags: "demo"
thumbnail: https://evan.beee.top/img/redefine-1-final.webp
sticky: 999
---

# H1 标题

## H2 标题

### H3 标题

#### H4标题

##### H5 标题

###### H6 标题

**加粗**

*斜体*

~~删除线~~

这是一段文本

![Screen Shot 2022-10-02 at 9.26.37 PM](https://evan.beee.top/img/Screen%20Shot%202022-10-02%20at%209.26.37%20PM.png)

`行内代码`

```
代码块
```

```python
print("代码高亮")
```



# 功能展示

## Font Awesome Pro v6.2.1

**Solid:** <i class="fa-solid fa-house"></i> <i class="fa-solid fa-envelope"></i> <i class="fa-solid fa-camera-retro"></i> <i class="fa-solid fa-cart-shopping"></i>

**Regular:** <i class="fa-regular fa-house"></i> <i class="fa-regular fa-envelope"></i> <i class="fa-regular fa-camera-retro"></i> <i class="fa-regular fa-cart-shopping"></i>

**Light:** <i class="fa-light fa-house"></i> <i class="fa-light fa-envelope"></i> <i class="fa-light fa-camera-retro"></i> <i class="fa-light fa-cart-shopping"></i>

**Thin:** <i class="fa-thin fa-house"></i> <i class="fa-thin fa-envelope"></i> <i class="fa-thin fa-camera-retro"></i> <i class="fa-thin fa-cart-shopping"></i>

**Duotone:** <i class="fa-duotone fa-house"></i> <i class="fa-duotone fa-envelope"></i> <i class="fa-duotone fa-camera-retro"></i> <i class="fa-duotone fa-cart-shopping"></i>

**Sharp Solid:** <i class="fa-sharp fa-solid fa-house"></i> <i class="fa-sharp fa-solid fa-envelope"></i> <i class="fa-sharp fa-solid fa-camera-retro"></i> <i class="fa-sharp fa-solid fa-cart-shopping"></i>

## Note Large大号提示块

{% btn center large::Note Large大号提示块文档::https://redefine-docs.ohevan.com/docs/advanced/writing-modules/note-module::fa-solid fa-book %}

{% notel default 信息 %}
换行测试
换行测试
换行测试
{% endnotel %}

{% notel blue 提示 %}
换行测试
换行测试
换行测试
{% endnotel %}

{% notel green 自定义标题 %}
换行测试
换行测试
换行测试
{% endnotel %}

{% notel yellow 自定义标题 %}
换行测试
换行测试
换行测试
{% endnotel %}

{% notel orange 自定义标题 %}
换行测试
换行测试
换行测试
{% endnotel %}

{% notel red 自定义标题 %}
换行测试
换行测试
换行测试
{% endnotel %}

## Note 小号提示块

{% btn center large::Note 小号提示块文档::https://redefine-docs.ohevan.com/docs/advanced/writing-modules/note-module::fa-solid fa-book %}

{% note  %}
默认 提示块标签
{% endnote %}

{% note default  %}
default 提示块标签
{% endnote %}

{% note primary  %}
primary 提示块标签
{% endnote %}

{% note success  %}
success 提示块标签
{% endnote %}

{% note info  %}
info 提示块标签
{% endnote %}

{% note warning  %}
warning 提示块标签
{% endnote %}

{% note danger  %}
danger 提示块标签
{% endnote %}

{% note red fa-bolt%}
自定义提示块标签
{% endnote %}

## Folding 折叠模块

{% btn center large::Folding 折叠模块文档::https://redefine-docs.ohevan.com/docs/advanced/writing-modules/folding::fa-solid fa-book %}

{% folding yellow::Folding 测试： 点击查看更多 %}

{% note danger  %}
danger 提示块标签
{% endnote %}

{% note tip  %}
tip 提示块标签
{% endnote %}

{% endfolding %}



{% folding green::Folding 测试： 点击查看更多 %}

{% note danger  %}
danger 提示块标签
{% endnote %}

{% note tip  %}
tip 提示块标签
{% endnote %}

{% endfolding %}



{% folding blue::Folding 测试： 点击查看更多 %}

啊啊啊啊啊

{% note danger  %}
danger 提示块标签
{% endnote %}

{% note tip  %}
tip 提示块标签
{% endnote %}

{% endfolding %}

## Tabs 分栏模块

{% btn center large::Tabs 分栏模块文档::https://redefine-docs.ohevan.com/docs/advanced/writing-modules/tabs::fa-solid fa-book %}

{% tabs First unique name %}
<!-- tab First Tab-->
**This is Tab 1.**
<!-- endtab -->

<!-- tab Second Tab-->
**This is Tab 2.**

This is Tab 2.

<!-- endtab -->

<!-- tab Third Tab-->
**This is Tab 3.**

This is Tab 3.

This is Tab 3.

<!-- endtab -->
{% endtabs %}

## Button 按钮模块

不设置任何参数的 {% btn 按钮:: / %} 适合融入段落中。

regular 按钮适合独立于段落之外：

{% btn regular::示例博客::https://www.ohevan.com::fa-solid fa-play-circle %}

{% btn regular::示例博客::https://www.ohevan.com::fa-solid fa-play-circle %}

large 按钮更具有强调作用，建议搭配 center 使用：

{% btn center large::Button 按钮模块 开始使用::https://redefine-docs.ohevan.com/docs/advanced/writing-modules/buttons::fa-solid fa-book %}



