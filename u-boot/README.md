## u-boot file

***  
 1. 安装设备树编译工具
 rpm -ivh dtc-1.4.6-1.el7.x86_64.rpm
 
 2. 生成专属的配置文件
  #make orangepi_one_defconfig
 
 3. 编译uboot   
  #make ARCH=arm CROSS_COMPILE=/home/liuwei/arm-linux/bin/arm-linux-gnueabihf-