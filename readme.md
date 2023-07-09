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
