git 学习使用创建新的git库名字为re01.
初始化git库
git add . 暂存所有文件
git commit -m "提交说明"
git branch v1.0 //创建分支
git checkout v1.0 //切换分支
git branch -M main  //创建分支main
git remote add origin https://www.com.git 设置自己的仓库网址相当于设置一个网盘地址用于push
代码
git push -u origin //将文件上传到设置的仓库网址的地方

假如现在分支在v2.0下面我添加了merge 语法
git merge main //就是将main中修改添加到v2.0中
同样的如果现在我在分支main下面使用git merge v2.0就是把当前在v2.0下面修改的内容复制到main下面
这个时候在main下面使用
git add .
git commit 可以将修改的内容添加到本地仓库中暂时存起来

之后可以使用git push -u origin 将本地库的main中的修改上传到仓库
