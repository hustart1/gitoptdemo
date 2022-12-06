# gitoptdemo
### git回退版本

```
git log # 查看历史版本
git reflog # 看看线上历史版本日志

git reset --hard HEAD^ # 回退到当前版本的上个版本
git reset --hard HEAD^^ ## 回退到上两个版本
git reset --hard HEAD~10 # 回退到前10个版本
git reset --hard versionid # 回退到提交id版本
git push origin main --force # 强制推送到目标分支（覆盖）
```
