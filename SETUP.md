# 发布检查清单

## 1. 创建主页仓库

在 GitHub 创建一个名为 `MRLEILOVE` 的公开仓库。仓库名称必须与 GitHub 用户名完全一致，主页 README 才会显示在个人主页。

不要在 GitHub 页面初始化 README、`.gitignore` 或 License，避免首次推送产生无关冲突。

## 2. 推送本地仓库

```powershell
git remote add origin https://github.com/MRLEILOVE/MRLEILOVE.git
git push -u origin main
```

## 3. 启用自动更新

进入仓库的 `Settings -> Actions -> General -> Workflow permissions`，确认允许 `Read and write permissions`。

然后在 `Actions` 页面手动运行一次：

1. `Update latest blog posts`
2. `Generate contribution snake`

贡献动画第一次生成后，会创建 `output` 分支。README 中的贡献轨迹随后即可显示。

## 4. 调整主页置顶项目

建议按下面顺序置顶：

1. `database-column-comments`
2. `ai-git-commit`
3. `spring-boot-shiro`
4. `yearning-tampermonkey-toolkit`
5. `quartz-lite-starter`
6. 后续公开的 `database-tools-plus` 或 `google-authenticator`

## 5. 发布前人工确认

- 检查 Banner 在桌面和手机宽度下是否清晰。
- 检查所有精选项目仍为公开仓库。
- 检查 CSDN RSS 工作流能否获取文章。
- 如果不希望公开位置，可从 README 删除“中国深圳”。
- 如果不希望使用第三方统计服务，可删除“GitHub 数据”区域。

