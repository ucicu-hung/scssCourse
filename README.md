git init       //若已經初始化過就可以不用輸入
git add .
git commit -m "first commit"
git remote add origin [GitHub Repositories Url]
git branch -M main
git push -u origin main      // 僅限第一次輸入，往後只需要輸入 git push


之後更新後續版本，只需打
git add .
git commit -m ""
git push
