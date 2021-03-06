## 管理源

### 默认源

即每次开启软件, 默认加载资源的网站. 在设置里, 点击选择相应的视频源即可.

:::tip
每次进行 `导入` 操作, 软件都会选择导入后的第一条数据为默认源.
:::

:::danger
对相关操作不了解的人, 切勿自定义视频源. 误操作导致无法正常使用软件. 请点击设置里 `重置软件` 按钮, 恢复默认设置.
:::

### 导出

设置界面, 选择源管理功能里, 点击 `导出` 按钮, 即可导出所有源.
```
[{"id":1,"key":"okzy","name":"OK 资源网","api":"http://cj.okzy.tv/inc/api.php","download":"http://cj.okzy.tv/inc/apidown.php"},{"id":2,"key":"zuidazy","name":"最大资源网","api":"http://www.zdziyuan.com/inc/api.php","download":"http://www.zdziyuan.com/inc/apidown.php"},{"id":3,"key":"doubanzy","name":"豆瓣电影资源","api":"http://v.1988cj.com/inc/api.php","download":"http://v.1988cj.com/inc/apidown.php"},{"id":4,"key":"135zy","name":"135 资源网","api":"http://cj.zycjw1.com/inc/api.php","download":"http://cj.zycjw1.com/inc/apidown.php"},{"id":5,"key":"kuyunzy","name":"酷云资源","api":"http://caiji.kuyun98.com/inc/ldg_api.php","download":"http://caiji.kuyun98.com/inc/apidown.php"},{"id":6,"key":"mgtvzy","name":"芒果 TV 资源网","api":"https://api.shijiapi.com/api.php/provide/vod/at/xml/","download":""},{"id":7,"key":"subo988","name":"速播资源站","api":"https://www.subo988.com/inc/api.php","download":""},{"id":8,"key":"209zy","name":"209 资源","api":"http://cj.1156zy.com/inc/api.php","download":""},{"id":9,"key":"zuixinzy","name":"最新资源","api":"http://api.zuixinapi.com/inc/api.php","download":""},{"id":10,"key":"kubozy","name":"酷播资源","api":"http://api.kbzyapi.com/inc/api.php","download":""},{"id":11,"key":"yongjiuzy","name":"永久资源","api":"http://cj.yongjiuzyw.com/inc/api.php","download":""},{"id":12,"key":"123ku","name":"123 资源","api":"http://cj.123ku2.com:12315/inc/api.php","download":""},{"id":13,"key":"88zyw","name":"88 影视资源站","api":"http://www.88zyw.net/inc/api.php","download":""},{"id":14,"key":"wolongzy","name":"卧龙资源","api":"http://cj.wlzy.tv/inc/api_mac.php","download":""},{"id":15,"key":"mahuazy","name":"麻花资源","api":"https://www.mhapi123.com/inc/api.php","download":""},{"id":16,"key":"kkzy","name":"快快资源","api":"https://api.kkzy.tv/inc/api.php","download":""},{"id":17,"key":"158zy","name":"壹伍捌资源网","api":"http://cj.158zyz.net:158/inc/api.php","download":""},{"id":18,"key":"rrzy","name":"人人资源","api":"https://www.rrzyw.cc/api.php/provide/vod/from/rrm3u8/at/xml/","download":""},{"id":19,"key":"mokazy","name":"魔卡资源网","api":"https://cj.heiyap.com/api.php/provide/vod/at/xml/","download":""},{"id":20,"key":"kyzy","name":"快影资源站","api":"https://www.kyzy.tv/api.php/kyyun/vod/at/xml/","download":""},{"id":21,"key":"solezy","name":"搜乐资源网","api":"https://www.caijizy.vip/api.php/provide/vod/at/xml/","download":""},{"id":22,"key":"bbkdj","name":"步步高顶尖资源网","api":"http://api.bbkdj.com/api","download":""},{"id":23,"key":"1886zy","name":"1886 资源","api":"http://cj.1886zy.co/inc/api.php","download":""},{"id":24,"key":"mbo","name":"秒播资源","api":"http://caiji.mb77.vip/inc/api.php","download":""}]
```

 | 属性 | 说明 |
 | --- | --- |
 | id | 数字小的会在前面显示, 即 id 为1, 则在列表第一个显示. id 不可重复, 必填 |
 | key | 网站的 key , 一般取 网站的域名. key 不可重复. 必填 |
 | name | 网站的中文名称, 必填 |
 | api | 视频源接口, 必填 |
 | download | 视频下载接口, 填写则会复制 MP4 格式的视频下载链接, 不填则复制 M3U8 格式的视频下载链接, 选填 |

### 编辑

为了方便查看编辑, 可以导出后格式化一下. 推荐使用以下在线格式化网站:
1. [jsonformatter](https://jsonformatter.org/)
2. [JSON 在线](https://www.sojson.com/)

资源网站可以百度获取, 以 OK资源网 为例
1. 百度 [OK资源](http://okzyw.com/)
2. 进入 [OK资源采集帮助中心](http://okzyw.com/help/)
3. 找到 [苹果10 MacCms10](http://okzyw.com/help/#MacCms10)
4. 其中 OK资源站:  `http://cj.okzy.tv/inc/api.php` 即是 `api`. 
5. 迅雷下载接口: `http://cj.okzy.tv/inc/apidown.php` 即是 `download`
6. 补齐 `id`, `key`, `name`, `api`, `download` 则完成了一个视频源的添加.

:::tip
1. `id` 不能重复
2. 除了 `download` 可以留空, 其他均为必填值
:::

:::warning
1. 视频源不是随意一个视频网址, 必须是类似采集网, 且必须是 MacCms10 的接口才行.
2. 部分视频源包含大量违规违法资源, 请用户自行甄别.
3. 请勿非法传播下载 违规违法资源, 否则后果自负.
:::

### 导入

编辑完, 复制到剪贴板, 然后点击软件设置里 `导入` 按钮, 即可导入视频源, 无需重启软件.