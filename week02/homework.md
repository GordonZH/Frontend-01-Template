### 写一个正则表达式 匹配所有 Number 直接量
```
^(\d*\.?\d*e?\d*|0((b|B)[0-1]*|(o|O)[0-7]*|(x|X)[0-9a-fA-F]*))$
```

###写一个 UTF-8 Encoding 的函数
```javascript
function encodingUtf8(str){
   return str.split('').map((s) => `\\u${s.codepointAt().tostring(16)}`)
}
```

### 写一个正则表达式，匹配所有的字符串直接量，单引号和双引号
```
   ..
```

