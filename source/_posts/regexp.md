---
title: regexp
category: Others
updated: 2019-07-31
---

reference:  
[Regular Expressions Quick Reference](http://www.regular-expressions.info/refquick.html)
[揭开正则表达式的神秘面纱](http://www.regexlab.com/zh/regref.htm)
[正则表达式30分钟教程](http://deerchao.net/)
[前端进阶必须知道的正则表达式知识](https://mp.weixin.qq.com/s/_C3hqSq_tZUhl4IULPYv3A)

example:
[最全的常用正则表达式大全——包括校验数字、字符、一些特殊的需求等等](http://www.cnblogs.com/zxin/archive/2013/01/26/2877765.html)
[由数字、26个英文字母、下划线或汉字的正则表达式](http://blog.sina.com.cn/s/blog_887d00920100tvvd.html)
[常用的正则表达式全面总结](http://www.ha97.com/4458.html)

online tool:   
[RegExr](http://gskinner.com/RegExr/)
[Debuggex](https://www.debuggex.com)
[regex101](https://regex101.com/)


### 元字符 （需转义`\`）

`( [ { \ ^ $ | ) ? * + . ] }`

### Character classes

| Pattern | Description                    |
| ------- | ------------------------------ |
| `.`     | Any character, except newline  |
| `\w`    | Word                           |
| `\d`    | Digit                          |
| `\s`    | Whitespace                     |
| `\W`    | Not word                       |
| `\D`    | Not digit                      |
| `\S`    | Not whitespace                 |
| `[abc]` | Any of a, b, or c              |
| `[a-e]` | Characters between `a` and `e` |
| `[1-9]` | Digit between `1` and `9`      |

### Anchors

| Pattern | Description      |
| ------- | ---------------- |
| `^abc`  | Start with `abc` |
| `abc$`  | End with `abc`   |

### Escaped characters

| Pattern    | Description                            |
| ---------- | -------------------------------------- |
| `\. \* \\` | Escape special character used by regex |
| `\t`       | Tab                                    |
| `\n`       | Newline                                |
| `\r`       | Carriage return                        |

### Groups

| Pattern | Description   |
| ------- | ------------- |
| `(abc)` | Capture group |

### Quantifiers

| Pattern  | Description           |
| -------- | --------------------- |
| `a*`     | Match 0 or more       |
| `a+`     | Match 1 or more       |
| `a?`     | Match 0 or 1          |
| `a{5}`   | Match exactly 5       |
| `a{,3}`  | Match up to 3         |
| `a{3,}`  | Match 3 or more       |
| `a{1,3}` | Match between 1 and 3 |

