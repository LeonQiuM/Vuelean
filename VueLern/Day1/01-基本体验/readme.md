### 创建 vue 实例传入的 options

1. el
    + 类型：string|htmlElement
    + 作用：决定 vue 实例会管理哪一个 DOM
2. data
    + 类型：object|function（组件中 data 必须是一个函数）
    + 作用：Vue 实例对用的数据对象
3. methods
    + 类型：{[key:string]:function}
    + 自定义属于本 vue 实例的方法，可以在其他地方进行调用，也可以在指令中使用


### vue的生命周期