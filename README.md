# UM Programme Code Finder（学院→专业联动版）

公开静态网站，保留原始 160 条专业代码和 19 个学院/单位。

使用方式：先选择学院，再从仅显示该学院专业的下拉框选择专业，显示代码并一键复制。不需要输入搜索关键词。

署名：小红书 KJ7860 · Instagram @lynnie_khoo。

## 更新已上线的网站
解压 ZIP，将四个文件直接上传到原 GitHub 仓库的根目录，替换同名文件并 Commit changes。Render 若已启用 Auto-Deploy，将自动更新。

## Render Static Site
- Branch: main
- Root Directory: 留空
- Build Command: echo "Static site ready"
- Publish Directory: .

注意：静态网站的 data.json 公开可访问。专业代码请以 UM 最新官方数据为准。
