# UM Programme Code Finder

公开免费的马来亚大学研究生专业代码查询网站，含 160 条记录、19 个学院/研究单位。

## Render 部署（推荐）
1. 解压 ZIP，将 `index.html`、`data.json`、`render.yaml` 上传到同一个 GitHub 仓库根目录。
2. Render Dashboard → New → Static Site → Connect GitHub repository。
3. Build Command: `echo "Static site ready"`；Publish Directory: `.`。
4. 选择 Free（如有选项），点击 Deploy Static Site。完成后获取 `https://你的名称.onrender.com`。
5. 修改 GitHub 文件后，Render 可自动重新部署。

也可以选择 Render Dashboard → New → Blueprint，读取仓库根目录的 `render.yaml`。

## 本地预览
在项目文件夹打开终端运行 `python -m http.server 8000`，浏览器打开 `http://localhost:8000`。不要直接双击 HTML，因为浏览器可能阻止读取本地 JSON。

## 数据与限制
- 数据来自用户提供的 Excel `专业代码库` 工作表。
- 主要来源 UM 2024/2025 研究生手册，并非最新完整课程名录。
- 页面不提供 Excel 下载，但 `data.json` 是公开文件，技术人员仍可下载；静态网站无法保护原始数据。
- 官方网站链接逐条保留，需以 UM MAYA 最新记录核对。
- 本网站非 Universiti Malaya 官方服务。
