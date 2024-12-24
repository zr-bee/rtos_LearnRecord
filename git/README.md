# Git

---

## Git的使用流程

* ==安装== 直接就是点击安装文件 exe文件，然后按照默认next即可

* ==Github连接== 

  * 首先需要在github上创建新的仓库
  * 本地创建目录，右击git bash，配置自己的用户名，账号
  * 生成密钥：`ssh-keygen -t rsa`   一路回车 生成相应的公钥私钥
    * 需要注意的是：这里需要保证电脑用户名是英文，要不然会无法生成，可能是中文无法编解码
    * 电脑用户账户修改用户名：中文--》英文 可以参考：[Windows中文用户名改为英文用户名的办法](https://blog.csdn.net/qqrescom/article/details/139563246?sharetype=blog&shareId=139563246&sharerefer=APP&sharesource=weixin_45671864)

  * 在github中进行配置相应的公钥
  * 验证：`git remote //--git查看远程仓库信息 `   参考：[Git连接github仓库](https://www.cnblogs.com/hdlan/p/14395681.html)

* 我在处理过程中，按照上述流程还是未能够进行连接push相应的文件至远程端，出现的问题是：
* ![image-20241224171305571](C:\Users\chenhao\AppData\Roaming\Typora\typora-user-images\image-20241224171305571.png)

* 解决办法：

  ![image-20241224171358456](C:\Users\chenhao\AppData\Roaming\Typora\typora-user-images\image-20241224171358456.png)

![image-20241224171417995](C:\Users\chenhao\AppData\Roaming\Typora\typora-user-images\image-20241224171417995.png)





