配置安装flutter

安装Xcode Android studio  Java  SDK      

1. 目录下新建 development 文件夹
2. cd ./development  官网下载flutter。或git clone flutter
3. developement  下解压 flutter
4. 执行 export PATH="$PATH:`pwd`/flutter/bin"
5. 执行 flutter precache 如果没有安装jdk，会报错，先安装java  jdk
6. 执行 flutter doctor 看是否安装好依赖
7. 创建  .bash_profile 文件 如过有直接执行下面命令
8. open .bash_profile
    export PATH=/Users/wusaisai/development/flutter/bin:$PATH
    export PUB_HOSTED_URL=https://pub.flutter-io.cn
    export FLUTTER_STORAGE_BASE_URL=https://storage.flutter-io.cn
9. 安装 android studio  https://developer.android.google.cn/studio/
10.  [✗] Android toolchain - develop for Android devices  报错信息
11. 打开 .bash_profile   
       添加
       export ANDROID_HOME="/Users/wusaisai/Library/Android/sdk"   //添加自己的sdk路径
       export PATH=${PATH}:${ANDROID_HOME}/tools
       export PATH=${PATH}:${ANDROID_HOME}/platform-tools
12. 执行 flutter doctor
13. 还会报错  执行  flutter doctor --android-licenses





1. 完美解决


最终 .badh_profile 
    export PATH=/Users/wusaisai/development/flutter/bin:$PATH
    export PUB_HOSTED_URL=https://pub.flutter-io.cn
    export FLUTTER_STORAGE_BASE_URL=https://storage.flutter-io.cn

    export ANDROID_HOME="/Users/wusaisai/Library/Android/sdk" 
    export PATH=${PATH}:${ANDROID_HOME}/tools
    export PATH=${PATH}:${ANDROID_HOME}/platform-tools
