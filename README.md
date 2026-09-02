# limidation.ca — Xu Tile Installation Inc.

基础版网站，纯 HTML/CSS/JS，无需任何构建步骤，可直接部署到 Netlify。

## 文件说明
- `index.html` 首页
- `projects.html` 项目案例
- `team.html` 团队（占位，以后加工人板块）
- `contact.html` 联系我们 / 留言表单（已接入 Netlify Forms，部署后自动生效）
- `css/style.css` 样式
- `js/lang.js` 中英文切换逻辑（以后加新语言只需扩展这个文件的 `langs` 数组）
- `images/` 放照片的文件夹（目前是空的，占位）

## 上传到 GitHub 仓库步骤
1. 打开仓库页面（Chinish-AI/limidation.ca）
2. 点击"上传已有文件"（Add file → Upload files）
3. 把这个文件夹里所有文件和文件夹一起拖进去（保持文件夹结构不变）
4. 提交（Commit changes）

## 部署到 Netlify 步骤
1. 登录 Netlify，选择 "Add new site" → "Import an existing project"
2. 选择 GitHub，授权后选中 `limidation.ca` 这个仓库
3. Build command 留空，Publish directory 填 `.`（表示根目录）
4. 点 Deploy，几分钟后会给一个临时网址（类似 xxx.netlify.app）先用这个网址检查效果

## 之后接自己的域名
网站在 Netlify 上确认没问题后，再去域名注册商后台把 limidation.ca 的 DNS 指向 Netlify 提供的记录（Netlify 部署成功页面会显示具体数值）。
