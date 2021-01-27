UWB无人机集群
==============
UWB介绍
-----------------------------

|          UWB测距是使用双向飞行时间法(TW-TOF，two way-time of flight )，TOF测距方法属于双向测
|       距技术，它主要利用信号在两个异步收发机(Transceiver)之间往返的飞行时间来测量节点间的距离。节点间的距离能得到，那么我们就可以进行定位了，UWB定位技术的原理和GPS卫星导航定位原理是类似的，都是通过无人机上面的标签与四个基站之间进行测距，再通过算法就可以把无人机的位置数据计算出来。

UWB无人机集群介绍
-----------------------------

|         UWB定位技术可在满足基站搭建的环境下提供稳定以及有效的定位，因此可在一些非GPS的区
|       域进行无人机飞行，室内室外兼备，再加上基站模块具有轻巧，方便携带的特点，使得基站摆放，飞行区域的搭建非常的方便，只需要几分钟就可以搭建好，就非常适用于无人机飞行的区域经常变更，而且会在无GPS的区域下飞行的情况。而结合无人机集群飞行，使得UWB无人机集群方案成为室内无人机集群飞行的一个低成本方案，而且由于可变更区域，使得UWB无人机集群更加灵活。


货物验收
-----------------------------

|          客户拿到全部的货物之后，应按照硬件清单一一检查各硬件模块的数量以及是否存在损坏异常
|      等。

集群飞行功能
-----------------------------

**操作步骤：**   

|          1.	按要求摆放基站并将标定基站位置数据；

    .. image:: ../../images/formation/14.png
        :height: 850px
        :width: 2000px
        :scale: 30 %
        :alt: None
        :align: center

|          2.	按要求摆放无人机；

    .. image:: ../../images/formation/15.png
        :height: 850px
        :width: 2000px
        :scale: 30 %
        :alt: None
        :align: center

|          3.	先进行单机定点飞行，确认无人机单机能够正常解锁并能够定点飞行；

|          4.   将1号无人机上电启动，在地面端电脑上通过NoMachine连接1号无人机的电脑，并启动位于1号机电脑桌面的formation_uwb.sh文件，确保各节点启动正常；

|          5.	在集群状态节点的终端窗口查看每架无人机的状态，确保没有异常；

            .. image:: ../../images/formation/16.png
                :height: 1280px
                :width: 1920px
                :scale: 30 %
                :alt: None
                :align: center 

|          6. 在模式切换节点的终端窗口根据提示输入数字0选择解锁起飞，无人机集群便飞行至目标位置；

            .. image:: ../../images/formation/17.png
                :height: 1280px
                :width: 1920px
                :scale: 30 %
                :alt: None
                :align: center 

|          7.	在位置控制节点的终端窗口输入正确的控制指令；

            .. image:: ../../images/formation/18.png
                :height: 1280px
                :width: 1920px
                :scale: 30 %
                :alt: None
                :align: center 

|          8.在集群控制节点的终端窗口输入1开始控制无人机集群；

            .. image:: ../../images/formation/19.png
                :height: 1280px
                :width: 1920px
                :scale: 30 %
                :alt: None
                :align: center 

|          9.可切换为一字队形或三角队形；

            .. image:: ../../images/formation/20.png
                :height: 1280px
                :width: 1920px
                :scale: 30 %
                :alt: None
                :align: center 

|          10. 用户可根据个人使用情况按照提示正确输入队形控制，模式控制，位置控制相关指令