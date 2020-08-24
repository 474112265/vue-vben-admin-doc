## 主题更换

### 主题色

默认全局主题色配置位于`config/glob/lessModifyVars.js`内

只需要修改**primaryColor**为您需要的配色，然后重新执行`yarn serve`即可

```js
const primaryColor = '#018ffb';

const modifyVars = {
  // -------- Colors -----------
  'primary-color': primaryColor, // 全局主色 Global dominant color
  'info-color': primaryColor, // 默认颜色 Default color
  'success-color': '#55D187', // 成功色 Success color
  'error-color': '#ED6F6F', // 错误色 False color
  'warning-color': '#FFD164', // 警告色  Warning color

  'link-color': primaryColor, //  链接色 Link color
  'disabled-color': '#C2C2CC', // 失效色 Failure color
  'heading-color': '#2C3A61', // 标题色 Title color

  'text-color': '#2C3A61', // 主文本色 Main text color
  'text-color-secondary ': '#606266', // Subtext color

  'background-color-base': '#F0F2F5', // background color

  'font-size-base': '14px', // 主字号 Main font size

  'box-shadow-base': '0 2px 8px rgba(0, 0, 0, 0.15)', // 浮层阴影 Floating shadow

  'border-color-base': '#cececd', // 边框色 Border color,
  'border-color-split': '#cececd', // 边框色 Border color,
  'border-radius-base': '2px', // 组件/浮层圆角 Component/float fillet
};

module.exports = {
  modifyVars,
  primaryColor,
};
```
