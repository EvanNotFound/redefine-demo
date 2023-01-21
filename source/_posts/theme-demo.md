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

## Font Awesome 6.1.0

**Solid:** <i class="fa-solid fa-house"></i> <i class="fa-solid fa-envelope"></i>

**Regular:** <i class="fa-regular fa-house"></i> <i class="fa-regular fa-envelope"></i>

**Light:** <i class="fa-light fa-house"></i> <i class="fa-light fa-envelope"></i>

**Thin:** <i class="fa-thin fa-house"></i> <i class="fa-thin fa-envelope"></i>

**Duotone:** <i class="fa-duotone fa-house"></i> <i class="fa-duotone fa-envelope"></i>

<link href="/css/thin.min.css" rel="stylesheet" type="text/css">

<link href="/css/light.min.css" rel="stylesheet" type="text/css">



## 大号提示块

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

## 笔记系列

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

## Mermaid JS

```markdown
	sequenceDiagram
    Alice->>John: Hello John, how are you?
    loop Healthcheck
        John->>John: Fight against hypochondria
    end
    Note right of John: Rational thoughts!
    John-->>Alice: Great!
    John->>Bob: How about you?
    Bob-->>John: Jolly good!
```

```mermaid
sequenceDiagram
    Alice->>John: Hello John, how are you?
    loop Healthcheck
        John->>John: Fight against hypochondria
    end
    Note right of John: Rational thoughts!
    John-->>Alice: Great!
    John->>Bob: How about you?
    Bob-->>John: Jolly good!
```



```markdown
  gantt
    dateFormat  YYYY-MM-DD
    section Section
    Completed :done,    des1, 2014-01-06,2014-01-08
    Active        :active,  des2, 2014-01-07, 3d
    Parallel 1   :         des3, after des1, 1d
    Parallel 2   :         des4, after des1, 1d
    Parallel 3   :         des5, after des3, 1d
    Parallel 4   :         des6, after des4, 1d
```



```mermaid
gantt
	dateFormat  YYYY-MM-DD
  section Section
  Completed :done,    des1, 2014-01-06,2014-01-08
  Active        :active,  des2, 2014-01-07, 3d
  Parallel 1   :         des3, after des1, 1d
  Parallel 2   :         des4, after des1, 1d
  Parallel 3   :         des5, after des3, 1d
  Parallel 4   :         des6, after des4, 1d

```













```markdown
  stateDiagram
    [*] --> Still
    Still --> [*]
    Still --> Moving
    Moving --> Still
    Moving --> Crash
    Crash --> [*]
```





```mermaid
stateDiagram
	[*] --> Still
  Still --> [*]
  Still --> Moving
  Moving --> Still
  Moving --> Crash
  Crash --> [*]
```



```markdown
pie
	"Dogs" : 386
  "Cats" : 85
  "Rats" : 15
```





```mermaid
pie
	"Dogs" : 386
  "Cats" : 85
  "Rats" : 15
```





```markdown
journey
  title My working day
  section Go to work
    Make tea: 5: Me
    Go upstairs: 3: Me
    Do work: 1: Me, Cat
  section Go home
    Go downstairs: 5: Me
    Sit down: 3: Me
```





```mermaid
journey
  title My working day
  section Go to work
    Make tea: 5: Me
    Go upstairs: 3: Me
    Do work: 1: Me, Cat
  section Go home
    Go downstairs: 5: Me
    Sit down: 3: Me
```



