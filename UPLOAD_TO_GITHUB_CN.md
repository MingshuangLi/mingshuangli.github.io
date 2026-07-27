# 在 GitHub Pages 上发布网站：逐步操作

## 1. 先在电脑上检查网站

1. 解压下载的 ZIP 文件。
2. 打开解压后的文件夹。
3. 双击 `index.html`。
4. 浏览器会显示网站。检查姓名、邮箱、电话、照片、论文和经历。

## 2. 注册或登录 GitHub

1. 打开 GitHub。
2. 登录账号；没有账号就先注册。
3. 记下你的 GitHub 用户名。

## 3. 新建 repository

1. GitHub 右上角点击 `+`。
2. 点击 `New repository`。
3. Repository name 填写：`你的GitHub用户名.github.io`
   - 例如用户名是 `mingshuangli`，仓库名就是 `mingshuangli.github.io`。
4. Description 可填写：
   `Academic website of Mingshuang Li, Ph.D., CCC-A, focused on speech enhancement, FFR/cABR, clinical audiology, and Au.D. education.`
5. 选择 `Public`。
6. 点击 `Create repository`。

## 4. 上传网站文件

1. 进入新建的 repository。
2. 点击 `Add file` → `Upload files`。
3. 上传解压文件夹里面的全部内容：
   - `index.html`
   - `assets` 文件夹
   - `files` 文件夹
   - `README.md`
4. 注意：必须让 `index.html` 位于 repository 最外层，不能再套一层文件夹。
5. 点击 `Commit changes`。

## 5. 开启 GitHub Pages

1. 在 repository 顶部点击 `Settings`。
2. 左侧点击 `Pages`。
3. 在 `Build and deployment` 中：
   - Source：`Deploy from a branch`
   - Branch：`main`
   - Folder：`/(root)`
4. 点击 `Save`。
5. 等待几分钟。
6. 页面会显示网站网址：`https://你的GitHub用户名.github.io/`

## 6. 后续更新

### 更新文字

1. 在 GitHub 打开 `index.html`。
2. 点击右上角铅笔图标。
3. 修改文字。
4. 点击 `Commit changes`。

### 更新照片

1. 准备新照片。
2. 文件名保持为 `mingshuang-li-headshot.jpg`。
3. 上传到 `assets` 文件夹并覆盖旧文件。

### 更新 CV

1. 导出最新 CV PDF。
2. 文件名保持为 `Mingshuang_Li_CV.pdf`。
3. 上传到 `files` 文件夹并覆盖旧文件。

## 7. 建议以后补充

- Google Scholar 链接
- ORCID 链接
- LinkedIn 链接
- ResearchGate 链接
- 每篇论文的 DOI
- 实验室成员和学生成果
- Speech enhancement 与 FFR/cABR 项目的新闻更新

不要上传学生隐私、未公开数据、审稿材料、密码或没有权利公开的论文 PDF。
