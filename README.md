# getgit
## 复制粘贴

```
ctrl + lns	复制
shift + ins   粘贴
```



## 下载源码的方式    


```
git clone git@github.com:代码仓库
```



```
git clone git@github.com:a/b.git
```

以此类推



## 常用命令

```
git init      //初始化
git add 		//提交 可添加多个，空格隔开   1.js 2.js ; .把当前改变的都提交
git status      //检查
git commit -m "添加了新的文件"    //上传
git diff		//当前改变的文件内容
git log 		//提交日志
git reset ==hard           //回滚版本，配合log使用
git reflog 			//  更详细的更新日志
git reset HEAD demo.js	//把 文件  从缓存区挪出来
git checkout -- demo.js   //取消之后输入的内容 能取消add


git remote add origin ssh 		//连接github
git pull origin master			//下载文件
git push origin master			//提交到GitHub
```



## 提交顺序

```
git add .
git commit -m "修改了哪里"
git status
//已经提交到本地
git push origin master
```



## SSH的设置

```
ssh-keygen -t rsa -C "个人邮箱地址"



```















