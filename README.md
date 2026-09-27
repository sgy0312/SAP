# SAP

SAP 相关项目的一级目录。当前内容按技术栈继续划分为二级目录：

```text
SAP/
└── ABAP/
    ├── BOM-Batch-Query/
    ├── Batch-production-order-Reporting-Cancel/
    ├── Bulk-cancellation-of-production-orders-and-cancellation-of-settlement/
    ├── Customized-program-translation/
    ├── Enhanced-validation-of-SAP-production-order-standard-price/
    ├── Equipment-MTBF-MTTR-Report/
    ├── SAP-BOM-upload-and-download/
    ├── SAP-Sales-Order-Bom-Report/
    └── ZMD04/
```

## 二级目录

- [`ABAP/`](ABAP/)：ABAP 报表、增强、批处理工具、源码和导入模板。

## 整理规则

- 每个项目使用独立目录。
- ABAP 源码放在项目的 `src/` 目录，并使用 `.abap` 扩展名。
- Excel 导入模板放在项目的 `templates/` 目录。
- 每个项目的 README 单独记录 SAP 对象名、依赖、部署步骤和运行注意事项。
- 源码以参考实现为主，部署前需结合目标 SAP 版本、增强点、权限和自定义对象进行验证。

最后整理日期：2026-09-27。
