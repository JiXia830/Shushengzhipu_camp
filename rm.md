# Shushengzhipu_camp 学习笔记
写在前面：这是日记本，参与书生实战营的知识点记录  
## 基础语法  
### 实践：在github上创建自己的仓库  
1.安装git-->官网下载即可（仅限windows用户），linux user 后续自行百度  
完事后打开终端（win+r—>cmd）输入指令检查 git --version检查一下   
2.学习一波git基础操作，自行百度  
3.cd到要操作的目录，后续会提交这个目录下的文件，git clone 一个你要操作的远程仓库，git clone + 仓库链接
4.git init --> git branch -a 看看本地分支和远程分支  
5.操作开始，可以在远程仓库已有分支进行操作（也就是说远程分支和你操作的这个分支是同名的）  
git checkout -b camp3 origin/camp3  
如果不是同名  
git checkout -b camp3  
6.创作时间.....  
7.提交更改到分支  
git add .  
git commit -m "自己写" 提交信息记录  
8.git push origin camp3  
9.完事之后github可以手动合并
