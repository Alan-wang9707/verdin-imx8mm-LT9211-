# Mallow Carrier Board开发板+lt9211c转接板点亮KD101HWX53EP
# 第一步
· 使用Toradex Easy Installer下载镜像到开发板\
· 我们的驱动使用6.8.1下游版本镜像\
<img width="1007" height="297" alt="image" src="https://github.com/user-attachments/assets/fb56c30b-8af1-42bb-a316-ff98dde79851" />\
# 第二步
· 交叉编译器中下载对应源码，并配置环境，详情见：https://developer.toradex.com/linux-bsp/6/os-development/build-u-boot-and-linux-kernel-from-source-code/build-linux-kernel-from-source-code#downstream \
· 下载完整源码，然后通过1cbf48124747这个哈希值进行检索，跳转到对应的分支
# 第三步
· 使用git clone我们的驱动与设备树，放置到对应的源码位置当中
· 然后根据toradex官方的教程进行进行编译，生成.KO以及.dtbo文件
# 第四步
· 把生成的生成.KO以及.dtbo文件放入对应位置
