# generateShortUrl
草田签提供生成短网址稳定接口
---
接口名称：	generateShortUrl<br>
接口用途：	短网址生成接口<br>
method：	POST<br>
接口地址：	https://ctsign.cn/Web/open/generateShortUrl<br>
输入参数：	<br>

key|参数类型|是否必须|参数解释
:--:|:--:|:--:|:--:
secretKey|string|是|官方公开秘钥:7554nbyd864tb4a26vaaf34cba9cqe28e
url|string|是|长网址

返回数据|
:--:|
      {
            "success": true,
            "info": "处理成功！",
            "data":
            {
                   "longUrl": "http://www.baidu.com",
                   "shortUrl": "https://ctsign.cn/Web/open/i021I10n",
                   "shortValue": "i021I10n",
                   "channelId": 2,
                   "createTime": null
            }
      }


备注：<br>
【success】 true 成功 false失败<br>
【info】信息<br>
【data】数据内容<br>
【longUrl】（长）原网址<br>
【shortUrl】生成的短网址<br>
【shortValue】短网址的值<br>
【channelId】渠道ID<br>
【createTime】创建时间<br>
