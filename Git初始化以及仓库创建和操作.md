*一、基本信息设置*

1、设置用户名
  git config --global user.name 'Yuguohugo'     //注意是user.name
  
2、设置用户名邮箱
  git config --global user.name 'XXXXXXX@icloud.com'
        
        以上设置反映在github仓库主页上显示谁提交了该文件

*二、初始化一个新的git仓库*
 1、创建文件夹
    mkdir test
 2、在文件夹内初始化git（创建git仓库）
    cd test
    git init
    注意：这里要设置显示隐藏文件
    
*三、向仓库添加文件*
   1、创建文件
   touch secondDemo.md    //创建一个md文件
   2、添加到暂存区
   git add secondDemo.md 
   3、提交到仓库
   git commit -m 'add secondDemo.md'
   
   
*四、修改仓库文件*
    1、修改文件
    2、添加到暂存区
    git add secondDemo.md
    3、提交到仓库
    git commit -m 'add secondDemo.md'

*五、删除仓库文件*
    1、删除文件
    rm -rf secondDemo.md
    2、删除同步到暂存区
    git rm secondDemo.md
    3、提交到仓库
    git commit -m 'add secondDemo.md'

    






    
