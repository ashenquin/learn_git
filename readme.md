git init Git repository初始化
cd .git 打开.git文件夹
cd ../ 退出
git add readme.txt 将文件放入栈存
git commit -m "wrote a readme file"确认存入
git diff 查看修改内容
git status 查看当前状态
git reset --hard HEAD^使版本回退^数量的版本 hard 指针
git log 查看仓库日志(j上k下q退出) --pretty=oneline修饰，一行显示