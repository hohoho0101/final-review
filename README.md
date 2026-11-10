# 期末复习方案 · 微积分 / 线性代数 / C++

华南理工大一上学期期末复习网站：考试倒计时、九周计划（每科每周两件事，可打勾）、三科必考题型与速查表、C++ 代码模板和陷阱清单。

整个网站只有一个 `index.html`，没有任何外部依赖（不用 CDN、不用 Google 字体），国内打开也快。

## 部署到 GitHub Pages（约 5 分钟）

1. 登录 GitHub，右上角 **+** → **New repository**，名字随便取，例如 `final-review`，选 **Public**，点 **Create repository**。
2. 在新仓库页面点 **uploading an existing file**，把 `index.html` 和 `README.md` 拖进去，点 **Commit changes**。
3. 进入仓库的 **Settings** → 左侧 **Pages**。
4. **Source** 选 **Deploy from a branch**，Branch 选 `main`、文件夹选 `/ (root)`，点 **Save**。
5. 等 1–2 分钟刷新，页面顶部会显示网址：`https://你的用户名.github.io/final-review/`

> 如果 github.io 在校园网打开慢，也可以把同一个 `index.html` 拖到 Cloudflare Pages 或 Vercel 部署；或者直接双击 `index.html` 在本地浏览器打开，功能完全一样。

## 怎么改

- **考试日期**：直接在网页的倒计时卡片里改，会自动保存。
- **每周任务**：用任意文本编辑器打开 `index.html`，搜索 `const WEEKS`，按格式改文字即可。每周有 `calc`（微积分）、`la`（线性代数）、`cpp`（C++）三个任务列表。
- **默认考试日期**：搜索 `DEFAULT_DATES` 修改。

## 说明

- 打勾记录和考试日期保存在浏览器的 localStorage 里，只对当前设备 / 浏览器有效，换手机或清缓存会丢失。
- C++ 的题型与分值参考华南理工《高级语言程序设计(C++)(一)》考试大纲；微积分范围参考微积分Ⅰ(一) 课程简介。具体以任课老师和教务处通知为准。
