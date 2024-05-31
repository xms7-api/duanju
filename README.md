# 短剧api永久免费接口稳定性高，欢迎对接。
## 全网短剧API接口


概述：
> 本文档提供短剧搜索服务API的对接指南，包括API功能、请求参数、返回数据格式及示例。 本接口主要是用来存储夸克网盘资源然后对接短剧机器人，来实现盈利。

功能描述：
> 短剧搜索服务API提供短剧名称的搜索功能，用户可通过API提交短剧名称关键字，获取相应的短剧信息列表。


搜索接口地址：<br/>
> `https://api.xms7.xyz/xms7/api/mov?q=短剧关键字&offset=1&limit=20`

返回数据:
```
{
    "records": [
        {
            "name": "9049-战神归来之巴掌战神81集",
            "link": "https://pan.quark.cn/s/bebae1e5279b"
        },
        {
            "name": "8622-瞎眼战神瞎子战神91集",
            "link": "https://pan.quark.cn/s/9d77233b6794"
        },
        {
            "name": "1198-战神殿 #狂怒战神",
            "link": "https://pan.quark.cn/s/a5825b679cd7"
        },
        {
            "name": "2092-战神殿 #狂怒战神",
            "link": "https://pan.quark.cn/s/0eddabf88f2d"
        },
        {
            "name": "战神殿狂怒战神长篇",
            "link": "https://pan.quark.cn/s/f8f6c572f75d"
        },
        {
            "name": "8729-捡个战神回家挑粪81集",
            "link": "https://pan.quark.cn/s/4f6fcb0825d5"
        },
        {
            "name": "8637-审判战神92集",
            "link": "https://pan.quark.cn/s/a97406ecf640"
        },
        {
            "name": "8440-战神妈妈之怒（79集）杨景景",
            "link": "https://pan.quark.cn/s/657ac3e652ff"
        },
        {
            "name": "8422-离婚战神：崛起（95集）王希如",
            "link": "https://pan.quark.cn/s/79a6c3f9b472"
        },
        {
            "name": "8397-反转战神（79集）",
            "link": "https://pan.quark.cn/s/f3fa1edadb19"
        }
    ],
    "total": 233,
    "size": 10,
    "current": 1,
    "orders": [],
    "optimizeCountSql": true,
    "searchCount": true,
    "countId": null,
    "maxLimit": null,
    "pages": 24
}
```
提供接口可用于微信搜索机器人，对接各大程序，网站，网页。
如有未搜到剧集，将在反馈后24小时更新！！！！
