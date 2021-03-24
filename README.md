# unable_to_merge_raster_demo
An demo project which contains two engine and webview and makes engine crash

```
F/libc    (11108): Fatal signal 6 (SIGABRT), code -6 (SI_TKILL) in tid 11142 (1.raster), pid 11108 (rge_raster_demo)
*** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
Build fingerprint: 'Xiaomi/umi/umi:11/RKQ1.200826.002/21.3.3:user/release-keys'
Revision: '0'
ABI: 'arm64'
Timestamp: 2021-03-24 11:52:19+0800
pid: 11108, tid: 11142, name: 1.raster  >>> com.example.unable_to_merge_raster_demo <<<
uid: 10224
signal 6 (SIGABRT), code -6 (SI_TKILL), fault addr --------
Abort message: '[FATAL:flutter/fml/raster_thread_merger.cc(48)] Check failed: success. Unable to merge the raster and platform threads.
'
    x0  0000000000000000  x1  0000000000002b86  x2  0000000000000006  x3  0000007c684fd150
    x4  0000007d6556a000  x5  0000007d6556a000  x6  0000007d6556a000  x7  0000000000881134
    x8  00000000000000f0  x9  a665056cd60a1e18  x10 0000000000000000  x11 ffffffc0fffffbdf
    x12 0000000000000001  x13 0000000000000079  x14 00239127bcc14346  x15 00003b351054f454
    x16 0000007d632d4948  x17 0000007d632b3390  x18 0000007c67a08000  x19 0000000000002b64
    x20 0000000000002b86  x21 00000000ffffffff  x22 0000000000000000  x23 b400007ccdaee900
    x24 0000000000000000  x25 0000007c684fe000  x26 0000000000000000  x27 0000000000000001
    x28 0000000000000051  x29 0000007c684fd1d0
    lr  0000007d63266aa0  sp  0000007c684fd130  pc  0000007d63266acc  pst 0000000000001000
backtrace:
      #00 pc 0000000000089acc  /apex/com.android.runtime/lib64/bionic/libc.so (abort+164) (BuildId: a790cdbd8e44ea8a90802da343cb82ce)
      #01 pc 0000000001310784  /data/app/~~W2sUpMihWXQXs-Yx0cuHWg==/com.example.unable_to_merge_raster_demo-IUwY4BX5gBqjR0Pxu09Pfw==/lib/arm64/libflutter.so (BuildId: 854273bae6db1c10c29f7189cb0cf640ad4db110)
      #02 pc 000000000133426c  /data/app/~~W2sUpMihWXQXs-Yx0cuHWg==/com.example.unable_to_merge_raster_demo-IUwY4BX5gBqjR0Pxu09Pfw==/lib/arm64/libflutter.so (BuildId: 854273bae6db1c10c29f7189cb0cf640ad4db110)
      #03 pc 0000000001337170  /data/app/~~W2sUpMihWXQXs-Yx0cuHWg==/com.example.unable_to_merge_raster_demo-IUwY4BX5gBqjR0Pxu09Pfw==/lib/arm64/libflutter.so (BuildId: 854273bae6db1c10c29f7189cb0cf640ad4db110)
      #04 pc 000000000137a420  /data/app/~~W2sUpMihWXQXs-Yx0cuHWg==/com.example.unable_to_merge_raster_demo-IUwY4BX5gBqjR0Pxu09Pfw==/lib/arm64/libflutter.so (BuildId: 854273bae6db1c10c29f7189cb0cf640ad4db110)
      #05 pc 0000000001328df8  /data/app/~~W2sUpMihWXQXs-Yx0cuHWg==/com.example.unable_to_merge_raster_demo-IUwY4BX5gBqjR0Pxu09Pfw==/lib/arm64/libflutter.so (BuildId: 854273bae6db1c10c29f7189cb0cf640ad4db110)
      #06 pc 000000000136b0ec  /data/app/~~W2sUpMihWXQXs-Yx0cuHWg==/com.example.unable_to_merge_raster_demo-IUwY4BX5gBqjR0Pxu09Pfw==/lib/arm64/libflutter.so (BuildId: 854273bae6db1c10c29f7189cb0cf640ad4db110)
      #07 pc 000000000136ba84  /data/app/~~W2sUpMihWXQXs-Yx0cuHWg==/com.example.unable_to_merge_raster_demo-IUwY4BX5gBqjR0Pxu09Pfw==/lib/arm64/libflutter.so (BuildId: 854273bae6db1c10c29f7189cb0cf640ad4db110)
      #08 pc 000000000136c414  /data/app/~~W2sUpMihWXQXs-Yx0cuHWg==/com.example.unable_to_merge_raster_demo-IUwY4BX5gBqjR0Pxu09Pfw==/lib/arm64/libflutter.so (BuildId: 854273bae6db1c10c29f7189cb0cf640ad4db110)
      #09 pc 000000000136b4ec  /data/app/~~W2sUpMihWXQXs-Yx0cuHWg==/com.example.unable_to_merge_raster_demo-IUwY4BX5gBqjR0Pxu09Pfw==/lib/arm64/libflutter.so (BuildId: 854273bae6db1c10c29f7189cb0cf640ad4db110)
      #10 pc 000000000136b2c4  /data/app/~~W2sUpMihWXQXs-Yx0cuHWg==/com.example.unable_to_merge_raster_demo-IUwY4BX5gBqjR0Pxu09Pfw==/lib/arm64/libflutter.so (BuildId: 854273bae6db1c10c29f7189cb0cf640ad4db110)
      #11 pc 0000000001376188  /data/app/~~W2sUpMihWXQXs-Yx0cuHWg==/com.example.unable_to_merge_raster_demo-IUwY4BX5gBqjR0Pxu09Pfw==/lib/arm64/libflutter.so (BuildId: 854273bae6db1c10c29f7189cb0cf640ad4db110)
      #12 pc 0000000001334d38  /data/app/~~W2sUpMihWXQXs-Yx0cuHWg==/com.example.unable_to_merge_raster_demo-IUwY4BX5gBqjR0Pxu09Pfw==/lib/arm64/libflutter.so (BuildId: 854273bae6db1c10c29f7189cb0cf640ad4db110)
      #13 pc 0000000001339eac  /data/app/~~W2sUpMihWXQXs-Yx0cuHWg==/com.example.unable_to_merge_raster_demo-IUwY4BX5gBqjR0Pxu09Pfw==/lib/arm64/libflutter.so (BuildId: 854273bae6db1c10c29f7189cb0cf640ad4db110)
      #14 pc 0000000000019da8  /system/lib64/libutils.so (android::Looper::pollInner(int)+916) (BuildId: 4e69b93bf70ed592f0029dbd1097529e)
      #15 pc 00000000000199ac  /system/lib64/libutils.so (android::Looper::pollOnce(int, int*, int*, void**)+112) (BuildId: 4e69b93bf70ed592f0029dbd1097529e)
      #16 pc 0000000000012c74  /system/lib64/libandroid.so (ALooper_pollOnce+100) (BuildId: e230c033dab215214d04e22e013a16b5)
      #17 pc 0000000001339e34  /data/app/~~W2sUpMihWXQXs-Yx0cuHWg==/com.example.unable_to_merge_raster_demo-IUwY4BX5gBqjR0Pxu09Pfw==/lib/arm64/libflutter.so (BuildId: 854273bae6db1c10c29f7189cb0cf640ad4db110)
      #18 pc 0000000001334c80  /data/app/~~W2sUpMihWXQXs-Yx0cuHWg==/com.example.unable_to_merge_raster_demo-IUwY4BX5gBqjR0Pxu09Pfw==/lib/arm64/libflutter.so (BuildId: 854273bae6db1c10c29f7189cb0cf640ad4db110)
      #19 pc 0000000001337b54  /data/app/~~W2sUpMihWXQXs-Yx0cuHWg==/com.example.unable_to_merge_raster_demo-IUwY4BX5gBqjR0Pxu09Pfw==/lib/arm64/libflutter.so (BuildId: 854273bae6db1c10c29f7189cb0cf640ad4db110)
      #20 pc 00000000000eb868  /apex/com.android.runtime/lib64/bionic/libc.so (__pthread_start(void*)+64) (BuildId: a790cdbd8e44ea8a90802da343cb82ce)
      #21 pc 000000000008ba88  /apex/com.android.runtime/lib64/bionic/libc.so (__start_thread+64) (BuildId: a790cdbd8e44ea8a90802da343cb82ce)
Lost connection to device.
```