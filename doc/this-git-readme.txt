以下操作以windows操作系统Git Bash为例：
    
    1  ls                #查看内容
    2  cd ~/.ssh         #查看是否已经有ssh key。如果有进行备份处理（略）
    3  ls
    4  ls
    5
    6  ssh-keygen.exe  -t rsa -C "youremailaddress" #生成ssh key
    7  cd /e/workspace/portlet                          #进入工作目录
    8  
    9  pwd                                              #查看当前路径
   10  
   11  git config --global user.name "username"       #配置git用户名  
   12
   13  git config --global user.email useremailaddress  #配置git邮件  
   14  
   15  git init                             #初使化工作目录
   16  
   17  touch  test.txt                      #生成一个文件
   18  
   19  git add *                            #添加新内容或修改的内容到索引。此处可以指定某个文件
   20  git commit -m 'first commit'         # 提交索引内容到版本库。
   21  git remote add origin git@github.com:username/GoldChamberlain.git     #将本地版本分支添加到远程版本库
   22  git push origin master                                               #将本地分支提交到远程版本库，如果有冲突可以查看相关帮助进行合并。
   



http web访问：
http://github.com/surpass/GoldChamberlain
