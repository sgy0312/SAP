# SAP

SAP 相关项目仓库集合。各项目以独立目录平铺存放，均为独立的 git 子仓库。

## 项目列表

```text
SAP/
├── BOM-Batch-Query/
├── Bulk-cancellation-of-production-orders-and-cancellation-of-settlement/
├── Customized-program-translation/
├── Enhanced-validation-of-SAP-production-order-standard-price/
├── SAP-Sales-Order-Bom-Report/
└── ZMD04/
```

## 各项目简介

| 目录 | 说明 |
|------|------|
| [BOM-Batch-Query](BOM-Batch-Query/) | 多种展开方式 BOM 查询报表 |
| [Bulk-cancellation-of-production-orders-and-cancellation-of-settlement](Bulk-cancellation-of-production-orders-and-cancellation-of-settlement/) | 生产订单批量取消 TECO & 取消结算 |
| [Customized-program-translation](Customized-program-translation/) | 批量翻译程序文本 |
| [Enhanced-validation-of-SAP-production-order-standard-price](Enhanced-validation-of-SAP-production-order-standard-price/) | 生产订单标准价增强校验 |
| [SAP-Sales-Order-Bom-Report](SAP-Sales-Order-Bom-Report/) | 销售订单 BOM 批量查询报表 |
| [ZMD04](ZMD04/) | 批量查询物料 MD04 程序 |

## 整理规则

- 每个项目使用独立目录，均为独立 git 仓库。
- ABAP 源码统一放在各项目的 `src/` 目录，并使用 `.abap` 扩展名。
- 每个项目的 README 单独记录 SAP 对象名、依赖、部署步骤和运行注意事项。
- 源码以参考实现为主，部署前需结合目标 SAP 版本、增强点、权限和自定义对象进行验证。

最后维护日期：2026-09-28。