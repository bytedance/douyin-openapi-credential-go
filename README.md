# Douyin OpenAPI SDK Credential for Go
本项目是抖音开放平台OpenAPI SDK Credential模块的Go语言实现。
该模块提供了获取抖音开放平台client_token以及access_token的方法，并且提供token过期自动刷新的能力。但是该代码仅支持单实例的情况下使用，如果需要在多实例场景下获取token需要实现Credential接口中的getClientToken()和getAccessToken()方法。


## 要求
您需要确保本地安装的 go 环境版本大于 1.12.0.

## 安装
你可以使用 go mod 来管理你的依赖
```
go get github.com/bytedance/douyin-openapi-sdk/credential-go
```

## 发行说明
每个版本的详细更改记录在[发行说明](./ChangeLog.txt)中。


## 许可证
[Apache-2.0](http://www.apache.org/licenses/LICENSE-2.0)

Copyright 2024 ByteDance Ltd. and/or its affiliates.