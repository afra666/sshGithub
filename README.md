# sshGithub

  ##  创建目录
   $ mkdir test  
   $ cd test   

 ##  初始化
   $ git init  

 ##  创建hello.md文件
   $ echo "This is a ssh key test" > README.md  

 ##  提交到本地
   $ git add .   #提交当前目录下所以文件  
   $ git commit -m "add README.md"   #提交记录说明   

 ##  提交到github
   $ git remote add origin ‘<SSH url>’  #引号内<SSH url>粘贴刚刚复制的仓库ssh路径   
   $ git push -u origin master  

 ##  ssh key若设置密码，则会提示输出密码
   Enter passphrase for key '~/.ssh/id_rsa':    
