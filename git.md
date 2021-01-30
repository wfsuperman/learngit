# git

<!--生成ssh公钥-->

```git bash
$ ssh-keygen -t rsa -C "79058609@qq.com"
```

<!--ssh连接github-->

```git bash
$ ssh -T git@github.com
```

<!--设置giuhub用户名密码-->

```
$ git config --global user.wfsup erman

$ git config --global user.email "79058609@qq.com"
```

<!--进入本地库目录，初始化-->

```
$ cd /d/learngit

$ git init
```

<!--将本地库与远程库关联，远程库代码下载到本地库-->

```
$ git remote add origin git@github.com:wfsuperman/learngit.git

$ git pull git@github.com:wfsuperman/learngit.git
```

<!--提交-->

```
$ git add .

$ git commit -m "second commit"

$ git push origin master
```

<!--远程库的文件将本地库文件还原-->

```
$ git status

$ git checkout wf.txt
```



