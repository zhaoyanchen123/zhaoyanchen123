#git learn 命令
Get started by creating a new file or uploading an existing file. We recommend every repository include a README, LICENSE, and .gitignore.

git init  # 初始化本地仓库
git add . # 添加所有改动到暂缓区
git commit -m "message"  #提交所有
git remote add origin git@github.com:CQUPTLei/VSCode.git
git push -u origin master

or create a new repository on the command line
echo "# git_init" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:zhaoyanchen123/git_init.git
git push -u origin main


push an existing repository from the command line
git remote add origin git@github.com:zhaoyanchen123/git_init.git
git branch -M main
git push -u origin main


