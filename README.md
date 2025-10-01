 
# OpenGL ES 3.0 开发系统性学习教程

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://github.com/githubhaohao/NDK_OpenGLES_3_0/blob/master/LICENSE.txt)
![Build](https://img.shields.io/badge/build-passing-brightgreen)
[![apk](https://img.shields.io/badge/APK-download-green.svg)](https://github.com/githubhaohao/NDK_OpenGLES_3_0/raw/master/doc/OepnGLES.apk)
[![GitHub stars](https://img.shields.io/github/stars/githubhaohao/NDK_OpenGLES_3_0)](https://github.com/githubhaohao/NDK_OpenGLES_3_0/stargazers)

备注: 请使用 **Android Studio 4.1+ ，NDK r21，其中一些 Case 的 3D 效果是通过手势触发（转动和缩放）**

## 关于跨平台
OpenGL ES 是一套跨平台的编程接口（原生 C 接口，Java 和 JS 库都是二次封装的），支持 Android、iOS、Windows、Linux 平台。

Android 代码只是做 UI 展示，核心代码是放到 C++ 那一层实现的，各个平台都可以共用（可以做到一套代码在这多个平台上共用和移植）。

本教程适用于 Android\iOS\Windows\Linux 平台的开发者。

## 作者声明

有读者反馈，最近有培训机构将本教程进行打包售卖，严重违背了本项目免费开源的初衷。再次声明：**任何商业机构或个人未经作者【微信ID：Byte-Flow 】许可，不得将本教程及其项目配套代码用于 "打包贩卖、出书和卖课" 等商业用途，一经发现，全网声讨，并使用法律手段维护作者权益。再次感谢各位读者的监督和反馈。**

## 展示图

![beating_heart](https://github.com/githubhaohao/NDK_OpenGLES_3_0/blob/master/gif/beating_heart.gif)
![poly_3d_model](https://github.com/githubhaohao/NDK_OpenGLES_3_0/blob/master/gif/poly.gif)

![ogl_head](https://github.com/githubhaohao/NDK_OpenGLES_3_0/blob/master/gif/head.gif)


## 基础篇

- [OpenGL ES 3.0 开发（01）：绘制一个三角形](https://blog.csdn.net/Kennethdroid/article/details/95622391)

- [OpenGL ES 3.0 开发（02）：纹理映射](https://blog.csdn.net/Kennethdroid/article/details/96887637)

- [OpenGL ES 3.0 开发（03）：YUV 渲染](https://blog.csdn.net/Kennethdroid/article/details/97153407)

- [OpenGL ES 3.0 开发（04）：VBO、EBO 和 VAO](https://blog.csdn.net/Kennethdroid/article/details/98088890)

- [OpenGL ES 3.0 开发（05）：FBO 离屏渲染](https://blog.csdn.net/Kennethdroid/article/details/98883854)

- [OpenGL ES 3.0 开发（06）：EGL](https://blog.csdn.net/Kennethdroid/article/details/99655635)

- [OpenGL ES 3.0 开发（07）：Transform Feedback](https://blog.csdn.net/Kennethdroid/article/details/100083599)

- [OpenGL ES 3.0 开发（08）：坐标系统](https://blog.csdn.net/Kennethdroid/article/details/100898155)

- [OpenGL ES 3.0 开发（09）：光照基础](https://blog.csdn.net/Kennethdroid/article/details/101220947)

- [OpenGL ES 3.0 开发（10）：深度测试](https://blog.csdn.net/Kennethdroid/article/details/101709694)

- [OpenGL ES 3.0 开发（11）：模板测试](https://blog.csdn.net/Kennethdroid/article/details/102533260)

- [OpenGL ES 3.0 开发（12）：混合](https://blog.csdn.net/Kennethdroid/article/details/102630858)

- [OpenGL ES 3.0 开发（13）：实例化（Instancing）](https://blog.csdn.net/Kennethdroid/article/details/102770813)

- [OpenGL ES 3.0 开发（14）：粒子（Particles）](https://blog.csdn.net/Kennethdroid/article/details/102881654)

- [OpenGL ES 3.0 开发（15）：立方体贴图（天空盒）](https://blog.csdn.net/Kennethdroid/article/details/102991524)

- [OpenGL ES 3.0 开发（16）：相机预览](https://blog.csdn.net/Kennethdroid/article/details/103189489)

- [OpenGL ES 3.0 开发（17）：相机基础滤镜](https://blog.csdn.net/Kennethdroid/article/details/103335598)

- [OpenGL ES 3.0 开发（18）：相机 LUT 滤镜](https://blog.csdn.net/Kennethdroid/article/details/103355129)

- [OpenGL ES 3.0 开发（19）：相机抖音滤镜](https://blog.csdn.net/Kennethdroid/article/details/103449935)

- [OpenGL ES 3.0 开发（20）：3D 模型](https://blog.csdn.net/Kennethdroid/article/details/103771970)

- [OpenGL ES 3.0 开发（21）：3D 模型加载和渲染](https://blog.csdn.net/Kennethdroid/article/details/103825593)

- [OpenGL ES 3.0 开发（22）：PBO](https://blog.csdn.net/Kennethdroid/article/details/103931627)

- [OpenGL ES 3.0 开发（23）：多重渲染目标（MRT）](https://blog.csdn.net/Kennethdroid/article/details/108873665)

- [OpenGL ES 3.0 开发（24）：帧缓冲区位块传送（Blit）](https://blog.csdn.net/Kennethdroid/article/details/109032497)

- [OpenGL ES 3.0 开发（25）：TBO（GLES 3.1）](https://blog.csdn.net/Kennethdroid/article/details/109749018)

- [OpenGL ES 3.0 开发（26）：UBO（GLES 3.2）](https://blog.csdn.net/Kennethdroid/article/details/109749018)


## 展示图

![avatar](https://github.com/githubhaohao/NDK_OpenGLES_3_0/blob/master/gif/avatar.gif)
![board](https://github.com/githubhaohao/NDK_OpenGLES_3_0/blob/master/gif/draw_board.gif)

## 应用篇

- [OpenGL ES 实现心动特效](https://blog.csdn.net/Kennethdroid/article/details/104536532)

- [OpenGL ES 实现瘦身大长腿效果](https://blog.csdn.net/Kennethdroid/article/details/104546234)

- [OpenGL ES 绘制贝塞尔曲线](https://blog.csdn.net/Kennethdroid/article/details/104721096)

- [OpenGL ES 实现瘦脸大眼效果](https://blog.csdn.net/Kennethdroid/article/details/104907763)

- [OpenGL ES 实现头部形变和头部晃动效果](https://blog.csdn.net/Kennethdroid/article/details/105208054)

- [OpenGL ES 实现实时音频的可视化](https://blog.csdn.net/Kennethdroid/article/details/106128767)

- [OpenGL ES 实现刮刮卡和手写板功能](https://blog.csdn.net/Kennethdroid/article/details/106339286)

- [OpenGL ES 实现 3D 阿凡达效果](https://blog.csdn.net/Kennethdroid/article/details/106423475)

- [OpenGL ES 实现动态（水波纹）涟漪效果](https://blog.csdn.net/Kennethdroid/article/details/106556584)

- [OpenGL ES 调试工具](https://blog.csdn.net/Kennethdroid/article/details/106695602)

- [OpenGL ES 传输超大数组给着色器程序](https://blog.csdn.net/Kennethdroid/article/details/109749018)

- [面试中经常被问到的 OpenGL ES 对象，你知道的有哪些？](https://blog.csdn.net/Kennethdroid/article/details/112379836)

- [OpenGL ES 渲染图像读取哪家强](https://blog.csdn.net/Kennethdroid/article/details/109339906)

- [利用 OpenGL ES 给视频播放器和相机做个字符画滤镜](https://blog.csdn.net/Kennethdroid/article/details/113379112)

- [使用 OpenGL 实现 RGB 到 YUV 的图像格式转换](https://blog.csdn.net/Kennethdroid/article/details/117675581)

- [OpenGL ES 共享上下文时，可以共享哪些资源？](https://blog.csdn.net/Kennethdroid/article/details/143743942)

- [OpenGL ES 文字渲染方式有几种？](https://blog.csdn.net/Kennethdroid/article/details/143744762)

- [OpenGL ES 文字渲染进阶：渲染中文字体](https://blog.csdn.net/Kennethdroid/article/details/143744917)

- [OpenGL ES + 人像抠图实现人像留色](https://blog.csdn.net/Kennethdroid/article/details/132055965) 

- [OpenGL ES + GLTranslations 实现各种图像转场效果](https://blog.csdn.net/Kennethdroid/article/details/132656888)

- [OpenGL ES 实现抖音传送带特效](https://blog.csdn.net/Kennethdroid/article/details/132656992)

- [OpenGL ES 实现抖音“蓝线挑战”特效](https://blog.csdn.net/Kennethdroid/article/details/132657029)
  
- [OpenGL ES 利用 Shader 实现 RGBA 到 NV21 图像格式转换](https://blog.csdn.net/Kennethdroid/article/details/132055489)

- [OpenGL ES 修图（P 图）功能](https://blog.csdn.net/Kennethdroid/article/details/133125813)

- [OpenGL ES 抖音“传送带“特效实现终极版](https://blog.csdn.net/Kennethdroid/article/details/135014109)

- [OpenGL ES 3.0 帧缓冲区失效 glInvalidateFramebuffer](https://blog.csdn.net/Kennethdroid/article/details/135203000)

- [OpenGL ES 如何直接渲染 P010、P016 格式图像？](https://blog.csdn.net/Kennethdroid/article/details/135348813)

- [OpenGL ES 渲染 NV21、NV12、I420、YV12、YUYV、UYVY、I444（建议收藏）](https://blog.csdn.net/Kennethdroid/article/details/136213988)

## 相关推荐

- [Android OpenGL Camera 2.0 实现 30 种滤镜和抖音特效](https://github.com/githubhaohao/OpenGLCamera2)
- [Android FFmpeg 音视频开发教程](http://mp.weixin.qq.com/s?__biz=MzIwNTIwMzAzNg==&mid=506681298&idx=1&sn=50177285bf0d330d0dfc4e0954d5ad12&chksm=0cf384e13b840df76f89aeb8ac76939ff32b2f9bf600729782d61698181af60d92cce61ee150#rd)




