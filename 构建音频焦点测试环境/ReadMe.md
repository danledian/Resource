

### 准备
安装文件夹下APK文件
如设备无界面操作，可使用以下ADB命令完成操作

### 启动APP

```
adb shell am start -n com.hs.audiofocusdemo1/com.hs.audiofocusdemo.MainActivity
```

### 获取音频焦点并播放音乐
```
adb shell am broadcast -a com.hs.audiofocusdemo1.requestFocus
```


