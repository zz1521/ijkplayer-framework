# ijkplayer-framework

ijkplayer编译打包的framework

- module-default.sh 更多的编解码器/格式
- module-lite-hevc.sh 较少的编解码器/格式(包括hevc)
- module-lite.sh 较少的编解码器/格式(默认情况)


#### 此处编解码器/格式 采用module-default.sh  支持更多格式 并且对https支持


#### 使用方法，下载对应版本，拖到项目工程中：

  -  1.需要添加系统依赖库
  
  ```
  AVFoundation.framework
  AudioToolbox.framework
  CoreGraphics.framework
  CoreMedia.framework
  CoreVideo.framework
  libbz2.tbd
  libz.tbd
  libc++.tbd
  MediaPlayer.framework
  MobileCoreServices.framework
  OpenGLES.framework
  QuartzCore.framework
  VideoToolbox.framework
  ```


#### 此次编译打包时间 --- 2020-07-11
