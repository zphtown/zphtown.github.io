# git-demo

说明：这是我的git测试项目

记录自己是如何使用git上传项目至github

# 准备工作

1.首先你需要一个github账号，所有还没有的话先去注册吧！github官网(https://github.com/)


2.我们使用git需要先安装git工具，这里给出下载地址，下载后一路直接安装即可： git官网(https://git-scm.com/)


3.在github new repoository（新建一个项目）

4.1  在github添加SSH keys

4.1.1 首先在本地打开git命令，类似cmd

4.1.2 执行ssh-keygen -t rsa -C "zphtown@163.com"

4.1.3 找到C:\Users\Administrator\.ssh\id_rsa.pub，这个内容则是所需的key，title随便写


# 开始上传

备注：将本地仓库关联到远程仓库:git remote add origin git@github.com/zphtown/git-demo.git

1.git clone 项目git地址（在github项目中找）

2.git add .

3.git commit  -m  "提交信息"  

4.git push -u origin master （直接git push也可以）

至此，已经上传成功，下次编码时先更新代码：git pull

