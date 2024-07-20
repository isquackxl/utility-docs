> 判断数据是否为非空类型，`null`或`undefined`或`''`或`[]`或`{}`均返回`false`

## 引入

```js
import { isNotEmpty } from "@quackxl/utility";
```
or
```js
import { isNotEmpty } from "@quackxl/utility/cores/isNotEmpty.js";
```

## 格式

```js
isNotEmpty(value);
```

## 参数

| 属性名   | 类型      | 描述           |
| -------- | --------- | -------------- |
| `value`  | `Any`     | 需要判断的数据 |
| `return` | `Boolean` |                |