# git常用命令
1.	git init :让该目录变成git可管理目录
2.	git add -A ：把当前目录下的全部文件添加到git仓库中
3.	git add README.md　：把README.md单个文件添加到git仓库中
4.	git commit -m "XXX" :提交更新log
5.	git status :查看提交状态
6.	git remote add origin 地址 :和远程仓库关联提交
7.	git push　：已关联远程仓库，直接提交
8.	git log :查看提交log
9.	git reset -hard HEAD^/HEAD^^/HEAD~100 : 回退版本1/2/100个
10.	连引用一起下载
git clone --recursive https://github.com/openssl/openssl.git

设置当前用户信息:
  git config --global user.name "antizy0"   
  git config --global user.email antizy0@gmail.com
