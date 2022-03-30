# Time UI

- 这是一款基于 **Vite / Vue3.0 / Typescript** 搭建的 UI 组件库，涵盖了Switch 、Button 等常见 UI 组件，同时适合**移动端和PC端**显示。
- 预览地址：https://xulei1998.github.io/time-ui-website/index.html

## 使用方法

### 安装

在项目中，使用终端执行以下命令：

```javascript
npm install time-ui  
```

或者

```javascript
yarn add time-ui
```

### 引入

```vue
import { Button, Tabs, Tab, Switch, Dialog, openDialog } from "time-ui"
import 'time-ui/dist/lib/time.css'
```

### 简单示例

在Vue单文件组件中使用 Button 组件：

```vue
<template>
  <div>
    <Button>按钮</Button>
  </div>
</template>

<script>
import { Button, Tabs, Tab, Switch, Dialog, openDialog } from "time-ui"
import 'time-ui/dist/lib/time.css'
export default {
  components: { Button }
}
</script>
```

