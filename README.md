# Cloud I Wanna 代码功能支持
尝试为新版 Cloud I Wanna 加入脚本模块，从而支持代码功能

>计划步骤

- [ ] 编译
  - [x] 解析
    - [x] 词法分析
    - [x] 语法分析
    - [x] 语法错误检查
    - [x] 类型错误检查
  - [ ] 优化
    - [ ] 自动计算值
    - [ ] 移除多余节点
  - [ ] 生成编码
    - [ ] 函数库构建
    - [ ] 编码为函数索引组
- [ ] 解释
  - [ ] 语句表达式执行
  - [ ] 内置对象/变量/函数处理
  - [ ] 错误处理
- [ ] 代码编辑器
  - [x] 语法高亮
  - [x] 错误检查
  - [ ] 自动补全
  - [ ] 函数提示
  
>注：本项目仅作为试验，极有可能失败（

测试链接：https://vicklleall.com/code-editor/

基本语法示例
```javascript
num a, b = 0, c = [2, 3, 3]; //定义数字类型变量/数组
str d, e = "ABC", f = ["AB", "CD"]; //定义字符串类型变量/数组
// if, for语句示例
for (num i = 0; i < 10; i++) {
  if (i < 3) {
    c[i] = i;
  } else {
    break;
  }
} 
```
