
1.libvlc来源于libvlc3.2.12版本，将androidX替换为androidSupport
2.so文件来自AS编译3.2.12版本生成的APK中lib
3.vlc-lib-android-3.2.12.aar不包含so,vlc-lib-android-armv7a-3.2.12.aar包含so
4.vlc-android仓库：https://github.com/videolan/vlc-android.git
5.vlc使用参考博客：https://blog.csdn.net/u010735007/article/details/108141213
**6.需要将libc++_shared.so/libvlc.so/libvlcjni.so/ push到 /system/lib，注意系统原本有一个libc++_shared.so**
