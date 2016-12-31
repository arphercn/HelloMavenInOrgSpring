### java命令行运行  
参考   
[Java基础-环境变量设置及Java命令行使用](https://my.oschina.net/xianggao/blog/88492)  
[Java-第四课命令行执行Java文件](http://www.cnblogs.com/lleid/archive/2013/03/21/java.html)  
设置CLASSPATH时,前面加.;表示编译javac时首先寻找本文件下的包packeage  
.;后面的值两个参考文件给出的不一样,有待考证
  
注意javac时如果包含package需要在包目录外执行,如  
`javac hello\HelloWorld.java`  
执行  
`java hello.HelloWorld`
## Maven学习笔记
参考<https://spring.io/guides/gs/maven/>  

根目录 D:\_java\_maven\HelloMavenSpring  
pom.xml位置: 根目录  
mvn命令运行位置: 根目录  
mvn compile 生成target文件夹包含编译后的文件
mvn package 生成jar包  
mvn install jar包安装到本地repository    
 &nbsp; pom.xml复制为~\\.m2\repository\org\springframework\gs-maven\0.1.0\gs-maven-0.1.0.pom   

引用文件后命令行运行暂无果,后续待研究 

   



  