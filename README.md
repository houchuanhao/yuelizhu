# yuelizhu
ylz经常把写了一半的文档弄丢，希望github可以帮到她
1.我要保存一下,可按顺序执行下面的命令
git add . 
git commit -m"这次我修改了。。。完成了。。。"  
git push origin master   

2.我想看一看我修改了什么
git diff 文件名          注意，这里的文件名必须带上扩展名

3.我把把文档改乱了，我昨天写的才是正确的,我想回到以前的版本，注意，回到以前的版本后现在的版本就没有了，所以记得备份一下
git log --pretty=oneline          这个命令是查看所有的历史版本
git reset --hard 版本号          这个历史版本的版本号可以通过上面那一条命令获取

当然，还有更简单的方式
git reset --hard HEAD^           回到上个版本  注意HEAD后面有一个^
git reset --hard HEAD^^          回到上两个版本 注意HEAD后面有俩个^


如果，你的这个文件夹都弄丢了。。。那么 还是可以找回来，但是找到的是你最后一次执行git pull origin master的状态-----








更多教程可参考  
http://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000/001374385852170d9c7adf13c30429b9660d0eb689dd43a000























































































创建远程版本库 ssh-keygen -t rsa -C"houchuanhao@imudges.com"


