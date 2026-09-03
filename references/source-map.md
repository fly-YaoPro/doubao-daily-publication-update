# 固定来源与机构配置

## 当前周总执行文档

- 2026-08-17 至 2026-08-23：`https://zqyd2vqyqmy.feishu.cn/wiki/RgQqwYIQAim7P6kSoqwchJBmn8S`
- 2026-08-24 至 2026-08-30：`https://zqyd2vqyqmy.feishu.cn/wiki/MbWMwxT6OiyDXQk3gDecYGr3nsb`
- 2026-08-31 至 2026-09-06：`https://zqyd2vqyqmy.feishu.cn/wiki/Jqnzwp8Zmivnkpksr9sci49anDb`
- 只读取“二、机构执行表格”下日期覆盖当周的机构文档。
- 新一周以群内最新总执行文档为准；旧周链接不得冒充本周来源。
- 当前外部机构执行文档入口基线为：闪光点、山恒、筑石、纽微特、志森、杭杭、萌兽、睿立、肆野、金铲子、诺信、映画。自建没有独立的当周文档入口，直接读取“每日执行看版”里当天的“日期-自建达人”区块。每次运行必须核对 12 家入口与自建区块，共计 13 家来源；缺少来源作为异常报告，不能按零发布处理。执行文档中的自建达人统一归属“自建”。
- 2026-08-31 首次登记时，“二、机构执行表格”仅有纽微特、闪光点、山恒 3 个入口；其他活跃机构在入口补齐前必须报告来源缺失。

## 客户发布表

| 平台 | 表格 | Sheet | 末列机构色 |
|---|---|---|---|
| 抖音 | `https://bytedance.larkoffice.com/wiki/Nc1ZwKb5VitIGUkVD0GcaITYnmc?sheet=RosN0G` | 视频发布（一口价） / `RosN0G` | `AR` |
| 小红书 | `https://zqyd2vqyqmy.feishu.cn/wiki/Tfduw59ylihFYQkyUtBciURbnWb?sheet=6tAENo` | 小红书视频发布 / `6tAENo` | `Z` |

## 客户工作任务审核表

| 平台 | 表格 | Sheet | 状态字段 |
|---|---|---|---|
| 抖音 | `https://bytedance.larkoffice.com/wiki/Nc1ZwKb5VitIGUkVD0GcaITYnmc?sheet=mjKGAg` | 工作任务-抖音视频审核 / `mjKGAg` | 目前进度 |
| 小红书 | `https://zqyd2vqyqmy.feishu.cn/wiki/Tfduw59ylihFYQkyUtBciURbnWb?sheet=SIjZmn` | 工作任务-小红书视频审核 / `SIjZmn` | 目前进度 |

只联动上述两张工作任务审核 Sheet，不得误改其他专项审核、发布 Sheet 或机构多维表。

## 机构多维表（本 Skill 不读）

机构当前协作表位于 Base `H0s2bjL9pa3mUpsd2eWcvIwbnfe`，按稳定名称 `机构 X 焦尾 执行表` 动态发现；全量汇总表为 `tblRtnL0U4zek1EA`。执行文档和机构多维表不是同一个东西：前者是每日发布与当周回溯的原始业务来源；后者通常由机构在次日上午补齐，只由 `$doubao-institution-publication-sync-audit` 检查登记及时性。每日发布表更新不得读取或修改机构多维表和全量表。

## 机构颜色

| 机构 | 色值 |
|---|---|
| 萌兽 | `#FBBFBC` |
| 闪光点 | `#FED4A4` |
| 纽微特 | `#FAF1D1` |
| 志森 | `#EEF6C6` |
| 睿立 | `#7EDAFB` |
| 金铲子 | `#DEE0E3` |
| 筑石 | `#FFF258` |
| 山恒 | `#34C724` |
| 杭杭 | `#AD82F7` |
| 肆野 | `#FF5833`，兼容旧色 `#F54A45` |
| 诺信 | `#FE8802` |
| 映画 | `#BACFFE` |

自建不使用机构色块；客户发布表末列直接写文字 `自建`，下游按文字识别机构归属。

## 人工复核人

- 刘朵，别名一朵
- 飞书 open_id：`ou_1948f811b81d776b153d038893751bc3`
