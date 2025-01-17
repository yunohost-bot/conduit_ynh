<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Conduit

[![集成程度](https://dash.yunohost.org/integration/conduit.svg)](https://ci-apps.yunohost.org/ci/apps/conduit/) ![工作状态](https://ci-apps.yunohost.org/ci/badges/conduit.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/conduit.maintain.svg)

[![使用 YunoHost 安装 Conduit](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=conduit)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Conduit。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

Conduit is a lightweight open-source server implementation of the Matrix Specification with a focus on easy setup and low system requirements. That means you can make your own Conduit setup in just a few minutes.
Conduit keeps things simple, it's a single binary with an embedded database and can be much faster than other server implementations in some cases.

**分发版本：** 0.8.0~ynh3
## 文档与资源

- 官方应用网站： <https://conduit.rs/>
- 官方管理文档： <https://docs.conduit.rs/>
- 上游应用代码库： <https://gitlab.com/famedly/conduit>
- YunoHost 商店： <https://apps.yunohost.org/app/conduit>
- 报告 bug： <https://github.com/YunoHost-Apps/conduit_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/conduit_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/conduit_ynh/tree/testing --debug
或
sudo yunohost app upgrade conduit -u https://github.com/YunoHost-Apps/conduit_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
