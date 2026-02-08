## 前言

欢迎来到家政项目小程序+SSM框架的GitHub开源项目页面。本项目旨在为用户提供一套完善的家政服务解决方案，结合当前流行的微信小程序和SSM框架技术，实现便捷、高效的家政服务体验。

## 内容介绍

本项目是一款基于Java语言和SSM框架开发的家政服务小程序，主要功能包括：用户注册登录、家政人员信息展示、预约家政服务、服务评价等。通过使用Uniapp技术，实现一套代码多端适配，让用户可以在微信小程序、H5等多种平台上使用。同时，本项目还提供了丰富的后台管理功能，方便管理员对家政人员、服务订单等进行管理。

## 技术介绍

- 语言：Java
- 使用框架：Spring、Springmvc、MyBatis、微信小程序
- 前端技术：JS、Vue、CSS3、Uniapp
- 开发工具：IDEA/Eclipse，Uniapp
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven：apache-maven 3.8.1-bin
- 前端环境：Node.Js 12\14\16

## 核心代码

以下是一段关于家政服务列表展示的核心代码：

```java
// HomeServiceController.java
@RestController
@RequestMapping("/homeService")
public class HomeServiceController {

    @Autowired
    private HomeServiceService homeServiceService;

    @GetMapping("/list")
    public ResponseEntity<List<HomeService>> listHomeServices() {
        List<HomeService> homeServices = homeServiceService.listHomeServices();
        return ResponseEntity.ok(homeServices);
    }
}
```

## 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

## 项目截图
![封面图片](https://img14.360buyimg.com/ddimg/jfs/t1/349143/32/2905/154792/68c4dda7F5c270df6/93bc3fe4cdcad038.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/323741/17/19617/29771/68c4dd7eFc44c088a/3320fd48251f5ebb.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/340608/37/10221/13124/68c4dd7eFab76f5f9/250d9cbaba648ef9.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/332371/1/12601/20759/68c4dd7fF40e27d53/bb0f0f15c4b2a56e.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/341561/21/2846/34657/68c4dd7fF4d2f5801/7a383348a4315ca2.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/332563/18/12696/44394/68c4dd7fF3dcbaf85/fa469b0bfa7794ba.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/328595/21/19509/10580/68c4dd7fF753b1fcd/cb8294a230db0d50.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/350855/14/2692/114254/68c4dd80Fee31a928/2a5f4241c9147a65.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/351111/25/2737/28804/68c4dd80F42ee8692/6866c455cf3c2cec.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/337781/26/10139/15132/68c4dd80Ff8251a62/a2439455451619da.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
