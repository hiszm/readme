
---

https://hiszm.lanzoui.com/iiCM8qmolud
密码:hiszm


备份：https://github.com/hiszm/readme/tree/main/resource


---

# 下载破解最新的 IDEA 2020.3.2 版本安装包
**第一步: 下载最新的 IDEA 2020.3.2 版本安装包**
我们先从 IDEA 官网下载 IDEA 2020.3.2 版本的安装包，下载链接如下：

**https://www.jetbrains.com/idea/download/**
IDEA 2020.3.2版本官网下载

点击下载，静心等待其下载完毕即可。

**第二步: 先卸载老版本的 IDEA**


注意，如果电脑上之前有安装老版本的 IDEA, 需要先卸载干净，否则可能安装失败！

注意，一定要先卸载干净掉老版本的 IDEA。

**1.笔者之前安装了老版本的 IDEA, 所以要先卸载，未安装老版本 IDEA 的小伙伴直接跳过，看后面步骤就行**:

卸载老版本的IDEA

卸载成功后，点击关闭:

IDEA老版本卸载成功

卸载成功后，双击刚刚下载好的 idea exe 格式安装包, 打开它；

**第三步: 开始安装 IDEA 2020.3.2 版本**
**2.安装目录默认为 C:\Program Files\JetBrains\IntelliJ IDEA 2020.3.2, 这里笔者选择的是默认路径:**

IDEA 2020.3.2安装第一步

**3.勾选自己想要创建的桌面快捷方式，笔者的操作系统是 64 位的，所以勾选的 64 位快捷方式**：

IDEA 2020.3.2安装第二步

**4.点击 Install ：**
IDEA 2020.3.2安装第三步

**5.安装完成后，勾选 Run IntelliJ IDEA，点击 Finish 运行软件:**
IDEA 2020.3.2安装第四步

**第四步： 开始激活**
**6.等待 IDEA 2020.3.2 运行, 中间会先弹出一个注册框，我们勾选 Evaluate for free, 点击 Evaluate， 先试用30天:**
试用IDEA 30天

注意，如果没有弹出上面的界面，可执行重置30天试用期脚本，脚本网盘地址下面可获取

IDEA 2020.3.2重置30天试用期补丁

打开该文件夹后，有对应系统的执行脚本，执行即可：
windows系统：reset_jetbrains_eval_windows.vbs
linux/mac系统：reset_jetbrains_eval_mac_linux.sh


**7.进入 IDEA 中， 先随便建个 Java 工程， 然后将网盘中最新的 IDEA 破解补丁 BetterIntelliJ.zip拖入 IDEA 界面中，如下图所示：**
将破解激活补丁拖入IDEA 2020.3.2界面中


**注意： **

**zip 补丁包无需解压 ~ 无需解压 ~ 无需解压 ~ **

激活后补丁不要移动，不要删除~

补丁安装成功后，需要输入激活补丁key.txt里面的激活码，两个步骤缺一不可，否则会激活失败~


PS: 很多小伙伴(刚接触编程)不知道怎么新建一个 Java 项目，可以参考下面这篇教程，图文讲解的哦：

《IDEA 如何新建 Java 项目 (图文讲解, 良心教程) 》


PS: 破解补丁页面提取人数过多，导致分享的百度网盘链接容易被封： IDEA 2020.3.2破解补丁分享失败蛋疼ing，为限制人数，目前暂不提供页面直接提取，改为从笔者公众号提取。


需要的小伙伴，请关注微信公众号: Java学习者社区, 或者扫描下方公众号二维码，回复关键字：idea, 即可免费无套路获取激活码、破解补丁，持续更新中~。



4.1 另外一种安装补丁的方式

如果拖动的方式不成功，还可以通过磁盘安装插件，点击菜单 File -> Settings -> Install Plugin From Disk，图文步骤如下：

IDEA 2020.3.2通过磁盘安装插件

注意：安装成功后一定要重启 IDEA !!!

注意：安装成功后一定要重启 IDEA !!!

注意：安装成功后一定要重启 IDEA !!!

**第五步: 必须重启 ，必须重启 ，重点 ！！ 否则不起作用 ！**
特别重要：插件安装完成后，必须要重启IDEA（检查进程，是否真得关闭了IDEA？），才能生效!!!

有同学说报key is invaild,是由于没有重启IDEA，就直接输入激活补丁key.txt里面的激活码，肯定不行的 ！！


PS: 如果重启一次还是提示 key is invaild, 请再重启一次试试 ！本人就是第一次没效果，再重启一次，再输入 激活补丁key.txt里面的激活码就ok了。

**第六步: 检查插件是否安装成功（建议）**

插件安装完成后，建议检查一下是否安装成功，点击菜单：Help -> Edit Custom VM Options...

打开 IDEA 2020.3.2 的配置文件

打开 .vmoptions 配置文件，如果插件安装成功，会在文件中添加以 -javaagent 为前缀的配置，如下图所示:
## 以windows为例，正确配置如下：

**-javaagent:C:\Users\Public\.BetterIntelliJ\BetterIntelliJ-版本号.jar**
## 以unix为例，正确配置如下：

-javaagent:${HOME}//.BetterIntelliJ/BetterIntelliJ-版本号.jar


编辑 IDEA 2020.3.2 的配置文件

注意：如果你之前配置了其他的 -javaagent 路径，请一定要先删除掉 ！！！ 否则会激活不成功 ！！！

注意：如果你之前配置了其他的 -javaagent 路径，请一定要先删除掉 ！！！ 否则会激活不成功 ！！！

注意：如果你之前配置了其他的 -javaagent 路径，请一定要先删除掉 ！！！ 否则会激活不成功 ！！！

第七步：输入 激活补丁key.txt里面的激活码

重启成功后，点击菜单 Help -> Register -> Add New License ， 如下图所示:

打开输入IDEA 2020.3.2激活码界面

复制网盘中的 激活补丁key.txt文件中的激活码，拷贝到输入框中，然后点击 Activate 按钮激活：

在IDEA 2020.3.2中输入激活码

到这里， IDEA 就已经激活成功了 ~

第八步: 验证 IDEA 是否激活成功

你说激活成功就激活成功了？我咋不信呢？

别急，接下来我们就来验证一下 IDEA 是否已经激活成功了，步骤如下：

1.进入 IDEA 界面后，点击 Help -> Register 查看：



2.可以看到，已经成功激活至 2099 年辣，撸到老，哈哈~


注意： 若官网更新了 IDEA 新版本, 后面再次打开 IDEA 时，会在右下角弹框提示你更新升级.

尽量不要升级 !!! 因为可能导致 IDEA 需要重新激活，且可能发生新版本激活不成功的情况 ！！！

尽量不要升级 !!! 因为可能导致 IDEA 需要重新激活，且可能发生新版本激活不成功的情况 ！！！

若嫌弹框烦的话，可以在设置里面手动关闭更新提示，具体步骤参考下面文章👇👇👇:

《IntelliJ IDEA 如何关闭更新提示？》

IDEA 2020.3.2 成功激活到2099年了
https://www.exception.site/essay/how-to-free-use-idea-202021-by-resigter-code#%E7%AC%AC%E5%85%AD%E6%AD%A5-%E6%A3%80%E6%9F%A5%E6%8F%92%E4%BB%B6%E6%98%AF%E5%90%A6%E5%AE%89%E8%A3%85%E6%88%90%E5%8A%9F%EF%BC%88%E5%BB%BA%E8%AE%AE%EF%BC%89
