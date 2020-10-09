# 层叠样式表
- 引入方式
  - link标签联系HTML(外联)
  - head标签中书写style标签(内嵌)
  - 标签中style属性 style属性值就是css代码()
- 书写规范
  - *通配符
  - .class类选择器
  - #id选择器
  - 标签选择器
- 基础选择器的优先级
  - id > class > tagname
- 常见属性
  - 文本
  - 边框
  - 背景
  - 盒子模型
    - 内边框
    - 外边距
    - display
  - 布局属性
    - 表格
      - 适配问题明显
    - 定位（left right top bottom如果不设置都为零）
      - 绝对定位
      - absoulute
        - 原先主文档的占位会被占据
      - position属性
        - relative为absoulute提供参照物
        - 如果当前元素的所有父级元素都为position都为normal，那么以body为参考点，只要没有设置页面的均为normal
      - relative的参考点：原来的主文档流动的位置的左上角
      - fixed固定在页面，绝对不动
      - 方便开发、直观的游离于主文档，但适配问题
      - 适用于微小的布局（运用在前端组件当中）
    - 浮动
      - 可以实现简单的适配布局
      - 脱离主文档流
      - 手机端布局问题
      - 自动控制
    - 弹性盒子布局
      - 广泛适用于手机端
```
*{
    属性名：属性值
}
div{
    属性名：属性值
}
.table{

}
#table{

}
```