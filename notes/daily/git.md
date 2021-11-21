# git clone

![image-20210908222736346](C:\Users\user\AppData\Roaming\Typora\typora-user-images\image-20210908222736346.png)



# git 

1. git push
2. git commit -m "message"
3. git add.

 gitpush使用https://www.cnblogs.com/du-hong/p/9921214.html

git配置sshhttps://blog.csdn.net/u013778905/article/details/83501204



# git出错记录

+ 初始化 讲文件夹设为可以操作的本地仓库

  ![image-20211107135332561](C:\Users\user\AppData\Roaming\Typora\typora-user-images\image-20211107135332561.png)

+ 切换到main

+ add .

+ commit

+ ![image-20211107135613873](C:\Users\user\AppData\Roaming\Typora\typora-user-images\image-20211107135613873.png)

+ git remote 关联github仓库

+ ![image-20211107135705549](C:\Users\user\AppData\Roaming\Typora\typora-user-images\image-20211107135705549.png)

+ 第一次尝试git push

+ ![image-20211107135731890](C:\Users\user\AppData\Roaming\Typora\typora-user-images\image-20211107135731890.png)

+ 查原因为本地与远程产生冲突，尝试将仓库clone下再进行上传

  ![image-20211107140307253](C:\Users\user\AppData\Roaming\Typora\typora-user-images\image-20211107140307253.png)

+ 解决：先把远程的变化拉取下来，再一并提交

  ![image-20211107140457317](C:\Users\user\AppData\Roaming\Typora\typora-user-images\image-20211107140457317.png)
  
+ 结果

  ![image-20211107140524023](C:\Users\user\AppData\Roaming\Typora\typora-user-images\image-20211107140524023.png)

  ![image-20211107140542655](C:\Users\user\AppData\Roaming\Typora\typora-user-images\image-20211107140542655.png)

  

  参考文档[提交代码报错 error: failed to push some refs to - 云+社区 - 腾讯云 (tencent.com)](https://cloud.tencent.com/developer/article/1773434)
  
+ 测试修改提交

  ![image-20211107141950469](git.assets/image-20211107141950469.png)

+ 仓库内md文件提交成功，图片文件夹未成功

  ![image-20211107142027709](git.assets/image-20211107142027709.png)

+ 加入了picgo上传图片方式来存储




用deveco push的时候报SSL那个错，cmd执行`git config --global http.sslVerify "false"`

但每次都弄真的很麻烦
