# New Concept English Courseware Data (新概念英语课件库)

本项目托管《新概念英语》全四册的 CourseBand 协议课件数据，供在 `ncego.com` 等平台中作为私人远程课件源使用。

## 目录结构说明

为了最大化兼容不同的 URL 模板，仓库同时提供了两种目录格式：

- `1/`, `2/`, `3/`, `4/`：对应第一至四册（推荐格式）
- `nce1/`, `nce2/`, `nce3/`, `nce4/`：官方默认命名格式

## 远程课件地址配置（推荐使用 jsDelivr CDN）

在 `ncego.com` 课件加载框中直接填入以下任意一种地址模板：

### 推荐模板（直接匹配 `1/` 结构）：
```text
https://cdn.jsdelivr.net/gh/LAIZHANGA/nce-data@main/{id}
```

### 兼容模板（匹配 `nce1/` 结构）：
```text
https://cdn.jsdelivr.net/gh/LAIZHANGA/nce-data@main/nce{id}
```