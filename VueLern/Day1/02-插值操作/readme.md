# 指令
1. mustache 语法
```$xslt
mastache [双大括号]语法中不仅仅可以直接传递显示变量，还可以写简单的表达式
```
2. v-once
```$xslt
v-once 指令只用于第一次加载时显示，后面不再继续动态加载修改值
```

3. v-html
```$xslt
用于解析 html标签
```

3. v-text
```$xslt
会覆盖原来的 标签中的 text内容
```

4. v-pre
```$xslt
 将{{string}}原封不动的展示出来  可能用于code review
```

5. v-cloak
```$xslt
用于防止业务在加载的过程，vue 未解析之前显示一些不友好的东西
1. 在 vue 解析之前，div 中有一个属性为 v-cloak
2. 在解析之后，dom不带有v-cloak属性
```