> 去掉 str 中的全部类型空格，包括`t\r\f\n\s`

## 引入

```js
import { trimAll } from "@quackxl/utility";
```
or
```js
import { trimAll } from "@quackxl/utility/cores/trimAll.js";
```

## 格式

```js
trimAll(str);
```

## 参数

| 属性名   | 类型      | 描述           |
| -------- | --------- | -------------- |
| `str`    | `Any`     | 需要判断的数据 |
| `return` | `Boolean` |                |