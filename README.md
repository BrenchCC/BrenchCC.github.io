# BrenchCC.github.io

Brench 的个人站点仓库，基于 Jekyll。

## 当前站点内容

- 首页展示：GitHub 项目卡片流
- About 页面：个人介绍 + 项目展示
- Tags 页面：大模型方向标签导航（不展示历史博文）
- 外部链接：小红书主页
  - https://www.xiaohongshu.com/user/profile/64ccf1d6000000000b00a502

## 项目展示仓库

- https://github.com/TIGER-AI-Lab/Mantis
- https://github.com/BrenchCC/VLMEvalKit/tree/contribution
- https://github.com/BrenchCC/InternVL2.5-NPU-Training
- https://github.com/BrenchCC/Deep-Learning-From-Scratch-PyTorch
- https://github.com/BrenchCC/QuarkAgent-FromScratch
- https://github.com/BrenchCC/claude-code-building-learning
- https://github.com/BrenchCC/LLM_Lab
- https://github.com/BrenchCC/FeiShu-Document-Convertor

## 本地预览

```bash
cd /Users/brench/brench_project_collections/Self_Learning_Project/BrenchCC.github.io
export PATH="$HOME/.gem/ruby/2.6.0/bin:$PATH"
jekyll serve --host 127.0.0.1 --port 4000
```

浏览器访问：`http://127.0.0.1:4000/`

## 关键文件

- `_config.yml`：站点信息、项目列表、标签配置
- `index.html`：首页项目流
- `about.html`：About 页面内容
- `tags.html`：标签导航页
- `_layouts/page.html`：侧边栏渲染
- `_includes/footer.html`：页脚链接

## License

MIT
