# docker/docker-install
这是 `get.docker.com` 和 `test.docker.com` 安装脚本的源代码仓库！

本安装脚本的目的是为了方便在支持的 Linux 发行版上快速安装最新版本的 Docker-CE。
不建议在生产系统部署中依赖此脚本。有关在支持的发行版上安装的更详细说明，
请参阅[安装说明](https://docs.docker.com/engine/install/)。

本仓库由 Docker, Inc. 独家维护。

## 使用方法：

从 `https://get.docker.com` 安装：
```shell
curl -fsSL https://get.docker.com -o get-docker.sh
sh get-docker.sh
```

从 `https://test.docker.com` 安装：
```shell
curl -fsSL https://test.docker.com -o test-docker.sh
sh test-docker.sh
```

从源代码仓库安装（这将从`stable`通道安装最新版本）：
```shell
sh install.sh
```

## 测试：

要验证安装脚本在支持的操作系统中是否正常工作，请运行：

```shell
make shellcheck
```

## 法律声明
*此声明由我们的法律顾问提供。更多上下文信息，
请参阅本仓库中的 [NOTICE](NOTICE) 文档。*

Docker 的使用和转让可能受到美国和其他政府的某些限制。

确保您的使用和/或转让不违反适用法律是您的责任。

更多信息，请访问 https://www.bis.doc.gov

## 报告安全问题

维护者非常重视安全问题。如果您发现安全漏洞，
请立即告知我们！

请**不要**公开提交问题，而是将您的报告私下发送至
[security@docker.com](mailto:security@docker.com)。

我们非常感谢安全报告，并会公开感谢您的贡献。
我们也喜欢赠送礼物—如果您对 Docker 周边感兴趣，请务必告诉
我们。目前我们没有提供付费的安全漏洞奖励计划，但不排除
将来会推出。

## 许可证

docker/docker-install 基于 Apache License, Version 2.0 授权。
完整的许可证文本请参见 [LICENSE](LICENSE)。
