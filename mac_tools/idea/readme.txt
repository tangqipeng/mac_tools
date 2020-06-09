https://www.jianshu.com/p/1998ae318ceb

或者：
1， 双击安装包安装IDEA。
2. 先打开idea
3，将网盘下载的jar包放入bin目录下。
4. 点击IDEA菜单："Help" -> "Edit Custom VM Options ...", 在打开的vmoptions编辑窗口末行添加,最后一行加入-javaagent:/Applications/IntelliJ IDEA 2.app/Contents/bin/jetbrains-agent.jar（就是javaagent: + 我们刚才放入的jar包的路径，依据自己的电脑路径而定），然后点击Save保存。

5. 最后再在Configure里面打开Manage License，选择License Server，输入http://jetbrains-license-server网址，选择Activate进行激活。
注意：http://jetbrains-license-server目前失效，改为http://fls.jetbrains-agent.com
