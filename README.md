# 量潮学术研究工作档案

学术研究领域的工作档案：学者、团队与组织的档案。

## 专题

五个专题原为独立仓库（`quanttide-research-of-*`），2026-09-21 以 git subtree 并入本仓，提交历史保留：

| 目录 | 内容 |
|---|---|
| `cloud-computing-economics/` | 云计算经济学：`proposals/`（自然垄断、公共化） |
| `data-economics/` | 数据经济学：Jupyter Book 工程 + `proposals/`（数据要素） |
| `economic-models/` | 经济模型：Jupyter Book 工程 + `proposals/`、`topics/` |
| `open-source-economics/` | 开源经济学：Jupyter Book 工程 + `facts/`、`ideas/`、`literatures/`、`proposals/` |
| `token-economics/` | 代币经济学：Jupyter Book 工程 + 三章书稿 + `proposals/` |

## 已知状态

- 各专题根级的 `_config.yml`、`_toc.yml`、`index.md` 与 `.github/workflows/jupyterbook-publish.yml` 是原书稿的工程配置；嵌套进本仓后不再生效。要恢复发布，需重排为一本书，或改为按目录触发的工作流。
- `open-source-economics/literatures/` 原有四份 PDF 走 Git LFS，其对象在源仓远端已缺失（404）、无法恢复；这四份文件未并入本仓（坏指针会让仓库无法推送），文件名、大小与 sha256 记在 `open-source-economics/literatures/README.md`，其对应的 Git LFS 配置与历史一并剥离。

## 许可

[CC BY 4.0](LICENSE)
