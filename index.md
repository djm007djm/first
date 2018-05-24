！！！
1.让本地仓库转git仓库， 如果已经有git后缀的 就已经是git仓库 
git init 

2.本地增删查改


3.把文件添加到缓存区
git add [xxx文件名字]  添加一个
或
git add .   添加全部



4.查看文件的状态
git status
	
清楚缓存区指定文件
git rm --cached [xxx文件]

5.提交文字描述，描述本次操作的内容

git commit -m "内容"


6.建立本地跟远程端的连接 （ssh和https）

git remote add origin [远程服务器的链接]

7.把缓存区的代码上传到服务器

git push origin master 





更新修改  

同步更新服务器的上的文档
git pull origin master


本地内容更新到服务器上






下载

git clone [远程服务器端的地址]
例如git clone https://github.com/djm007djm/first.git


