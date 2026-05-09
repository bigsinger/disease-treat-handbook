# 项目文档

## 书籍信息

- **书名**：常见病症及治疗指南
- **版本**：v1.0.0
- **作者**：Sing
- **创建日期**：2026-05-09

## 目录结构

```
disease-treat-handbook/
├── README.md               # 书籍介绍
├── SUMMARY.md              # GitBook 目录
├── CHANGELOG.md            # 修订记录
├── part1/                  # 第一篇 · 家庭用药基础
├── part2/                  # 第二篇 · 内科常见病症
├── part3/                  # 第三篇 · 外科与皮肤问题
├── part4/                  # 第四篇 · 特殊人群用药指南
├── part5/                  # 第五篇 · 户外急救与实用附录
├── doc/                    # 项目文档
└── assets/                 # 图片等资源
```

## 技术说明

本书使用 GitBook Maker 技能创建，遵循 handbook 模板结构。章节内部采用七段式手册结构。

## 维护说明

- 每章修改后需运行 `add_navigation.py` 刷新导航链接
- 发布前运行 `quality_scan.py` 进行质量检查
- CHANGELOG.md 记录所有版本变更
