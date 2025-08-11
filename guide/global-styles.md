# 全局样式变量

全局样式在 `app.wxss` 中定义，可在任意组件内使用 `var()` 调用。

```css
:root {
  --color-primary: #1677ff;
  --color-success: #52c41a;
  --color-warning: #faad14;
  --color-error: #f5222d;
  --color-text-primary: #1f1f1f;
  --color-text-secondary: #8c8c8c;
  --spacing-sm: 8px;
  --spacing-md: 16px;
  --spacing-lg: 24px;
}
```