# markdown 语法 

[返回首页](index.html)

### Headers

```
使用#号获得标题效果
#一级标题
##二级标题
```



### Emphasis 强调

```
使用*或者_获得强调效果
效果：使用一个*的效果
使用两个*的效果
使用一个_的效果
使用个_的效果
```

效果：使用一个**的效果:*
使用两个***的效果**
使用一个__的效果_
使用2个___的效果__

#### Unordered 无序列表

```
* Item 1
* Item 2
	* Item 2a
	* Item 2b
```

* Item 1
* Item 2
  * Item2a
  * Item2b

#### Ordered 有序列表

```
1. Item1
2. Item2
	1. Item2c
	2. Item3c
```

1. Item1
2. Item2
   1. Item2c
   2. Item3c

### Images 图片

```
![aaaa](../img/my.png)
Fromat:![aaaaaaaa](url)
```

![aaaa](../img/my.png)

### Links 链接

```
http://www.baidu.com
[百度](http://www.baidu.com)
```

[百度](http://www.baidu.com)

### Blockquotes 块引用

```
As kanye West said；
>We're living the future so
>the presont is out past.
```



As kanys west said:

> We're living the future so
>
> the present is our past.

### Inline code 内联代码

```
I think you should use an `<addr>` element here instead.
```

I think you should use an `<addr>` element here instead.

### Syntax highlighting 代码（code）

```
​```javascript
function aaa(arg){
  if(arg){
    alert(arg);
  }
}
```

选择语言会有对应语言的高亮效果,如果没有选择语言的话，缩进要自己控制，并且每有颜色

```javascript
function aaa(arg){
  if(arg){
    alert(arf);
  }
}
```

### Task Lists 多选框/任务列表

```
- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item
```

- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item

### Tables 表格

```
First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column
```

| First Header                | Second Header                |
| --------------------------- | ---------------------------- |
| Content from cell 1         | Content from cell 2          |
| Content in the first column | Content in the second column |

如果是用**Typore**的话，则好	`|aa|bb|`这样也可以直接生成表格

### SHA references

Any reference to a commit’s [SHA-1 hash](http://en.wikipedia.org/wiki/SHA-1) will be automatically converted into a link to that commit on GitHub.

```
16c999e8c71134401a78d4d46435517b2271d6ac
mojombo@16c999e8c71134401a78d4d46435517b2271d6ac
mojombo/github-flavored-markdown@16c999e8c71134401a78d4d46435517b2271d6a
```

### Strikethrough 删除线

```
用~~包围的内容，~~产生删除线~~
```

用~~ 包围的内容，~~产生删除线~~ 

### Emoji 表情

```
使用：开始并用：结束
如：:haha:
```

如::haha:

### Automatic linking for URLs

任何URL（如http://www.github.com/）会自动转换成一个可点击的链接。

### Username @mentions

使用@用户名，可以提醒对于用户1

### Issue references within a repository

Any number that refers to an Issue or Pull Request will be automatically converted into a link.

```
#1
mojombo#1
mojombo/github-flavored-markdown#1
```
该文章引用[github markdown](https://guides.github.com/features/mastering-markdown/).