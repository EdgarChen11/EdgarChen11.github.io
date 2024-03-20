# 常用 Git 指令筆記

## 常用指令
* `git init`

   建立新的本地端儲存庫(Repository)。這個命令會在當前目錄中創建一個新的 .git 子目錄，用於存儲 Git 版本控制所需的相關文件和數據。會在當前目錄（你所在的目錄）中創建一個名為 .git 的子目錄，這個子目錄包含了 Git 版本控制所需的相關文件和數據。這個 .git 目錄是 Git 儲存庫的核心，所有的版本控制信息都會存儲在這個目錄中。

* `git clone [Repository URL]`

   複製遠端的儲存庫(Repository) 檔案到本地端，如果以github SSH 協議來說：git clone git@github.com:github名稱/儲存庫名稱.git

* `git status`

   檢查本地端檔案狀態，例如：未進入版本控管（Untracked）、新增檔案（New File）、刪除檔案（Deleted）、檔案已修改（Modified）。

* `git add [檔案或資料夾]`

   將指定的檔案（或資料夾）加入版本控制。可用 `git add .` 加入全部版本控制。

* `git commit`

   用於將已暫存（staged）的更改提交到本地Repository。

* `git commit -m "提交說明內容"`

   用於將已暫存（staged）的更改提交本地儲存庫(Repository)，並透過 `-m` 參數設定摘要說明文字。

* `git push`

   將本地儲存庫(Repository)的 commit 推送到遠端儲存庫(例如 GitHub 上的遠端儲存庫)。