---
title: 部署网站的另一种可能 Netlify.com
date: 2019-08-21 21:23:05
tags: [Bitbucket,GitHub,GitLab,NetLify,]
---
Netlify是构建快速，现代化网站所需的一切：持续部署，无服务器功能等等,并且可以连接你的存储库，如GitHub,GitLab,Bitbucket,可以经授权后直接部署你的网站，可以自定义二级域名，可以绑定顶级域名，提供免费的HTTPS服务，前提是要用他们的DNS服务器，也可以在这个网站直接购买域名，剩下的他能帮你全部自动搞定。

网站登录

![Netlify.png](https://i.loli.net/2019/08/21/qPmaFQZoytKzDvE.png)
<!---more--->
如果你用GitHub账号登录，经过授权后日志实时显示您的站点构建的详细跟踪，在站点仪表板的“部署”部分中找到它们。


自动预览您的PR或分支

每次打开拉取请求或将新更改推送到分支时，Netlify都会自动使用唯一的URL构建预览。就像每个PR或分支的临时环境一样，预览非常适合测试和协作。

![1.png](https://i.loli.net/2019/08/21/dsuAnRLZJHb7Kyk.png)

将流量拆分为多个分支

在两个或多个分支之间将流量拆分到主域，不会造成性能损失。只需单击一下即可设置简单的A / B测试，利用边缘节点逻辑请求。
![2.png](https://i.loli.net/2019/08/21/sUWohElGawKBQvx.png)


部署AWS Lambda功能，无需配置API网关，协调部署或设置AWS账户。

您的功能与Netlify站点的其余部分一起进行版本控制，构建和部署，Netlify API网关自动处理服务发现。此外，您的功能受益于部署预览和回滚的强大功能。

![3.png](https://i.loli.net/2019/08/21/JGzOmyQPgZ5aBFl.png)

管理注册，登录，密码恢复等 - 所有这些都不需要滚动您自己的身份验证服务。

注册并验证您网站的访问者，以便您可以登录内容，启用CMS功能，对外部服务进行经过身份验证的呼叫等。与任何了解JSON Web令牌的服务安全集成。
![4.png](https://i.loli.net/2019/08/21/JjTmiPIKXF3yQgG.png)

管理表单和提交，无需任何服务器端代码或JavaScript。


将HTML表单编码到您网站的任何页面中，向该标记添加属性，您将在Netlify仪表板中收到提交。HTML文件在部署时直接解析，因此您无需在您的网站上进行API调用或包含额外的JavaScript。

![5.png](https://i.loli.net/2019/08/21/3NdesbVWRHvnAiZ.png)

直接在Git中处理图像和其他大型资产文件，而不会使您的存储库膨胀。

在Netlify工作流程中释放Git LFS的强大功能。Git将指针文件存储在您的存储库中，然后将真实文件上传到我们的资产服务器。以高分辨率上传图像，然后使用图像转换即时提供您站点中所需的大小。



![6.png](https://i.loli.net/2019/08/21/yVfCut5H6vSYzMD.png)

绑定独立域名

![7.png](https://i.loli.net/2019/08/21/jT1SKIRGdHU3avz.png)



