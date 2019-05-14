#下拉列表插件

#在线示例
https://sudh-17.github.io/kselect/kselect.html

#使用方法
1. 导入 kselect.js以及kselect.css

#实例构造器
kselect.init(dom, data, multi)， 参数分别为挂载点(dom节点)，数据源(键值对数组, 数组元素必须包含key和value，例如[{key:'123', value:'json'}, ...]) 以及多选设置(boolean)

#API
1. getValue()，当multi为false时，返回字符串，当multi为true时返回字符串数组
2. setOption(option)，参数option包含height和width两个属性，分别表示输入框的高和宽，支持纯数字和带有单位的字符串