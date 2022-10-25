# jsfloatcal
 
# 快速上手
## 安装
```shell
npm i jsfloatcal
```

## 使用
```javascript
import { add, subtract, multiply, divide } from 'jsfloatcal'
```
## 例子

```javascript
// 加
 function add(a, b, digits) {
    return operation(a, b, digits, 'add')
}
// 减
 function subtract(a, b, digits) {
    return operation(a, b, digits, 'subtract')
}
// 乘
 function multiply(a, b, digits) {
    return operation(a, b, digits, 'multiply')
}
// 除
 function divide(a, b, digits) {
    return operation(a, b, digits, 'divide')
}

add(0.1,0.2) //0.3
add(0.1,0.2,2) //0.30
注：digits 为精确的位数 默认为0，可不传
