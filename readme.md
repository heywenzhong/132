# 测试remote远端 的远程仓库名称是否默认是origin

- 测试结果为NO， origin作为远程仓库名只是因为连接远程仓库link时，我们起名为origin；
	- 我们通常输入的是 git remote add origin url_link...
	- 本git仓库， 我输入为 git remote remote_repo https://github.com/heywenzhong/132.git
- 则之后的第一次push改为：  git push -u remote_repo master
	- 主分支默认确实为 master。 
