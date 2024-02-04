# win7下如何生成 github ssh公钥 GIT



1.安装git,可以去官网下最新的，但由于局域网问题，我们百度git即可，一般版本也比较新；

2.一路默认下一步，安装成功后，从程序目录打开"Git Bash”;

3.输入命令：ssh-keygen-t rsa-C"1234567890@qq.com"，回车（"1234567890@qq.com"是github账号）；

4.提醒输入key的名称，输入如id_rsa等，我们可以敲入三个回车，默认配置；

5.在C:\Users\Administrator\.ssh下产生两个文件 ： id_rsa和id_rsa.pub ;

6.用编辑器打开id_rsa.pub文件，复制内容，在github.com的网站上到ssh密钥管理页面，添加新公钥即可。