#一、第三方库版本
####1.xadmin 下载地址 https://pypi.org/project/xadmin2/#modal-close
####2.django版本 2.0  ```pip install django==2.0```
#二、创建项目
####1.创建好django项目，创建好之后，在项目主目录下新建extra_app文件夹
####2.xadmin版本 xadmin2 下载xadmin2，放到创建好的extra_app,添加路径
```import sys``` <br>
```sys.path.insert(0,os.path.join(BASE_DIR,'extra_apps'))```
####3.```pip install requirement.txt```