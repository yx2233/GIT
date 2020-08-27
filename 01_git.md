1.安装git
2.新建文件夹->右键git bash here->git init 初始化仓库
3.linux简单操作命令
      clear：清屏
      echo "wenjian"：打印内容
      echo "wenjian" >test.txt ：打印"wenjian"到新建的文件夹test.txt下
      ll：查看所有的子文件及目录
      find  ./ ：展示子孙文件及目录
      find ./  -type f：只展示文件，不展示目录
      rm text2.txt ：删除文件
      cat text.txt : 查看文件内容
      vim test.txt ->i(进入插入模式,可修改内容) ->Esc(退出插入模式)->:wq(保存并退出)
      
总结：
    清屏：clear
    打印内容：echo "wenjian"
    增(创建文件)：>text.txt
    删(删除文件)：rm text2.txt
    改(更改文件)：
           更改文件名(重命名文件)：mv text.txt text3.txt  将text改为text3
           更改文件内容：vim test.txt ->i(进入插入模式,可修改内容) ->Esc(退出插入模式)->:wq(保存并退出)  q!(强制退出)
           显示行号：vim test.txt ->i(进入插入模式,可修改内容) ->Esc(退出插入模式)->:set nu(显示行号)
    查：
          查找所有子文件或目录： ll
          查找所有子孙文件或目录：find ./
          只查找文件，不查目录：find ./ -type f
          查看文件内容：cat test.txt
   
问题：
  1.再怎么删除子文件里边的孙文件
  2.怎么切换目录










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
3.从GitHub上拉取项目到本地
	git pull 	本地没有修改的前提下



