# 图片转存

我的一个项目需要使用谷歌图片服务器上的图片, 于是面临了几个问题：

1. 图片被墙，不能正常访问
2. 图片总量庞大，不能全爬
3. 我的服务器属于极轻量级，不能用来存储文件

于是便有了这个服务：

服务提供一个接口，接口接受一个参数：图片url

1. 服务下载指定图片
2. 上传图片到免费图床
3. 返回图床上的图片url等信息

## 部署

1. 安装 now
> npm install -g now

2. 部署
> now


## 接口

> /?url={image url}
