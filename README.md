1. Git设置

1）安装git
https://git-scm.com/

2）生成rsa公钥，在git-bash中输入
ssh-keygen -t rsa

3）将 ~/.ssh/id_rsa.pub文件发给管理员，添加git用户

4）管理员添加用户之后
git clone ssh://git@192.168.21.199:22/Users/git/xiaoshuazhi.git
