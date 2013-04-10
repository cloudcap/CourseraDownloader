## Usage
usage : ./downloader.py download_dir username password class_name

**download-dir**: 你要把文件下载到哪个文件夹里，可使用绝对路径或相对路径

**class-name**: 你要下载的课程URL名称，如 https://class.coursera.org/neuralnets-2012-001/lecture/index 这门课，class_name就是neuralnets-2012-001

![revolunet logo](https://raw.github.com/royguo/CourseraDownloader/master/demo.png "revolunet logo")

## Download

需要注意，必须要先在coursera上enroll课程才可以下载

下载逻辑在downloader.py的main函数中，可以根据需要修改

下载过程使用curl，在linux正常运行，没测试windows。

## Issue
不知道为何，下载过程总是会时不时的僵死，重启即可，文件已经存在的话不会重新下载，此问题正在解决中，看起来像是国内的网络问题导致。
