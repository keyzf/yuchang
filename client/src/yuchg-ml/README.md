# yuchang-ml

可视化脚本编辑工具Yuchang的插件库，提供机器学习相关的Block定义, 
注意：yuchg版本必须1.2.0以上

## 使用步骤

+  (1）安装 npm install --save yuchg-ml
+  (2）引入

```
  import yuchg from 'yuchg'
  import ml from 'yuchg-ml'
  import 'yuchg/css/style.css'

  let editor = yuchg.Scratch.init(dom)
  editor.setOption({
    packages: [ml]
  })
   
```
