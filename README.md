# 知识库 GitHub Pages 部署说明

## 部署步骤
1. 在 GitHub 创建一个新仓库（如 knowledge-base）
2. 将以下 3 个文件上传到仓库根目录：
   - **data.json**（刚下载的，包含你的知识库数据）
   - **index.html**（把你当前使用的 knowledge-base.html 重命名为 index.html）
   - **README.md**（本说明文件）
3. 进入仓库 Settings → Pages
4. Source 选择 "Deploy from a branch"
5. Branch 选择 "main"，目录选 "/ (root)"，点击 Save
6. 等待 1-2 分钟后，访问 https://你的用户名.github.io/仓库名/

## 更新数据
在本版本更新知识库后，重新导出 data.json 替换 GitHub 仓库中的文件即可。

## 注意事项
- 共享版为只读，访客可浏览、搜索、问答，但不能上传编辑
- 智能问答需访客自行配置 API Key
- data.json 包含文件原始数据，可能较大（GitHub 单文件限制 100MB）
