# 格式化通知公告API

> 格式化通知公告

| URL |  Header | Method |
| ------------- |:-------------:| -----:|
| /api/webview_info/ | 无 | GET |

<hr/>

## URL Params

    无

## POST Data(json)

    无

## Return Data(json)

    {
        "title": "xxxx"
        "content": "xxxx"
        "date": "2016-06-19",
        "appendix_list": [] // 下载链接
    }

## Status Code

    200 ok
    502 服务器端异常

## Notes

    信息公告是定时爬取 + 服务器端缓存
