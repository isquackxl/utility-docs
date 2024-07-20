> 判断数据是否为`Object`类型，仅仅判断通过`{}`或`new Object()`创建出来的对象

## 引入

```js
import { isObject } from "@quackxl/utility";
```
or
```js
import { isObject } from "@quackxl/utility/cores/isObject.js";
```

## 格式

```js
isObject(value);
```

## 参数

| 属性名   | 类型      | 描述           |
| -------- | --------- | -------------- |
| `value`  | `Any`     | 需要判断的数据 |
| `return` | `Boolean` |                |