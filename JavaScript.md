
### JavaScript
---


- alert(typeof null)   --object
- alert(typeof undefined)  --undefined
- alert(typeof NaN)  --number
- alert(NaN == undefined)  --false
- alert(NaN == null)  --false

**JavaScript的原型和原型链是什么**
- 原型：
  - JavaScript的所有对象中都包含了一个 [__proto__] 内部属性，这个属性所对应的就是该对象的原型
  - JavaScript的函数对象，除了原型 [__proto__] 之外，还预置了 prototype 属性
  - 当函数对象作为构造函数创建实例时，该 prototype 属性值将被作为实例对象的原型 [__proto__]。

- 原型链：
  -  当一个对象调用的属性/方法自身不存在时，就会去自己 [__proto__] 关联的前辈 prototype 对象上去找
  -  如果没找到，就会去该 prototype 原型 [__proto__] 关联的前辈 prototype 去找。依次类推，直到找到属性/方法或 undefined 为止。从而形成了所谓的“原型链”
      
      
**webpack和gulp分别是什么，有什么异同点**
    
       

