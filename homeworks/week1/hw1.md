## 交作業流程

1. 到 GitHub Classroom 建立自己的 repository (repo)
2. 使用 `git clone <URL>` 複製 repo 到自己的本機
3. 用 `git branch` 新增 branch （e.g. branch_week1），`git checkout` 切換到另一個 branch（或是 `git checkout -b <new_branch>` 直接新增並切換）
4. 寫作業在已經建立好的的檔案
5. 用 `git status` 檢查檔案更動的情形、`git diff` 檢視變動前後差異
6. 確認檔案（作業）無誤後，`git add` -> `git commit -m` 或 `git commit -am` 提交到 branch 上 （e.g. branch_week1），其中：
   -a：`git add`，檔案加入提交
   -m：提交附上的說明文字
7. `git push origin week1` 把作業推（上傳）到 <week1> 這個分支
8. 到 GitHub repo 發 PR（open pull request），取得連結，回到學習系統送出。等助教改作業。

