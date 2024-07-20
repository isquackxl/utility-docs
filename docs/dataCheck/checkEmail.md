> 判断数据是否符合邮箱规范，支持带汉字的邮箱

## 引入

```js
import { checkEmail } from "@quackxl/utility";
```
or
```js
import { checkEmail } from "@quackxl/utility/cores/checkEmail.js";
```

## 格式

```js
checkEmail(str);
```

## 参数

| 属性名   | 类型      | 描述             |
| -------- | --------- | ---------------- |
| `str`    | `String`  | 需要判断的字符串 |
| `return` | `Boolean` |                  |