---
sidebar_position: 1
---

# 数据平台介绍

天工LCA数据平台提供四大核心数据模块，支持用户进行生命周期评估数据的查看、管理和分析。所有模块均包含模型、过程、流、流属性、单位、来源和联系人信息，但操作权限有所不同。

## 开放数据

**开放数据**模块提供经过平台审核的标准化生命周期评估数据集，所有用户均可查看和引用。主要特点包括：

- 数据来源：公开可获得的数据来源
- 数据权限：仅支持查看和使用数据
- 数据发布：用户创建的数据集通过审核后可发布至此模块
- 数据应用：支持搜索、筛选和引用，适用于研究和分析场景

## 商业数据

**商业数据**模块提供商业化生命周期评估数据集的元数据信息，主要特点包括：

- 数据内容：仅展示数据集元数据（描述性信息）
- 数据权限：仅支持查看元数据
- 数据获取：用户可联系数据提供商获取完整数据集
- 数据发布：商业用户可通过平台发布经审核的元数据

## 我的数据

**我的数据**模块是用户进行数据创建和管理的核心区域，支持完整的数据操作权限。模块包含以下功能：

- **模型**：支持可视化构建产品生命周期评估模型
- **过程**：创建和管理单元过程，保存产品模型核算结果
- **流**：创建和编辑产品流、废物流
- **流属性**：定义流的物理、化学、经济属性及组成
- **单位**：创建和管理单位组（物理单位、货币单位、能量单位等）
- **来源**：管理数据引用来源和图片文件，支持文献、报告等
- **联系人**：维护个人及团队联系信息

注意：不建议新建流属性和单位，建议使用平台提供的标准属性和单位，以保证将来可以正常计算LCIA结果。

## 团队数据

**团队数据**模块用于管理和共享团队协作数据，主要特点包括：

- 数据权限：仅支持查看
- 数据范围：可查看已加入团队的所有数据
- 数据管理：团队管理员可在"我的数据"模块进行数据维护
- 协作支持：支持团队成员间的数据共享和引用

## 数据操作权限说明

| 功能模块 | 查看 | 新建 | 编辑 | 删除 |
|----------|------|------|------|------|
| 开放数据 | ✔️   | ❌   | ❌   | ❌   |
| 商业数据 | ✔️   | ❌   | ❌   | ❌   |
| 我的数据 | ✔️   | ✔️   | ✔️   | ✔️   |
| 团队数据 | ✔️   | ❌   | ❌   | ❌   |

## 数据管理最佳实践

1. **数据标准化**：建议使用平台提供的标准单位和分类体系
2. **数据引用**：使用来源模块规范记录数据引用信息
3. **权限管理**：合理设置团队数据访问权限
4. **版本控制**：定期备份重要数据，记录变更历史
5. **数据审核**：提交开放数据前确保数据完整性和准确性
