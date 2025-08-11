# ui-device-card 设备卡片

设备信息展示卡片，包含名称、编号、位置、状态。

## 引入
```xml
<ui-device-card
  name="传感器-A1"
  id="SN-001"
  location="机房1楼"
  status="online">
</ui-device-card>
```

## API
| 属性 | 类型 | 必填 | 说明 |
|------|------|------|------|
| `name` | String | 是 | 设备名称 |
| `id` | String | 是 | 设备编号 |
| `location` | String | 否 | 设备位置 |
| `status` | String | 是 | 设备状态（`online`/`offline`/`warning`） |

## 状态颜色
- 在线：`var(--color-success)`
- 离线：`var(--color-error)`
- 告警：`var(--color-warning)`

## 交互示例
```js
Page({
  data: {
    device: {
      name: '传感器-A1',
      id: 'SN-001',
      location: '机房1楼',
      status: 'online'
    }
  }
})
```