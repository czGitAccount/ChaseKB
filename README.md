# UDS 诊断笔记（个人知识库）

ISO 14229（UDS）诊断服务详解与报文示例 — 纯静态单页笔记站，由 Markdown 自动生成，GitHub Pages 托管。

## 在线访问

开启 GitHub Pages 后访问：`https://<你的用户名>.github.io/<仓库名>/`

## 本地更新流程

修改 Markdown 后重新生成并推送：

```bash
python .workbuddy/md2html.py        # 在工作区根目录执行，重新生成本仓库的 index.html
cd github/ChaseKB
git add index.html
git commit -m "update notes"
git push
```

## 特性

- 响应式布局，手机/平板/电脑自适应
- 侧边目录 + 目录搜索 + 阅读进度条 + 当前章节高亮
- 亮色/暗色主题（跟随系统，可手动切换并记忆）
- 单文件零依赖，无需构建工具
