# Ant Design 实战课程练习
*************
## 第一章：基础知识
1. 基础知识
    - 初始化项目
        - node
        - npm
        - umi
        - config/config.js
        - src/page/HelloWorld.js
        - .gitignore
        - README.md
    - 插件
        - umi-plugin-react
    - 构建和部署
        - cnpm run build
        - cnpm install serve -g
        - serve ./dist
2. 第一个组件
    - jsx语法
        - 必须闭合
        - 顶层只能有一个标签
        - HTML 原生标签使用小写，自定义的组件标签首字母大写
        - 允许js与jsx混写，{}进入js上下文
    - 组件定义
        - 继承React.Component基类，重写render方法
        - 标签属性传值：this.props
        - 标签内容传值：this.props.children
        - 组件内部状态：this.state
    - 组件生命周期
        - componentDidMount：组件挂载后自动调用
        - componentWillUnmount：组件卸载前自动调用
        - componentDidUpdate：UI 每次更新后调用 
3. 使用 Ant Design 组件