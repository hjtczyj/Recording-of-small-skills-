# 如何使用git命令行来操作Github上的项目


<br/>**常规步骤**</br>
1.在Git官网https://git-scm.com/downloads下载并安装Git。

2.在Github自己的主页中添加Repository。

3.在添加的Repository的“settings”里将“Github Pages”由None改为master branch。这样此Repo就有了自己的网址。

4.在本地计算机想要的存放Repo的目录右键，选择“git bash here”，就会打开git的命令行窗口。

5.在命令行窗口输入命令：
    git clone xxxxxx 
<br/>就能将Github主页内的某个Repo克隆到当前所选文件夹中。（其中“xxxxxx”是第3步得到的Repo网址）



<br/>**常用git命令**：</br>  
git clone  //本地如果无远程代码，先做这步，不然就忽略

cd //定位到你blog的目录下

git status //查看本地自己修改了多少文件

git add . //添加远程不存在的git文件

git commit  -m “what I want told to someone” //提交修改

git push  //更新到远程服务器上

git rm //移除文件

<br/>参考：</br> 
1.https://blog.csdn.net/web_hwg/article/details/72188612
2.https://blog.csdn.net/tuesdayma/article/details/72615868
3.https://www.cnblogs.com/eyunhua/p/8463200.html
