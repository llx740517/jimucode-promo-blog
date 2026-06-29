# 发布到 GitHub / Gitee

本仓库已经整理好 V001 到 V058 的推广图文博客素材。根目录 `README.md` 适合在代码托管平台直接浏览，`index.html` 适合作为静态博客首页发布。

## 本地预览

```bash
cd "/Users/longlingxi/Desktop/Z视频/jimucode-promo-blog"
python3 -m http.server 8098 --bind 127.0.0.1
```

浏览器打开：

```text
http://127.0.0.1:8098/
```

## 继续推送

当前本地仓库已经提交到 `main` 分支，远端如下：

```text
gitee  https://gitee.com/zaixianjianmo/jimucode-promo-blog.git
github https://github.com/llx740517/jimucode-promo-blog.git
```

配置好账号凭据后执行：

```bash
cd "/Users/longlingxi/Desktop/Z视频/jimucode-promo-blog"
git push -u gitee main
git push -u github main
```

如果 HTTPS 要求用户名和密码，密码位置通常填写平台生成的私人令牌，而不是账号登录密码。不要把令牌写进仓库文件或聊天记录。

## 网页预览

GitHub / Gitee 的仓库页面会直接渲染 `README.md`，可以先用仓库首页作为文章目录。

如果要做成真正的网页博客：

- GitHub：进入仓库 `Settings` -> `Pages`，选择从 `main` 分支的根目录发布。
- Gitee：进入仓库的 Pages / Gitee Pages 服务，选择 `main` 分支根目录发布。

发布后，访问根页面即可看到 `index.html` 的博客卡片列表。

## 本次仓库内容

- `posts/V001-.../` 到 `posts/V058-.../`
- 每篇包含 `README.md`
- 每篇保留 `图文发布稿.md`
- 每篇保留 `图文发布稿-直接复制.md`
- 每篇保留 `cover-flow-images/`
- 每篇保留 `ppt-images/`
- 不包含原始视频、音频、剪辑工程、v8 安全版包
