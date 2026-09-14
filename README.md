# 可管理的衰老

从连续穿戴监测到个人细胞与类器官计算，如何把衰老从命运改写成可测量、可解释、可有限度改写的轨迹。

这是一本用 [mdBook](https://rust-lang.github.io/mdBook/) 编写的开放电子书。正文在 `src/`。许可见 [`LICENSE`](LICENSE)（CC BY-NC-SA 4.0）。

## 在线阅读

<https://javik-heart.github.io/agemoco/>

仓库需在 **Settings → Pages → Source** 选择 **GitHub Actions**。推送到 `main` 后由工作流构建。

## 本地构建

```bash
curl -sSL https://github.com/rust-lang/mdBook/releases/download/v0.5.4/mdbook-v0.5.4-x86_64-unknown-linux-gnu.tar.gz | tar -xz
./mdbook serve --open
```

生成的静态站点在 `book/`。

## 结构

六部正文之外，导读含总图与测量学；第五部后有一章可检验的假想闭环病例。论证提纲 `guide.md` 只给作者和审稿人核对，不作为读者入口。
