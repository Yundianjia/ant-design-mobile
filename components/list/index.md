# List

- category: Components
- chinese: 列表
- type: 列表

---

AntUI列表容器,其中会有列表头,列表尾,列表主体。

## 何时使用

## API

### List

| 成员        | 说明           | 类型               | 默认值       |
|-------------|----------------|--------------------|--------------|
| prefixCls    | 默认class前缀        | String |   'am'  |
| style      | 定制的样式       | Object           | 无
| isFormList      | 是否是FormList       | bool           | true
| isIconList      | 是否是Iconlist       | bool           | false

### List.Header
| 成员        | 说明           | 类型               | 默认值       |
|-------------|----------------|------------------|--------------|
| prefixCls   | 默认class前缀        | String |   'am'  |
| style      | 定制的样式       | Object           | 无

### List.Body
| 成员        | 说明           | 类型               | 默认值       |
|-------------|----------------|--------------------|--------------|
| prefixCls    | 默认class前缀        | String |   'am'  |

### List.Footer

| 成员        | 说明           | 类型               | 默认值       |
|-------------|----------------|--------------------|--------------|
| prefixCls    | 默认class前缀        | String |   'am'  |
| style      | 定制的样式       | Object           | 无
| align      | 左对齐或者是右对齐   | String(left/right) | left
| onClick      | 点击事件   | Func |   无  |

### List.Item

| 成员        | 说明           | 类型               | 默认值       |
|------------|----------------|--------------------|--------------|
| prefixCls    | 默认class前缀        | String |   'am'  |
| line       | 单行或者双行        | number |   1  |
| link       | 如果item需要跳转,则需要URL  | String |   无  |
| arrow      | 箭头方向        | String（horizontal/up/down/无） |   无  |
| icon       | 缩略图  | imgsrc |   无  |
| thumd       | 缩略图  | imgsrc |   无  |
| extra      | 右边内容        | String/HTML |   无  |
| onClick    | 点击事件的回调函数 | Function |   无  |