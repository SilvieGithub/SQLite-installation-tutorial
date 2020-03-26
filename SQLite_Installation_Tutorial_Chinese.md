# SQLite安装教程

SQLite是一个进程内库，它实现了一个自包含、无服务器、零配置、事务性的SQL数据库引擎。本教程介绍了在Windows操作系统中安装SQLite的步骤。

### 安装步骤

1. #### 访问[SQLite主页](<http://www3.sqlite.org/index.html>)

2. #### 点击主页菜单栏中的download进入[下载页面](<http://www3.sqlite.org/download.html>)

3. #### 下载 **sqlite-tools-win32-\*.zip** 和 **sqlite-dll-win32-\*.zip** 压缩文件

   提示：sqlite-dll文件请根据根据操作系统是64位还是32位的对应下载。

4. #### 新建文件夹，解压文件至该文件夹中。

5. #### 配置Path环境变量

   - 进入设置电脑属性页面
   - 点击高级系统设置

   - 点击环境变量
   - 系统变量中选择path后点击编辑
   - 将包含SQLite文件的文件夹路径添加其中

6. #### 验证是否安装成功

   在cmd中输入sqlite验证是否出现版本信息，若出现，则表明安装成功。

   