# 使用VirtualBox安装OpenEuler操作系统
## 1.在OpenEuler官网下载VirtualBox
在 VirtualBox 官网点击 Windows hosts,下载安装应用程序
![](https://www.openeuler.org/assets/e02.C9OPn4uC.png)
## 2.创建虚拟机
打开 VirtualBox ,点击“新建”按钮，输入虚拟机名称（如openEuler），选择类型 Linux，版本选择 Other Linux(64-bit)，随后选择合适的安装路径
![](https://www.openeuler.org/assets/e05.rX4_Uium.png)

给虚拟机分配适当的内存，建议不低于2GB，根据主机性能可适当增加
![](https://www.openeuler.org/assets/4G.Cp5iCjwq.png)

选择现在创建虚拟硬盘，虚拟硬盘文件类型，并选择默认的VDI（VirtualBox 磁盘映像）

![](https://www.openeuler.org/assets/hard.CJJWnPdQ.png)
![](https://www.openeuler.org/assets/e07.XGx7EL45.png)

选择“动态分配”或“固定大小”，大小至少为20GB，但考虑到实际应用中的内存占用问题，选择“动态分配”，空闲时可自动缩减占用的硬盘空间
![](https://www.openeuler.org/assets/e08.B0-xpaJy.png)

这里我们自定义文件的存储位置后，将硬盘大小设为64GB
![](https://www.openeuler.org/assets/64G.-gTrCFxo.png)
## 3.安装OpenEuler
点击“启动”按钮，进入虚拟机启动界面，在启动菜单中，选择相应的文件并启动
![](https://www.openeuler.org/assets/e14.C9nTxkZn.png)

选择 【Install openEuler 20.03-LTS】回车，进行安装
![](https://www.openeuler.org/assets/e15.DOFsWxNf.png)

选择安装语言，这里我们选择英文
![](https://www.openeuler.org/assets/e16.DLAkTr3l.png)

自定义安装的磁盘（建议选择D盘，以防C盘空间不够用）
![](https://www.openeuler.org/assets/e18.CORYxIcA.png)

分别设置用户名和root用户的密码
![](https://www.openeuler.org/assets/e20.DQHcULKW.png)

安装完成后，选择 Reboot 重启虚拟机
![](https://www.openeuler.org/assets/e22.BVGP3ZG6.png)

关闭虚拟机，选择【设置】选中 openEuler-20.03-LTS-x86_64-dvd.iso，鼠标右键，删除盘片，保存退出
输入用户（root）密码（安装阶段设置的密码），进入 openEuler 虚拟机
![](https://www.openeuler.org/assets/e26.BVicgI2O.png)