# 前言

欢迎来到宿舍管理小程序项目，该项目基于Spring Boot开发，致力于为宿舍管理者提供便捷、高效的管理工具。通过微信小程序，实现宿舍信息查询、报修、投诉等功能，提高宿舍管理的透明度和效率。

# 内容介绍

本项目主要包括以下几个模块：宿舍信息管理、维修管理、投诉建议、宿舍分配等。用户可以通过微信小程序端轻松完成报修、投诉等操作，管理员则可以通过后台管理系统进行宿舍信息的维护和调整。此外，项目还提供了丰富的数据统计和分析功能，为管理者决策提供数据支持。

# 技术介绍

## 语言：Java

## 使用框架：Spring、Spring MVC、MyBatis、微信小程序

## 前端技术：JS、Vue、CSS3、Uniapp

## 开发工具：IDEA/Eclipse、Uniapp

## 数据库：MySQL 5.7/8.0

## 数据库管理工具：phpStudy/Navicat

## JDK版本：JDK 1.8

## Maven：Apache Maven 3.8.1-bin

## 前端环境：Node.js 12/14/16

# 核心代码

以下是项目中的一部分核心代码，展示了Spring Boot与MyBatis结合实现宿舍信息查询的过程：

```java
// 宿舍信息查询接口
@RequestMapping("/getDormitoryInfo")
public DormitoryInfo getDormitoryInfo(@RequestParam("dormitoryId") int dormitoryId) {
    return dormitoryService.getDormitoryInfo(dormitoryId);
}

// 宿舍信息Service层实现
public DormitoryInfo getDormitoryInfo(int dormitoryId) {
    return dormitoryMapper.getDormitoryInfo(dormitoryId);
}

// 宿舍信息Mapper.xml
<select id="getDormitoryInfo" resultType="com.example.dormitory_management.entity.DormitoryInfo">
    SELECT * FROM dormitory_info WHERE id = #{dormitoryId}
</select>
```

# 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

# 项目截图
![封面图片](https://img10.360buyimg.com/ddimg/jfs/t1/350315/19/3228/77902/68c6264aF6d2c7f6c/92171ec6fc0b6a4e.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/345560/25/3236/20895/68c62622F20d54866/fc49e20a13b8e00d.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/333370/29/12873/12717/68c62622Fbb94e39b/4e13b1e86ff64765.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/332509/11/13101/20151/68c62623F0ed6f8a6/e9e1caf762e2d55c.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/329287/2/13056/18252/68c62623Fe8dfebc1/e03aa773179ccb8d.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/328002/17/19940/12987/68c62624Fdbd816fe/069df905c830eba3.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/329192/3/12962/23317/68c62624Fe4c8d0d9/93e8e99c3110c0d3.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/325394/21/19677/13282/68c62624Fba6274da/76b8dc535fe8a997.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/326447/16/19838/16929/68c62625F338908e5/84bded915dbcce70.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/342445/13/3192/15441/68c62625F27d8443f/d5a95b5a342f9e0f.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
