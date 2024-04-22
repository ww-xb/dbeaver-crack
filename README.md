# DBeaver Enterprise/DBeaver Ultimate 激活工具

## 使用方法
1. 复制`${DBEAVER_ECLIPSE_HOME}/plugins/com.dbeaver.lm.api_x.x.x.jar`和`${DBEAVER_ECLIPSE_HOME}/plugins/org.jkiss.utils_x.x.x.jar`两个文件到项目的libs目录中, 同时修改`pom.xml`中的依赖为实际包名
2. 修改`DBeaverLicenseCrack.java`文件中的`DBEAVER_ECLIPSE_HOME`变量为自己DBeaver的实际安装目录
3. 运行main方法，控制台中的最后会输出一段激活码，复制到Dbeaver中即可
4. 程序会在`$HOME/.jkiss-lm`目录中保存密钥文件，激活后可以保留也可以删除，不影响激活

## 参考文档
https://www.52pojie.cn/thread-1668629-1-1.html

## 警告
1. 程序会对DBeaver本身的内容作出修改，具体修改内容请阅读上方文档
2. 本代码仅供学习之用，禁止用于商业用途，否则后果自负