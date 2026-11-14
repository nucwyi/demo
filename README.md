# demo

最小 GitHub Pages 中文演示仓库。

## 本次新增内容

- `docs/index.html`：纯静态中文测试页，无外部依赖、无表单、无数据收集。
- `.github/workflows/pages.yml`：官方 GitHub Pages Actions 工作流，发布 `docs/` 目录。

## 预期访问地址

- `https://nucwyi.github.io/demo/`

说明：

- 这是 GitHub Pages 分配的仓库路径地址，不是独立域名。
- 若仓库尚未启用 Pages，或分支/PR 还未合并，以上地址可能暂时不可访问。

## 如需启用官方 Pages

仓库设置路径：

1. `Settings`
2. `Pages`
3. `Build and deployment`
4. `Source` 选择 `GitHub Actions`

完成后，工作流可部署 `docs/` 中的静态页面。
