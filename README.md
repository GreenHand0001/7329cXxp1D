# 前言

本项目为【Java计算机毕业设计分享】的逍遥大药房管理系统，是一个基于Java和MySQL开发的实战项目。在此分享给大家，以供学习和参考。项目包含完整的源码、文档报告及代码讲解，助你轻松掌握药店管理系统的开发流程。

# 内容介绍

逍遥大药房管理系统旨在帮助药店实现信息化管理，提高工作效率。系统主要包括以下模块：用户管理、药品管理、库存管理、销售管理等。通过这些模块，可以实现药品的采购、销售、库存等环节的自动化处理，降低人力成本，提高管理水平。

# 技术介绍

## 语言：Java
## 使用框架：Spring Boot
## 前端技术：JS、Vue、css3
## 开发工具：IDEA/Eclipse
## 数据库：MySQL 5.7/8.0
## 数据库管理工具：phpstudy/Navicat
## JDK版本：jdk1.8
## Maven: apache-maven 3.8.1-bin
## 前端环境：Node.Js 12\14\16

# 核心代码

以下为药品管理模块的部分核心代码：

```java
// 药品实体类
public class Drug {
    private int id; // 药品ID
    private String name; // 药品名称
    private double price; // 药品价格
    private int stock; // 药品库存

    // 省略getter和setter方法
}

// 药品服务类
@Service
public class DrugService {
    @Autowired
    private DrugMapper drugMapper;

    // 添加药品
    public int addDrug(Drug drug) {
        return drugMapper.insert(drug);
    }

    // 更新药品
    public int updateDrug(Drug drug) {
        return drugMapper.updateById(drug);
    }

    // 删除药品
    public int deleteDrug(int id) {
        return drugMapper.deleteById(id);
    }

    // 查询药品列表
    public List<Drug> getDrugList() {
        return drugMapper.selectList(null);
    }
}
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

![封面图片](https://img13.360buyimg.com/ddimg/jfs/t1/319932/31/25174/134290/689f2a7aFa88f4a54/828fc7f4e576f5a7.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/322383/40/9160/70850/689ef5ccF07cfd881/c7671d48924dc699.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/320436/3/25036/75271/689ef5ccF9e68b51b/73990a9060dbd071.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/320340/32/25375/20737/689ef5cdF9e0f4ed0/e25cd797be6e735d.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/313573/19/27078/37242/689ef5cdFd5301c5e/240174f4d83f882a.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/320307/11/25594/33455/689ef5d0Fba6b8b96/d2004595dac14dc3.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/307587/4/26645/55303/689ef5d0F8ce36b95/b16d159650c706bb.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/316751/19/25534/73732/689ef5d4Ff7f94236/89ba198c48d5ef64.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/190746/26/47786/57563/689ef5d5F252bc673/4a16e1207aa18819.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/291445/1/26746/44087/689ef5d9F756d4baf/1bc47ee6ced4b60f.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
