# qt5-runtime
Qt5.12 Runtime
* 1、没有将Qt5.12.0全部库打包，否则镜像太大
* 2、支持中文显示
* 3、以ubuntu 16.04作为基础镜像包

若此镜像中Qt5.12.0库有缺失，导致应用无法运行的，可以自行在```package/opt/Qt5.12.0```中自行添加对应库文件；
如若需要其他版本Qt，也可依照此项目中Dockerfile文件修改，并将```package/opt/Qt5.12.0```替换为实际使用的安装库文件即可。