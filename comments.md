### 完成度：

- 页面样式还原度还行，但分组列表无法验证
- 完成需求 1，2，分组相关功能未实现，添加功能也未实现，且分组接口在讲师大于 1 时报 500 错

**Details:**

### 测试：

- 没有测试

**Details:**

### 知识点：

- 有划分分组列表和学员列表等组件，其中列表元素可以抽象成公共组件
- 使用了语义化标签，但还可以加强使用和更正错误
- 使用了 Flex 布局，scss 及其特性（嵌套，变量，mixin）
- 运用了 ES6+语法及 axios，不过还可以加强和优化
- 运用 React 相关知识点，有的地方可以改进和优化

**Details:**

- \+ 使用了 mixin

* \- 没有必要设置 state，直接使用 props 就好
* \- 循环渲染需要给子元素设置 key，可参见 error

### 工程实践：

- 小步提交做的不错
- 有抽取 API 层，且做了拆分
- 有做组件拆分，但可以进一步优化抽象和复用

**Details:**

- \+ baseURL 这个实践不错

* \- 下面部分可以封装成可复用的组件，且包含删除功能
* \- ul li 多余了，button 可以封装成可复用的组件
* \- 纯 UI 组件可以使用函数组件
* \- 这里不是 nav，直接使用 ul 就好
* \- 文件命名优化，和 router 有什么关系？