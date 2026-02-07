# ProjectDrone

一个以“安全、合规、可控”为核心的开源无人机落地项目文档库。

本仓库聚焦于在澳洲监管环境下，从零到第一次合规飞行的可执行路径，优先验证边界与风险控制，而不是追求性能或商业化速度。

## 项目目标

- 在非公众场景完成首次安全飞行验证
- 建立可复用的硬件、软件、流程基线
- 用明确边界降低试飞风险与合规风险

## 仓库内容

- `PRD.md`: 项目一页版 PRD，定义范围、边界、成功/失败标准
- `SOP.md`: 首飞标准作业流程（SOP）
- `Manual.md`: 从软件安装到首次可解锁起飞的执行说明
- `Checklist.md`: 从设备到合规再到试飞复盘的检查清单
- `Hardware.md`: 硬件采购建议与预算区间
- `Software.md`: 开源软件栈选择建议（ArduPilot / Mission Planner / SITL 等）
- `Regulation.md`: 澳洲监管逻辑与场景可行性分析

## 推荐阅读顺序

1. `PRD.md`
2. `Regulation.md`
3. `Hardware.md`
4. `Software.md`
5. `Manual.md`
6. `SOP.md`
7. `Checklist.md`

## 当前阶段边界

- 白天飞行
- 非公众区域
- 目视范围内操作（VLOS）
- 不飞越无关人员
- 高度不超过 120 米

任何超出上述边界的需求，默认不在当前阶段范围内。

## 使用方式

- 按 `Hardware.md` 和 `Software.md` 完成最小系统搭建
- 按 `Manual.md` 完成刷写与校准
- 严格执行 `SOP.md` 与 `Checklist.md` 后再进行首飞
- 每次飞行后做日志复盘并记录风险项

## 免责声明

本仓库内容用于学习与工程实践参考，不构成法律或监管建议。实际飞行前请以澳洲 Civil Aviation Safety Authority（CASA）及场地管理方最新要求为准。
