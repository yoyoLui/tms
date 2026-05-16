# 02-系统设计 · 待 M1 阶段产出

PRD v1.0 完成后，本目录将产出以下文档（全部用 Mermaid 绘制）：

- `architecture-c4.md` — C4 模型架构图（Context / Container / Component）
- `database-er.md` — ER 图与 30+ 核心表设计
- `sequence-diagrams.md` — 关键业务时序图：
  - 下单到签收的完整链路
  - GPS + 温度采集 → 报警链路
  - 派车撮合算法时序
  - 出入库 + 装载对接
- `iot-protocol.md` — 车载终端通讯协议设计（MQTT topic / 消息格式）
- `state-machines.md` — 订单状态机 / 调度单状态机
- `module-boundary.md` — 7 大子系统的边界、职责、依赖关系
