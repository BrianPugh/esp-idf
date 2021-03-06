有关 ESP-IDF 的最新支持政策，详见 [支持期限政策](./SUPPORT_POLICY_CN.md)。
支持期限政策
=================

* [English Version](./SUPPORT_POLICY.md)

ESP-IDF 的每个主要版本和次要版本（如 V4.0、V4.1 等）自其首次稳定版本发布之日起将维护 18 个月。

维护意味着 ESP-IDF 团队将会对 GitHub 上的发布分支继续进行 bug 修复、安全修补等，并根据需求定期发布新的 bugfix 版本。

在某一版本支持期限结束，停止更新维护 (EOL) 前，建议用户升级到较新的 ESP-IDF 版本。根据《支持期限政策》，我们将停止对 EOL 版本进行 bug 修复。

《支持期限政策》不适用于预发布版本（包括 beta、preview、`-rc` 和 `-dev` 版本等）。有时，在发布的版本中存在被标记为 "Preview" 的特定功能，则该功能也不在支持期限内。

有关 [ ESP-IDF 不同版本](https://docs.espressif.com/projects/esp-idf/zh_CN/latest/versions.html)（主要版本、次要版本、bugfix 版本等）信息，可参阅《ESP-IDF 编程指南》。

长期支持版本
------------

有些发布版本（从 ESP-IDF V3.3 开始）属于长期支持 (LTS) 版本。LTS 版本将自其首次稳定版本发布之日起维护 30 个月（2.5 年）。

我们将至少每 18 个月发布一个新的 LTS 版本。这意味着将至少有 12 个月的期限可更新至下一个 LTS 版本。

示例
-----

ESP-IDF V3.3 于 2019 年 9 月发布，属于 LTS 版本，将维护 30 个月至 2022 年 2 月停止。

- V3.3 的首个发布版本为 2019 年 9 月发布的 `v3.3`。
- ESP-IDF 团队将持续进行 bug 修复、安全修补等更新，并 backport 至分支 `release/v3.3`。
- 定期从 release 分支创建稳定的 bugfix 版本，比如，`v3.3.1`、`v3.3.2` 等，并建议用户保持使用最新的 bugfix 版本。
- V3.3 的 bugfix 版本发布将持续至 2022 年 2 月，届时所有 V3.3.x 将停止更新维护。

现有版本
--------

ESP-IDF V3.3 及所有后续更新版本都将遵守该《支持期限政策》。每一版本发布时将同时公布其支持期限。

对于该政策公布之日前发布的版本，应适用下述支持期限：

- ESP-IDF V3.1.x 和 V3.2.x 将维护至 2020 年 10 月。
- ESP-IDF V3.0.9（计划 2019 年 10 月发布）将是 V3.0 的最后一个 bugfix 版本。ESP-IDF V3.0.x 自 2019 年 10 月起停止更新维护 (EOL)。
- ESP-IDF 中 V3.0 之前的版本均已停止更新维护 (EOL)。
