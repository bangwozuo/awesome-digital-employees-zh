# Contributing to Awesome Digital Employees

感谢你对数字员工生态的兴趣！本指南帮助你快速参与贡献。

## 贡献类型

| 类型 | 说明 | 示例 |
|------|------|------|
| 添加资产 | 新增精选资产包、技能、工作流或连接器 | 提交新的数字员工包 |
| 更新信息 | 修正现有资产的描述、链接或状态 | 修复失效链接 |
| 改进文档 | 优化说明文字、分类或导航 | 改进README |
| 报告问题 | 发现错误、失效链接或不当内容 | 提交Issue |

## 提交规范

### 添加新资产

1. **Fork** 本仓库
2. 在对应分类下添加条目，遵循现有格式
3. 确保资产符合 [digital-employee-spec](https://github.com/bangwozuo/digital-employee-spec)
4. 提交 **Pull Request**，使用 PR 模板

### 资产条目格式

```markdown
### 资产名称
- **ID**: `asset-id`（小写蛇形，唯一）
- **描述**: 一句话说明（30字以内）
- **分类**: 对应 [digital-employee-taxonomy](https://github.com/bangwozuo/digital-employee-taxonomy) 分类
- **来源**: 原仓库链接
- **License**: 原仓库License
```

### Commit Message 规范

```
add: <asset-name> to <category>
update: <description>
fix: <description>
docs: <description>
```

## 审核标准

- [ ] 资产必须开源或有明确的使用许可
- [ ] 资产必须符合 digital-employee-spec 规范
- [ ] 描述必须准确、客观、无夸大
- [ ] 链接必须有效
- [ ] 不得包含恶意代码或不当内容

## 行为准则

所有贡献者必须遵守 [CODE_OF_CONDUCT.md](./CODE_OF_CONDUCT.md)。

## 获取帮助

- 提交 [Issue](https://github.com/bangwozuo/awesome-digital-employees-zh/issues)
- 阅读 [SUPPORT.md](./SUPPORT.md)
