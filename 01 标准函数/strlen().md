---
tags:
  - 字符串
---
## 使用

```c
strlen(s1);
```

> [!example]
> ```c
> char s1[20] = "Hello";
> char s2[20] = "Hello, World";
> printf("%d, %d, %d", strlen(s1), strlen(s2));  // 5, 12
> ```

## 效果

`strlen(s1)` 将会取得字符串 `s1` 的长度。

> [!attention] 
> 空格也算作一个字符。