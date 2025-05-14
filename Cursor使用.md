
Cursor能通过添加API的日志快速定位出问题的代码并自动改正，你甚至不需要读懂（当然能读懂错误更好，这有助于不犯同样的错误），只要把相关的完整代码发给Cursor





cd your-local-project-folder

git init

git remote set-url origin git@github.com:taobb123/DailyThinking.git
git remote add origin https://github.com/你的用户名/你的仓库名.git

git add .

git commit -m "initial commit"

git push -u origin master  # 或者 main，具体看默认分支名



# 生成SSH密钥（如果还没有）
ssh-keygen -t rsa -b 4096 -C "your_email@example.com"

# 将SSH密钥添加到GitHub账户（需要复制公钥内容到GitHub设置中）
# 公钥通常位于 ~/.ssh/id_rsa.pub

# 更改远程URL为SSH格式
git remote set-url origin git@github.com:taobb123/DailyThinking.git

# 测试SSH连接
ssh -T git@github.com



git push -u origin main

# 检查当前分支
git branch

# 如果你当前是在 master 分支，切换到 main
git checkout main

# 更新远程分支设置
git pull origin main

# 如果本地 main 没有任何改动，推送到远程
git push origin main



