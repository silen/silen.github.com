---
layout: api
title: ihuacheng api
---


<a name="login"></a>
##登录
/index.php?m=apic=user&a=updateNickName

http请求方式: POS

| 参数        | 是否必填        |  说明 |
| ------------- |:-------------|:-------------|
|token| 是 | 验证token
|username| 是 | 用户名
|password| 是 | 密码
```
{
    "status":1,
    "member":
        {
            "nickname":"silen",
            "openid":"oyh77skAEgtPUKGaOqiD14N9Rou8",
            "systemid":"264",
            "subscribe":"1",
            "headimgurl":"http:\/\/wx.qlogo.cn\/mmopen\/JceeNIg7n5947ZgnNdWciae5M6GQ5d27dDmHUE4wyxq4KFVEJM10f4TPibUmVAr2XvNzkPq93rwojL6Jcx8B28xHwRb0xNevTs\/0"
        }
}
```

