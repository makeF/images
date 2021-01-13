## jsdelivr加速访问  
https://cdn.jsdelivr.net/gh/makeF/images/  
## 清除历史提交
``` shell
git checkout --orphan latest_branch
git add -A
git commit -am "commit message"
git branch -D master
git branch -m master
git push -f origin master
```
