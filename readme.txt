this is used to practice the linux and the git
add distribution
this time is to prove using vim is equivlent to vi




实际上,可以把git分成两大部分
第一部分是
工作区
工作区本质是本地的空间
就是在非.get的目录下建立一个目录，而这个目录用来存放本地的文件
在修改或创建文件之后可以通过将文件git add或者git reset指令上传到本地的git版本库
在存到版本库之前，首先还要经过暂存区







第二部分
git的版本库
本质上就是,git所在的目录
然后通过git commit 在git上更改到最新的版本文件
同时储存过去的版本文件
如果要远程上传的话需要使用git push origin master指令

总结以下输入的指令

thomas@thomas-Inspiron-7560:~/learngit$ git add readme.txt将本地的文件放到缓冲区
thomas@thomas-Inspiron-7560:~/learngit$ git commit -m "first version"
将缓冲区的文件放到git的版本库上
thomas@thomas-Inspiron-7560:~/learngit$ git status 查看是否缓冲区还有未上传的文件
thomas@thomas-Inspiron-7560:~/learngit$ git push origin master 上传到连接的github 上
