# GlobalNet 外贸网络服务展示网站

这是一个单文件、响应式 HTML 网站，可直接部署到 GitHub Pages。无需构建工具、服务器或第三方 JavaScript 库。

## 文件
- `index.html`：网站全部内容、样式和交互。

## 上线前请先修改
在 `index.html` 中搜索并替换：
1. `GlobalNet`：替换为你的品牌名称。
2. `your-email@example.com`：替换为你的商务邮箱。
3. `your_username`：替换为你的 Telegram 用户名。
4. `00000000000`：替换为 WhatsApp 国际号码（国家代码+号码，不加 `+`）。
5. 联系方式区的微信/其他联系方式文字。
6. 按你实际提供的服务调整服务介绍；不要保留不符合实际情况的描述。

## GitHub Pages 部署
1. 在 GitHub 新建一个仓库，例如 `globalnet-site`。
2. 上传 `index.html` 到仓库根目录并提交。
3. 进入仓库 `Settings` → `Pages`。
4. 在 `Build and deployment` 中选择 `Deploy from a branch`。
5. Branch 选择 `main`，文件夹选择 `/(root)`，点击保存。
6. 等待 GitHub Pages 部署完成，页面会显示网站地址。

## 绑定自定义域名
1. 在仓库 `Settings` → `Pages` → `Custom domain` 输入你的域名，例如 `blog.example.com`。
2. 在 DNS 服务商处为子域名添加 CNAME 记录：
   - 名称/主机记录：`blog`
   - 目标/记录值：`你的GitHub用户名.github.io`
3. 等 DNS 生效后，在 Pages 设置中启用 `Enforce HTTPS`。
4. 如果绑定的是根域名（例如 `example.com`），DNS 记录配置不同，不要直接照搬上面的 CNAME 子域名配置。

## 注意
- 这是静态网站，联系卡片会打开邮件或外部聊天链接，不包含后台、在线支付或自动工单系统。
- 当前所有联系信息都是示例占位符。请在公开网站上线前换成真实联系方式。
- 页面未使用虚构的运营商合作声明、覆盖数量或性能数据。
