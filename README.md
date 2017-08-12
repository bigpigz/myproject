# myproject
这是一个git项目

### git 基本指令
+git init 初始化git仓储  
 ```
 git init
 ```
+git 全局配置用户名和邮箱
```
git config --global user.name "username"  
git config --global user.email "useremail"
```
+git 添加文件到git存储
```
git add ./filename.html  //添加指定文件到临时存储
git add ./    //提交目录下所有文件到临时存储
git commit -m "提交说明"   //将临时存储中的文件上传到git存储中
git commit --all -m "提交说明"   //将目录文件夹下所有文件一次性提交
git status  //查看文件当前状态
```
+配置.gitignore文件，忽略配置文件路径中的文件，可以自行配置忽略不必要上传的文件
```
/.idea
/.gitignore
/node_modules
```
+查看git 日志
```
git log //查看存储日志
git log --oneline  //存储日志以单行形式显示
```
+git 版本操作
```
git reset --hard Head~0 //返回到最近配置，数字0是索引号
git reset --hard [版本号] //版本号可以通过  git log --oneline获取
git reflog //输出版本切换记录
git branch [分支名] //创建一个分支
git branch  //查看分支
git checkout [分支名]  //切换到指定分支
git merge [分支名]   //合并指定分支
git branch -d [分支名]   //删除指定分支
```
+在github上操作
```
 git push https://github.com master  //将本地目录文件上传到github服务器的master目录下
 git pull https://github.com   //从github服务器上下载文件
 git clone https://github.com  //从github服务器上下载文件，与pull区别是多次操作会覆盖本地目录文件
```
