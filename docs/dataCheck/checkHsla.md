> 判断数据是否符合 hsla 颜色格式规范

## 引入

```js
import { checkHsla } from "@quackxl/utility";
```
or
```js
import { checkHsla } from "@quackxl/utility/cores/checkHsla.js";
```

## 格式

```js
checkHsla(color);
```

## 参数

| 属性名   | 类型      | 描述             |
| -------- | --------- | ---------------- |
| `color`  | `String`  | 需要判断的字符串 |
| `return` | `Boolean` |                  |