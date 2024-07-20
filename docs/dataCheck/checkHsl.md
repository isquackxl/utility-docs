> 判断数据是否符合 hsl 颜色格式规范

## 引入

```js
import { checkHsl } from "@quackxl/utility";
```
or
```js
import { checkHsl } from "@quackxl/utility/cores/checkHsl.js";
```

## 格式

```js
checkHsl(color);
```

## 参数

| 属性名   | 类型      | 描述             |
| -------- | --------- | ---------------- |
| `color`  | `String`  | 需要判断的字符串 |
| `return` | `Boolean` |                  |