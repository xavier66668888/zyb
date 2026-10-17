# PDS 产品需求管理 · 业务评审原型

前端演示页面，使用 HTML、CSS 和原生 JavaScript。直接打开 index.html 即可查看，无需构建。

包括需求录入、AI 情报关联和快照抽屉、产品经理待办、详情页底部处理弹窗，以及多选需求合并。合并差异字段可引用原值并手工编辑，原始申请资料保留快照。

页面均使用演示数据，不接入真实 PDS、CRM、OA 或企业微信；文件仅展示演示名称，填写和处理结果仅在当前页面临时保留。

## GitHub Pages 发布

将本目录中的 index.html、robots.txt 和 .nojekyll 放入发布分支根目录。

在仓库 Settings → Pages 中选择 Deploy from a branch，分支选择 main，目录选择 / (root)，保存并等待部署完成。

代码中情报详情链接基于当前页面地址生成，适用于 GitHub Pages 的项目子路径。

仅发布本目录的静态文件；不上传本地部署配置、依赖目录或账号凭证。
