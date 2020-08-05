#把本地项目变成版本仓库，然后推送到GitHub仓库
1.把本地目录变成git可管理的仓库
	进入项目目录->右键git bash here->git init初始化
2.将本地目录的所有文件都添加到暂存区里
	git add -A 
3.将暂存区的文件提交到仓库
	git commit -m "第一次提交"
4.将本地仓库与GitHub仓库关联
	git remote add origin https://github.com/yx2233/gshop_client.git 
5.将本地仓库的内容推送到GitHub仓库
	git push -u origin master


1.之后的将本地修改的内容推送到GitHub仓库
	git add -A -> git commit -m "" -> git push origin master
2.从GitHub上克隆项目
	git clone https://github.com/yx2233/gshop_client.git



