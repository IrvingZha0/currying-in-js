# currying-in-js

```
// 剪头函数版本
let add = n1 => n2 => n1 + n2
// function版本
function add(n1){
  return function(n2){
    return n1 + n2
  }
}
```
