# 教大家如何在vbox虚拟机上安装deepin 

## 虚拟机设置部分

![](https://gitee.com/xiongshijie/xiongshijie2/raw/master/img/20210121220039.png)

首先这应该是我们打开vbox看的的界面 大致相似

![](https://gitee.com/xiongshijie/xiongshijie2/raw/master/img/20210121220333.png)

然后，我们点击新建 在名称里输入你给虚拟机的命名 这里 我们就叫deepin就行

输入名称后 我们点击下一步 

![](https://gitee.com/xiongshijie/xiongshijie2/raw/master/img/20210121220523.png)

这个地方要我们选择大小 我们选择4096mb就行 这个根据你自己的电脑内存条大小选择

比如你的内存条是16gb 那么我们建议你选择8gb左右就可以 或者是更小 

当然如果你是大佬 随便你选 注意！！！ 这里1GB=1024MB 

![](https://gitee.com/xiongshijie/xiongshijie2/raw/master/img/20210121220824.png)

点击创建

![](https://gitee.com/xiongshijie/xiongshijie2/raw/master/img/20210121220856.png)

下一步 动态分配，

 下一步

![](https://gitee.com/xiongshijie/xiongshijie2/raw/master/img/20210121220936.png)

选择硬盘的大小 这个地方我们选择64gb 因为刚好够全盘安装 也可以手动安装

注意 这里deepin限制的全屏安装大小为64gb 手动安装最小是15gb  

然后点击创建

![](https://gitee.com/xiongshijie/xiongshijie2/raw/master/img/20210121221132.png)

现在我们可以看见刚刚创建的虚拟机了 不过这还没有结束 我们选中它，点击设置 

![](https://gitee.com/xiongshijie/xiongshijie2/raw/master/img/20210121221339.png)

注意我打箭头的这些东西 ，以此点击 然后选择我们的ISO镜像 选择好之后点击确定

然后再打开设置 

![](https://gitee.com/xiongshijie/xiongshijie2/raw/master/img/20210121221545.png)

把显存大小拉满

然后点击启动 

![](https://gitee.com/xiongshijie/xiongshijie2/raw/master/img/20210121221639.png)

选择镜像 点击启动 

## 系统设置部分

![](https://gitee.com/xiongshijie/xiongshijie2/raw/master/img/20210121221741.png)

勾选 点击下一步

![](https://gitee.com/xiongshijie/xiongshijie2/raw/master/img/20210121221814.png)

这个地方有两种安装方式 建议小白直接点击全盘安装 然后下一步

或者是手动安装

![](https://gitee.com/xiongshijie/xiongshijie2/raw/master/img/20210121221913.png)

我们点击它之后右边有个小加号 我们点击它

![](https://gitee.com/xiongshijie/xiongshijie2/raw/master/img/20210121221953.png) 

先设置efi分区 点击新建

![](https://gitee.com/xiongshijie/xiongshijie2/raw/master/img/20210121222048.png)

然后下面的一个分区再次点击右边的加号 如图选择，点击新建



![](https://gitee.com/xiongshijie/xiongshijie2/raw/master/img/20210121222128.png)

最后应该是这样 点击下一步 确定 然后继续安装

![](https://gitee.com/xiongshijie/xiongshijie2/raw/master/img/20210121222219.png)

就会开始安装 不过我们的工作还没有结束 等待他跑进度就行

![](https://gitee.com/xiongshijie/xiongshijie2/raw/master/img/20210121222453.png)

然后出现这一幕 注意 注意 注意！ 直接关掉虚拟机

![](https://gitee.com/xiongshijie/xiongshijie2/raw/master/img/20210121222536.png)

强制退出

![](https://gitee.com/xiongshijie/xiongshijie2/raw/master/img/20210121222615.png)

然后再打开虚拟机设置 将硬盘调整为第一位

再次启动虚拟机

![](https://gitee.com/xiongshijie/xiongshijie2/raw/master/img/20210121222700.png)





就进入系统了 然后一路点击下一步

![](https://gitee.com/xiongshijie/xiongshijie2/raw/master/img/20210121222740.png)

来到这个地方 设置用户名 密码 注意！！ 一定不要忘记 不然很麻烦

用户名必须是字母开头，而且11首字母必须小写！

![](https://gitee.com/xiongshijie/xiongshijie2/raw/master/img/20210121222950.png)

输入你刚刚设置的密码  就可以进入系统了 如果你是虚拟机 就选普通模式就好了

![](https://gitee.com/xiongshijie/xiongshijie2/raw/master/img/20210121223057.png)

## root用户密码设置

然后右键 打开终端 

![](https://gitee.com/xiongshijie/xiongshijie2/raw/master/img/20210121223153.png)

然后输入

```
sudo passwd root 
```

再输入你之前设置的密码

注意 Linux输入密码都不是明文显示的

直接输入 然后回车就行

![](https://gitee.com/xiongshijie/xiongshijie2/raw/master/img/20210121223327.png)

注意这个地方输入的两边是root账户的密码 一定不要和你之前设置的账户一样

不然很危险！！！

基础安装到此结束    As熊世杰









