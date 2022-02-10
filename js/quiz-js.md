# JS 使用和基本编程

## 写代码

请完成以下文件中的编码需求：

- [查看 `clone.js`](./clone.js)
- [查看 `get-host.js`](./get-host.js)
- [查看 `get-sum.js`](./get-sum.js)

## 方法论

如果你有一定的开发经验，并且追求代码的质量。  
那么你一定知道一些实践技巧，简答 3 ～ 10 条即可。

例如：

> 面向对象编程，代码逻辑可以内聚。
> 禁止使用 var，不可变数据用 const 声明，可变数据用 let 声明。

答：
> - 使用对象属性代替多个if else
> - 辅助函数拆分为多个简单函数
> - 提取公共方法避免重复代码

## 请问以下代码做了什么事情

```js
const getLoglevel = () => {
  return localStorage.loglevel ?? 'INFO';
};
```

答：
```js
 如果localStorage.loglevel为真则返回localStorage.loglevel，否则返回'INFO'
 相当于: 
       localStorage.loglevel || 'INFO'

       localStorage.loglevel ? localStorage.loglevel : 'INFO'
```
