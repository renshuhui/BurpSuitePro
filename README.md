# BurpSuitePro
下载
    Burp Suite Pro 2022.11.4 下载  https://portswigger.net/burp/releases/professional-community-2022-11-4
    BurpSuiteCN 汉化包（点开链接之后点击releases ,然后下载Assets 下面的burpsuitloader.jar）https://github.com/Leon406/BurpSuiteCN-Release
    BurpLoaderKeygen 注册机
安装
    下载Burp Suite Pro 2022.11.4，按照常规步骤安装
    注：建议更换路径安装
    下载BurpLoaderKeygen 注册机，将其放入到 Burp Suite Jar 包的同级目录下。

激活
   1. 打开命令行窗口，先带着注册机运行一下 BurpSuite （注意先使用cd /d 命令将目录切换到BurpSuite的安装目录之下）
      D:\tool\BurpSuitePro\jre\bin\java.exe --add-opens=java.base/java.lang=ALL-UNNAMED --add-opens=java.base/jdk.internal.org.objectweb.asm=ALL-UNNAMED --add-opens=java.base/jdk.internal.org.objectweb.asm.tree=ALL-UNNAMED --add-opens=java.base/jdk.internal.org.objectweb.asm.Opcodes=ALL-UNNAMED -javaagent:BurpLoaderKeygen.jar -jar D:\tool\BurpSuitePro\burpsuite_pro.jar
   2. 运行后，会弹出一个窗口，提示Enter License Key，不管，放一边
   3. 新开命令行窗口，运行：
      D:\tool\BurpSuitePro\jre\bin\java.exe -jar D:\tool\BurpSuitePro\BurpLoaderKeygen.jar
   4.将左侧窗口中的License中的内容复制粘贴到激活页面的Enter License key中，点击Next
   5.点击Manual activation进行手动激活
   6.点击Copy Request将其复制粘贴到左侧窗口的Activation Request中后，自动生成Activation Response
   7.将左侧窗口的Activation Response的值复制粘贴到激活页面的第三个输入框内，点击Next
   8.激活成功
汉化 以及优雅的使用
   --add-opens=java.desktop/javax.swing=ALL-UNNAMED
   --add-opens=java.base/java.lang=ALL-UNNAMED
   --add-opens=java.base/jdk.internal.org.objectweb.asm=ALL-UNNAMED
   --add-opens=java.base/jdk.internal.org.objectweb.asm.tree=ALL-UNNAMED
   --add-opens=java.base/jdk.internal.org.objectweb.asm.Opcodes=ALL-UNNAMED
   -javaagent:burpsuitloader-3.7.17-all.jar=loader,han
   -javaagent:BurpLoaderKeygen.jar
   -Xmx2048m
