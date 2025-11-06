# 前言

欢迎来到基于SSM（Spring、SpringMVC、MyBatis）的宿舍管理系统设计项目。该项目旨在为学校宿舍管理部门提供一个便捷、高效的管理工具，实现宿舍信息管理、宿舍分配、维修申报等功能。以下是对该项目的基本介绍和技术细节。

## 内容介绍

本项目基于Java语言，使用Spring、SpringMVC、MyBatis框架进行开发，前端采用JS、Vue、CSS3技术，数据库使用MySQL 5.7/8.0。项目结构清晰，易于维护和扩展。主要模块包括：宿舍楼信息管理、房间信息管理、学生信息管理、维修申报管理等。

## 技术介绍

- **语言：** Java
- **使用框架：** Spring、SpringMVC、MyBatis
- **前端技术：** JS、Vue、CSS3
- **开发工具：** IDEA/Eclipse
- **数据库：** MySQL 5.7/8.0
- **数据库管理工具：** phpstudy/Navicat
- **JDK版本：** jdk1.8
- **Maven：** apache-maven 3.8.1-bin
- **前端环境：** Node.Js 12\14\16

## 核心代码

以下是一段关于查询宿舍楼信息的核心代码：

```java
// 注入Service层
@Autowired
private DormitoryService dormitoryService;

// 查询宿舍楼信息
@RequestMapping("/listDormitory")
public String listDormitory(Model model) {
    List<Dormitory> dormitoryList = dormitoryService.listDormitory();
    model.addAttribute("dormitoryList", dormitoryList);
    return "dormitoryList";
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

![封面图片](https://img11.360buyimg.com/ddimg/jfs/t1/329881/21/10330/88747/68bbdd58Fade2a747/e0f8d6172c4d975d.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/327643/23/16616/18714/68bbdd30Ff774cff8/522ea41c05d301b8.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/332679/18/10058/31293/68bbdd30F94aa251f/f32eb46236aa6665.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/326321/32/16903/34789/68bbdd31F42e52c58/272604a24ef27420.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/343387/27/249/31778/68bbdd31Fe7492ffd/5679d510e9592b5e.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/327600/32/16853/48193/68bbdd32F7c572510/40dfbe9a74ad20ae.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/347839/33/317/34410/68bbdd33F01ec2bc6/3f4e166c2c1c15f4.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/344912/28/333/50838/68bbdd33F43877f45/f9e1d4a3aff9c2d3.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/349523/39/330/68575/68bbdd34F946d476b/b63fbed022bcf14f.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/333243/38/10286/18587/68bbdd35F1eafbbc6/ac33e2e783bd2745.jpg)

