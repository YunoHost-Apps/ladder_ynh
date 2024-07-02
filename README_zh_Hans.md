<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Ladder

[![集成程度](https://dash.yunohost.org/integration/ladder.svg)](https://ci-apps.yunohost.org/ci/apps/ladder/) ![工作状态](https://ci-apps.yunohost.org/ci/badges/ladder.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/ladder.maintain.svg)

[![使用 YunoHost 安装 Ladder](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=ladder)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Ladder。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

Freedom of information is an essential pillar of democracy and informed decision-making. While media organizations have legitimate financial interests, it is crucial to strike a balance between profitability and the public's right to access information. The proliferation of paywalls raises concerns about the erosion of this fundamental freedom, and it is imperative for society to find innovative ways to preserve access to vital information without compromising the sustainability of journalism. In a world where knowledge should be shared and not commodified, paywalls should be critically examined to ensure that they do not undermine the principles of an open and informed society.

Some sites do not expose their content to search engines, which means that the proxy cannot access the content. A future version will try to fetch the content from Google Cache.

Certain sites may display missing images or encounter formatting issues. This can be attributed to the site's reliance on JavaScript or CSS for image and resource loading, which presents a limitation when accessed through this proxy. If you prefer a full experience, please consider buying a subscription for the site.

**分发版本：** 0.0.21~ynh2

## 截图

![Ladder 的截图](./doc/screenshots/example.png)

## 文档与资源

- 上游应用代码库： <https://github.com/everywall/ladder>
- YunoHost 商店： <https://apps.yunohost.org/app/ladder>
- 报告 bug： <https://github.com/YunoHost-Apps/ladder_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/ladder_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/ladder_ynh/tree/testing --debug
或
sudo yunohost app upgrade ladder -u https://github.com/YunoHost-Apps/ladder_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
