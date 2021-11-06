### 1.代码克隆
- 当你本地没有代码的时候，你需要直接从远程clone到当前文件夹一份： 克隆的时候选择克隆dev分支 
git clone -b dev git@github.com:Hitcs509/AgriculturalBrainProject.git
- 当你本地有了代码，但远程代码发生了更新，你需要用pull去获得： 
git pull origin dev

### 2.代码开发
进入你的代码开发目录进行开发

### 3.代码提交
开发完成后使用 git add 待提交文件 将文件提交的暂存区 例如 git add README.md 将代码更新的主要功能/改动写上注释，双引号内为注释内容，中英文都可以。 
git commit -m "first commit" 
git remote add origin https://github.com/Hitcs509/AgriculturalBrainProject.git 
提交分支也是选择dev分支提交 git push -u origin dev
