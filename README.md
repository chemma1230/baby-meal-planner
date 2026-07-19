# 宝宝每周食谱规划器

这是一个完全免费、无需服务器的 MVP。

## 功能
- 添加和删除食谱
- 按规则生成一周菜单
- 锁定某一餐
- 单独更换某一餐
- 排除过敏原
- 工作日限制烹饪时间
- 生成购物清单
- 导入和导出 JSON 备份
- 使用浏览器 localStorage 保存数据

## 本地运行
直接双击 `index.html` 即可使用。

## 免费部署到 Vercel
1. 新建 GitHub 仓库。
2. 上传 `index.html`。
3. 在 Vercel 中导入该 GitHub 仓库。
4. Framework Preset 选择 `Other`。
5. Deploy。

也可以部署到 GitHub Pages、Netlify 或 Cloudflare Pages。

## 分享机制
朋友打开同一个网址即可使用，但每个人的数据保存在各自浏览器里，彼此看不到。

## 下一阶段建议
- Supabase 登录和云端同步
- 用户自己的宝宝档案
- 共享食谱模板库
- 编辑食谱
- 食材库存与保质期
- 更严格的营养规则
