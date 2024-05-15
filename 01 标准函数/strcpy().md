---
tags:
  - 字符串
---
## 使用

```c
strcpy(s1, s2);
```

> [!example]
> ```c
> char s1[8] = "Hello";
> char s2[8] = "World";
> strcpy(s1, s2);
> printf("%s, %s", s1, s2);  // World, World
> ```

> [!example] 
> ```c
> char *s1[10] = "12345";
> char *s2[10] = "1234";
> printf("%s", strcpy(s1, s2));  // 1234
> ```

## 效果

此行代码将字符串 `s2` 复制到字符串 `s1`，覆盖掉了原来的数据。

> [!attention]
> - 是**后面**覆盖**前面**；
> - `strcpy()` 有返回值：复制完成之后的字符串。