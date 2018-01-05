# wx-miniapp
第三方平台开发小程序
==
1.开发小程序绑定
  
    在第三方后台中需要建立开发小程序，绑定后在小程序开发工具中上传的代码都会进入该第三方后台的草稿箱，每个小程序有且只有一条草稿记录，最多添加10个开发小程序。
  
2.小程序第三方平台配置

    开发小程序可保留自定义配置ext.json

3.小程序草稿，模板

    通过API可将草稿选定为模板，通过模板为授权的小程序上传代码，最多可容纳50个模板。

4.授权小程序，部署发布

    在小程序将开发管理权限授权给第三方平台后，通过API可以为小程序上传代码，提交审核，发布小程序，回退等小程序管理。

5.分享小程序
    
    小程序本身，有两种主要分享方式，小程序卡片与小程序码，小程序卡片主要场景是会话，大图营销效果比较好；而小程序码主要是针对微信会话，朋友圈进行分享。

6.拓展

    这里有一个玩法：
    做第三方平台的，可能对分享小程序的场景有更多的要求。如，要达到从某一个app分享多个（几十，上百个）不同的小程序到微信。
    通常情况下，思路还是很清晰的，转一下，放个小程序码，做图片分享就行了；
    不过，同时要支持小程序卡片分享就需要考虑一下，开放平台对移动应用的分享能力的限制，其中分享小程序需要该小程序同时也绑定在开放平台10个可绑小程序和公众号的名额中，
    这里，可以转一下思路，同样在有限的数量下，移动应用->中介小程序->某小程序；通过小程序跳转的方式达到目的。
    
