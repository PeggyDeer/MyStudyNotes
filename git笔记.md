# 一 git的安装

## 1.下载Git软件：

​   傻瓜式安装，一直下一步;
   安装成功后 ，在桌面鼠标右键你会看见两个东西    
   Git GUI Here :可视化软件操作
   Git Bash Here : 命令行操作

## 2.安装乌龟的Git  ，下一步遇到那个哪个;

​    |-- 选中OpenSSH;   
    |-- username: 瞎写
    |-- email: 瞎写

## 3.汉化包安装了:

## 4.安装成功后 桌面鼠标右键 ，放到乌龟图标上，选中

   settings;  选中 中国 ，中国文简体
    

# 二git的使用

## 1注册github账号.

用谷歌浏览器打开百度 ，搜索GitHub  ，并注册账号; 过程有点慢 需要网络好

![1597878629574](C:\Users\DELL\AppData\Local\Temp\1597878629574.png)

##6需要在本地创建一个repository文件夹作为本地仓库;

随便找个盘符: 在盘符下创建repository文件夹 
 必须在文件夹中 ， 鼠标右键 点击 Git bash here
Git的命令： git  init 回车

![1597837057699](C:\Users\DELL\AppData\Local\Temp\1597837057699.png)

## 7使用Git 时，将数据存储到 暂存区f

1.在repository文件夹中  创建一个 hello.txt
   里面写点啥都行;
    执行 git add 文件名 --->这时就是将 文件存储到暂存区中了
  ***这时 你的文件会出现 蓝色的 +  ，就是在暂存区中;

如果不变蓝按Win+R键打开运行对话框，输入 regedit.exe ，准备修改注册表；  找到 HKEY_LOCAL_MACHINE\Software\Microsoft\Windows\CurrentVersion\Explorer；  新建一个键名称为 “Max Cached Icons” 数据设置为 “2000”；  重启一下电脑，图标就可以显示了。  

![1597837845885](C:\Users\DELL\AppData\Local\Temp\1597837845885.png)

## 8输入git commit -m "文件名.txt 提交了" 出现下面的界面就代表把暂存文件放到本地仓库了 

![1597839306898](C:\Users\DELL\AppData\Local\Temp\1597839306898.png)

9去Github上创建远程仓库;



![1597846306115](C:\Users\DELL\AppData\Local\Temp\1597846306115.png)

![1597846524362](C:\Users\DELL\AppData\Local\Temp\1597846524362.png)

![1597846981189](C:\Users\DELL\AppData\Local\Temp\1597846981189.png)











![1597847243062](C:\Users\DELL\AppData\Local\Temp\1597847243062.png)

3.回到Git窗口 ，创建SSH 密钥
     ssh-keygen -t rsa -C "tangleipyl@163.com"  一直 回车

会出现下图

![1597840707120](C:\Users\DELL\AppData\Local\Temp\1597840707120.png) 

 这时去 你的C:\Users\Administrator\.ssh

 id.rsa.pub 文件打开;



 添加成功后 ，GitHub上会有个钥匙

 切回仓库页面  
 git remote add origin git@github.com:PeggyDeer/Peggy1.git

 git remote add origin git@github.com:PeggyDeer/Two.git 回车执行

 git push -u origin master ，执行完毕后 ，浏览器刷新
  就会看见 GitHub上的文件;

***
  1.文件在暂存区 
  2.本地仓库  
       提交到 master 本地仓库标识 
  3.中央仓库  

  以上操作 如果命令行不好使, 就用小乌龟软件提交

----------------------------------------
绿色对号 和蓝色加号的显示
  进入到注册标后 ，让你创建，选择 项目，左边会出现
文件夹，起名字Max ....... ,界面的右侧有一个默认键 双击代开
  2000 ， 关机重启

git命令一定要进入文件夹操作