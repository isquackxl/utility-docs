> 判断数据是否符合身份证号码规范，15 位或者 18 位

## 引入

```js
import { checkID } from "@quackxl/utility";
```
or
```js
import { checkID } from "@quackxl/utility/cores/checkID.js";
```

## 格式

```js
checkID(str);
```

## 参数

| 属性名   | 类型      | 描述             |
| -------- | --------- | ---------------- |
| `str`    | `String`  | 需要判断的字符串 |
| `return` | `Boolean` |                  |