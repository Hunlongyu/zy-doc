## 快捷键

快捷键绑定使用了 [mousetrap](https://github.com/ccampbell/mousetrap) 插件.

除了全局快捷键, 其他快捷键, 只在 `播放界面` 和 `Mini 模式` 下生效

|          快捷键          | 说明       |          快捷键          | 说明       |
| :----------------------: | ---------- | :----------------------: | ---------- |
| `Alt + Space` | 聚焦或取消聚焦（全局快捷键）| | |
| `→` | 快进 5 秒 | `←` | 快退 5 秒 |
| `↑` | 音量调高 | `↓` | 音量调低 |
| `m` | 静音 | `t` | 置顶或退出置顶 |
| `f` | 进入或退出全屏 | `esc` | 退出全屏 |
| `Alt + →` | 下一集 | `Alt + ←` | 上一集 |
| `Alt + ↑` | 透明度调高 | `Alt + ↓` | 透明度调低 |
| `home` | 跳到视频开始位置 | `end` | 跳到视频结束位置 |
| `pgUp` | 播放倍速加快 0.25 | `pgDown` | 播放倍速减慢 0.25 |
| `Alt + m` | 进入或退出 Mini 模式 | `space` | 播放或暂停 |

:::danger
对相关操作不了解的人, 切勿自定义快捷键. 误操作导致无法正常使用软件. 请点击设置里 `重置软件` 按钮, 恢复默认设置.
:::

### 导出

设置界面, 选择快捷键功能里, 点击 `导出` 按钮, 即可导出快捷键.
 ```
 [{"name":"back","desc":"快退","key":"left"},{"name":"end","desc":"跳到视频结束位置","key":"end"},{"name":"escape","desc":"退出全屏","key":"esc"},{"name":"forward","desc":"快进","key":"right"},{"name":"fullscreen","desc":"进入或退出全屏","key":"f"},{"name":"home","desc":"跳到视频开始位置","key":"home"},{"name":"mini","desc":"进入或退出mini模式","key":"alt+m"},{"name":"mute","desc":"静音","key":"m"},{"name":"next","desc":"下一集","key":"alt+right"},{"name":"opacityDown","desc":"透明度调低","key":"alt+down"},{"name":"opacityUp","desc":"透明度调高","key":"alt+up"},{"name":"playAndPause","desc":"播放或暂停","key":"space"},{"name":"playbackRateDown","desc":"播放倍速减慢","key":"pagedown"},{"name":"playbackRateUp","desc":"播放倍速加快","key":"pageup"},{"name":"prev","desc":"上一集","key":"alt+left"},{"name":"top","desc":"置顶或退出置顶","key":"t"},{"name":"volumeDown","desc":"音量调低","key":"down"},{"name":"volumeUp","desc":"音量调高","key":"up"}]
 ```

 | 属性 | 说明 |
 | --- | --- |
 | name | 不可删除, 不建议修改. |
 | desc | 中文描述, 便于阅读. 不可删除, 不建议修改. |
 | key | 键盘 key 值, 修改相应 key 值, 即可改绑. |

### 编辑

为了方便查看编辑, 可以导出后格式化一下. 推荐使用以下在线格式化网站:
1. [jsonformatter](https://jsonformatter.org/)
2. [JSON 在线](https://www.sojson.com/)

快捷键分两种:
1. 单个按键, 如: `right` 快进
2. 组合按键, 如: `alt+right` 下一集


支持的按键
1. 普通键: `a`, `b`, `c`, `0`, `1`, `2`, `+`, `-`, `*`, `/` 等
2. 组合键: `shift`, `ctrl`, `alt`, `meta`, `option`, `command`. 后两个为 mac 键盘.
3. 其他特殊键: `backspace`, `tab`, `enter`, `retur`, `capslock`, `esc`, `space`, `pageup`, `pagedown`, `end`, `home`, `left`, `right`, `down`, `ins`, `del`, `plus`

:::tip
1. 所有字母均为小写, 组合按键使用 `+` 连接. 中间注意不能有空格.
2. 同一 key 不能绑定两次.
3. 快捷键可以删除, 修改, 但不能添加.
:::

### 导入

快捷键编辑完复制到剪贴板, 然后点击软件设置里 `导入` 按钮, 则导入自定义的快捷键.

::: warning
需要注意的是, 导入快捷键需要重启软件.
:::
