# Teaching-Calendar

教学日历仓库 — 校历总览 + 各年级各科教学进度。

## 目录结构

```
├── 校历总览.md            # 学期总览（周次、考试、假期）
├── schedule.json          # 课表数据（Dashboard 读取）
├── src/                   # 各年级各科进度文件
│   ├── README.md
│   ├── 初中/
│   │   ├── 七年级/语文/上学期.md
│   │   ├── 七年级/语文/下学期.md
│   │   ├── 八年级/...
│   │   └── 九年级/...
│   └── 高中/
│       └── 高一/...
├── AGENTS.md              # 日历维护规范
└── .gitignore
```

## 更新规则

- 学期初更新校历总览.md（年份、开学日期、假期）
- 每周更新教学进度（已完成/待完成标注）
- schedule.json 需手动同步或通过 Dashboard 管理

## 关联仓库

| 仓库 | 关系 |
|------|------|
| [Teaching-Dashboard](https://github.com/1686756626/Teaching-Dashboard) | 读取校历总览.md + schedule.json |
| [Teaching-Materials](https://github.com/1686756626/Teaching-Materials) | 按周次组织备课材料 |
