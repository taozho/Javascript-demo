# JavaScript中的对象类型
在JavaScript中，对象这个概念比较复杂，大家都知道Window、Document是对象，Object也是对象，Global也是对象，用户还可以自己定义对象等，那么他们之间存在什么联系和区别呢？

从语法的角度来分析上述对象，他们都属于同一类型数据结构。但是，如果细分这些JavaScript对象，你会发现他们是不同级别的。一般来说，在JavaScript可以创建和使用的对象包含三种类型：本地对象、内置对象、宿主对象。

### 本地对象
本地对象就是独立于宿主环境的JavaScript预定义对象，这些本地对象实际上都是抽象的类，通俗说就是构造函数，本地对象的主要成员如下表所示。由于用户自定义的对象都是本地对象的具体事例，所以他们应该属于本地对象范畴。

** JavaScript预定义的本地对象** 

|    |     |     |      |     |     |
| :--: | ------------ |----------------| ----------------|----------------| :--: |
| Object | Function | Array | String | Boolean | Number |
| Data | RegExp | Error | EvalError | RangeError | ReferenceError |
| SyntaxError | TypeError | URLError |


