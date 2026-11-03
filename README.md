# koyunoss

Koyun 客户端启动引导配置（Cloudflare Pages 静态托管）。

- `boot.json`：加密 + 签名的配置文件，由 koyun_vpn 仓库的 `tools/bootstrap.py` 生成，**不要手动修改**。
- `_headers`：Cloudflare Pages 响应头（缓存 60 秒）。

Cloudflare Pages 设置：框架预设选 **None**，构建命令留空，输出目录填 `/`。
