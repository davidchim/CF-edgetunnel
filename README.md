# Edge Tunnel

Edge Tunnel 是一个基于 Cloudflare Pages 的免费代理解决方案, 配置精简, 适合新手快速上手

## 项目特点

- **免费**：利用 Cloudflare Pages 免费托管
- **易用**：通过环境变量灵活配置
- **兼容性强**：支持 v2ray 和 clash 客户端

> **欢迎各位大佬指正代码中存在的问题！**

如果本项目对您有帮助, 请点 Star 支持 !

## 使用方法

1. **Fork 本项目**
2. **创建 Cloudflare Pages**
- **导入您 Fork 的仓库**
- **添加环境变量**
- **保存并部署**
4. **导入订阅(域名/订阅路径)并开始使用**

## 环境变量说明

| 变量名 | 示例值 | 说明 |
|-|-|-|
| SUB_PATH | `订阅路径` | 域名/`订阅路径` |
| PROXY_IP | `proxyip.cmliussss.net` | 反代地址和端口, 端口不填默认 `443` |
| FAKE_WEB | `baidu.com` | 伪装网页 |

## 不再提供优选IP