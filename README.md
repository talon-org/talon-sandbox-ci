# talon-sandbox-ci

Talon Sandbox 平台的持续构建仓库。

## 构建产物

发布版本可在 [Container Registry](https://github.com/orgs/talon-org/packages) 与官方文档站获取。

| 产物 | 位置 |
| --- | --- |
| Linux 二进制(`sandbox-api` / `sandbox-worker` / `sandbox-bootstrap`)| Release 资产 |
| systemd 部署 tarball | Release 资产 |
| Docker 镜像 | `ghcr.io/talon-org/agent-sandbox:<tag>` |

## 平台约束

- 仅支持 linux/amd64
- 运行时依赖 `libtalon.so`,Release tarball 已随附

## 文档

完整使用与部署文档:[docs.sandbox.talon.net.cn](https://docs.sandbox.talon.net.cn)
