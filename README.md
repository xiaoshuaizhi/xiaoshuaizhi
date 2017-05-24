## Git环境设置

1. 安装git
<pre>
https://git-scm.com/
</pre>

2. 生成rsa公钥，在git-bash中输入
<pre>
ssh-keygen -t rsa
</pre>

3. 将 `~/.ssh/id_rsa.pub` 文件发给管理员，添加git用户

4. 管理员添加用户之后
<pre>
git clone ssh://git@192.168.21.199:22/Users/git/xiaoshuazhi.git
</pre>
