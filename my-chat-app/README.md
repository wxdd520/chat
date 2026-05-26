# 🔐 密聊 · 密码配对聊天

两人输入相同密码即可私密聊天。纯浏览器端 P2P 直连，不需要任何服务器。

## 在线地址

```
https://你的用户名.github.io/仓库名/
```

## 使用说明

1. 两人打开同一个网址
2. 各自输入昵称 + 约定好的房间密码
3. 自动配对，开始聊天

---

## 部署到 GitHub Pages（三步）

### 第一步：创建 GitHub 仓库

1. 打开 https://github.com/new
2. **Repository name** 随便填，比如 `my-chat`
3. 选 **Public**（公开，免费）
4. 点 **Create repository**

### 第二步：上传文件

把本文件夹里的 `index.html` 上传到仓库：

**方式 A — 网页上传（最简单）**
1. 在刚创建的仓库页面，点 **Add file → Upload files**
2. 把 `index.html` 拖进去
3. 点 **Commit changes**

**方式 B — GitHub Desktop**
1. 打开 GitHub Desktop → File → Clone repository
2. 选中刚创建的仓库，选个本地路径
3. 把 `index.html` 复制到那个文件夹里
4. GitHub Desktop 里点 **Commit to main** → **Push origin**

### 第三步：开启 Pages

1. 进仓库 **Settings** → 左侧 **Pages**
2. **Branch** 选 `main` → 文件夹选 `/ (root)` → **Save**
3. 等 1-2 分钟，刷新页面，顶部会出现：
   ```
   Your site is live at https://你的用户名.github.io/my-chat/
   ```

### 完成 🎉

把上面那个网址 + 你们约定的密码告诉对方，就可以开始聊天了。

---

## 注意事项

- 需要网络加载 PeerJS 库
- 支持 Chrome / Firefox / Edge / Safari
- 密码就是房间号，不同密码的人互相看不见
- 聊天内容端到端加密，不经过任何服务器
