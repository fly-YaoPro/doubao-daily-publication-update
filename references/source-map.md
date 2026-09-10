# 来源解析

先按 SKILL.md 的公共配置步骤读取本次 `business-context`，此文件不保存来源地址副本。

## 周执行文档

使用 `sources.weeklyExecutionDocument` 中业务日期对应的链接。正式机构入口在“二、机构执行表格”；自建入口在“每日执行看版”中当天的“日期-自建达人”。实际入口必须覆盖公共机构清单；缺失入口是来源缺失，不是零发布。跨周补跑必须按对应业务日期重新取配置，不能沿用最新周链接。

## 客户流程

独立端是电子表格（Sheets），不是机构多维表；发布页由公共配置根 URL 与 `publication.id=urUTaQ` 定位，审核页为 `k7ZXFh`。以真实发布日期核对，不靠周期标签筛选当天。

- 原抖音、小红书：`sources.customers.douyin` / `sources.customers.xiaohongshu`，分别提供 `publication` 与 `review`。工作任务和课程教学共享平台表，按内容方向与项目字段分开。
- 独立端：`sources.customers.independent`。每日发布更新只修改唯一匹配的已有审核记录；发布页客户维护，禁止新增或改写发布行。
- 机构标记列读取各 publication 的 `markerColumn`；颜色读取 `policy.institutionColors`，兼容色读取 `legacyInstitutionColors`。自建使用 `selfBuiltInstitution` 文字，不借用其他机构颜色。
- 实际字段仍须按实时表头校验；地址配置不能证明目标表字段完全兼容。

## 机构多维表边界

本 Skill 的发布事实来自当周执行文档，不读取或修改机构多维表与全量表。机构次日登记由专门的进度检查流程核对。不得因执行文档缺记录而拿机构表替代。

## 人工复核人

- 刘朵，别名一朵
- 飞书 open_id：`ou_1948f811b81d776b153d038893751bc3`
