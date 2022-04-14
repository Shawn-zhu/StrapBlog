---
layout: post
title: 做一个小成本博客
tags: [Github Pages,Markdown]
---
## 在[github](https://github.com/)上创建一个网页

1. 首先你需一个[github](https://github.com/)账号，如果没有那你的第一步就是注册一个。
2. 在[github](https://github.com/)上创建一个新的仓库(repository).
   ![create repository](/assets/img/blogs/UseGithubPagesToSetupWeb/github_new_create_repository.png)
   给你的仓库起一个名字，勾选增加README并创建它。
   ![name your repository](/assets/img/blogs/UseGithubPagesToSetupWeb/Screen Shot 2022-04-14 at 16.01.23.png)
3. 在主界面上点击*setting*，并在左侧选择*pages*。在右侧的配置界面中选择选择一个*branch*，这个时候除了None应该只有master这个可以选择。
   ![name your repository](/assets/img/blogs/UseGithubPagesToSetupWeb/Screen Shot 2022-04-14 at 16.49.12.png)
   点击*save*后就可以在上面提示的网址访问自己的web了。在下面可以根据自己的喜好选择一个主题。

## 通过域名服务平台申请域名和解析服务

1. 域名服务平台有很多，我使用的是[华为云](https://www.huaweicloud.com/product/domain.html)。域名不是免费的，需要花钱租用。
2. 域名的注册目前都需要认证，需要提供身份证以及一些基本信息。一般工作日1天就可以审核通过。
3. 有了域名之后还需要解析服务，一般的域名服务平台都免费提供解析服务。域名购买成功后，找到*控制台*搜索*云解析服务*。增加如下2条*记录集*。
   ![name your repository](/assets/img/blogs/UseGithubPagesToSetupWeb/Screen Shot 2022-04-14 at 17.04.49.png)
   一般后2个是默认生成的，只需要添加前2个。需要注意将*值*改成*YourCountId.github.io*。
4. 最后是回到你的仓库里，*setting->pages*配置*Domain Name*为刚刚申请的域名，点击保存。整个过程可能需要几分钟，几分钟之后属于你的网页就可以访问里。
