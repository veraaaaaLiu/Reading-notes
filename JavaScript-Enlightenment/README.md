# JavaScript 深入精要

## Ch1 JavaScript 物件

### JavaScript 有九種原生物件建構式

- Number()
- String()
- Boolean()
- Object()
- Array()
- Function()
- Date()
- RegExp()
- Error()

>  ＊ Math 是一個靜態物件，不需要 new 運算子

---

建構函式把他想像成一個餅乾模具，用途是建立預先設定好的物件，透過 new 運算子，建立一個實例 (instance)

---

使用 new 將原生建構式實例化
```
var myNumber = new Number(23);
console.log(myNumber.constructor) // logs Number() 
```

### JavaScript 字面值 (literal)
```
var myNumber = new Number(23); // 物件
var myNumberLiteral = 23; // 原始數字值，不是物件
```

原始字串 / 數字 / 布林，在你使用方法或建構式的屬性時，JavaScript 會先將它包裝成物件，可讓你用物件的方式處理他，結束呼叫方法後，再回傳字面值類型

 > JavaScript 的所有事物都具有類似物件的行為

### 原始值 (簡單值 / 單純值)
