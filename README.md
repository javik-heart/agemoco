# 可管理的衰老

从连续穿戴监测到 iPSC 细胞与类器官计算平台，如何把个人衰老从命运改写成可测量、可解释、可有限度改写的轨迹。

这是一本用 [mdBook](https://rust-lang.github.io/mdBook/) 编写的开放电子书。论证提纲见 [`guide.md`](guide.md)，正文在 `src/`。

## 在线阅读

发布地址：<https://javik-heart.github.io/agemoco/>

（仓库需在 GitHub 的 **Settings → Pages → Source** 选择 **GitHub Actions**。推送到 `main` 后由工作流构建并部署。）

## 本地构建

需要 [mdBook](https://github.com/rust-lang/mdBook) 0.5.x：

```bash
curl -sSL https://github.com/rust-lang/mdBook/releases/download/v0.5.4/mdbook-v0.5.4-x86_64-unknown-linux-gnu.tar.gz | tar -xz
./mdbook serve --open
```

或：

```bash
mdbook build
```

生成的静态站点在 `book/`。

## 结构

全书按提纲六块展开：曲线的定义，两把不能混用的尺子，穿戴层，细胞与类器官层，闭环与成功标准，以及边界中的命题。
