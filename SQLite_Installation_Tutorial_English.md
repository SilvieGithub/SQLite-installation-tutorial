## SQLite Installation Tutorial

SQLite is an in-process library that implements a self-contained, serverless, zero-configuration, transactional SQL database engine. 

### Installation Steps

1. #### Visit [SQLite home page](<http://www3.sqlite.org/index.html>)

2. #### Click "download" in the home menu bar to enter the [download page](<http://www3.sqlite.org/download.html>)

3. #### Download the compressed files: **sqlite-tools-win32-\*.zip** 和 **sqlite-dll-win32-\*.zip**

   Tip: Please download SQLite DLL file according to whether the operating system is 64 bit or 32-bit.

4. #### Create a new folder and extract the files to it.

5. #### Configure environment variable

   - Enter **computer properties setting** page
   - Click **advanced system settings**
   - Click **environment variable**
   - Select **Path** in the system variable and click Edit
   - Add the folder path containing SQLite files to **Path**

6. #### Verify whether SQLite is installed successfully

   Enter sqlite in CMD to see whether the version information appears. If it appears, the installation is successful.