# 多平台异构服务适配及协作构件

通过反射对AWS、Azure、Google、Alibaba等公司的开发API接口及其SDK的分析，生成对应云管API的参数、调用关系和执行逻辑。进而可以分析其代码与文档质量，为服务集成提供支撑。

## 技术架构

![Alt Screenshot](https://github.com/tteat/wukong/raw/master/img/架构2.png)

## 技术特色

* Java反射：API分析方法利用Java反射技术，通过分析云服务示例代码抽象出三元组模型，使用基于统计分析的方式进行API的搜索和发现；
* 动态映射：通过分析出服务的API并构造成树形结构，接着建立High-level API和Low-level API映射模型，通过动态映射的方式实现运行时服务适配

## 代码架构
wukong<br>
├─LICENSE<br>
├─README.md<br>
├─pom.xml<br>
├─src<br>
|  ├─main<br>
|  |  ├─java<br>
|  |  |  ├─io<br>
|  |  |  | ├─github<br>
|  |  |  | |   ├─pdoslab<br>
|  |  |  | |   |    ├─wukong<br>
|  |  |  | |   |    |   ├─Analyzer.java<br>
|  |  |  | |   |    |   ├─StartAnalyzer.java<br>
|  |  |  | |   |    |   ├─utils<br>
|  |  |  | |   |    |   |   ├─ClassUtils.java<br>
|  |  |  | |   |    |   |   ├─JSONUtils.java<br>
|  |  |  | |   |    |   |   ├─JavaUtils.java<br>
|  |  |  | |   |    |   |   ├─KubeUtils.java<br>
|  |  |  | |   |    |   |   └StringUtils.java<br>
|  |  |  | |   |    |   ├─model<br>
|  |  |  | |   |    |   |   └JDKInfo.java<br>
|  |  |  | |   |    |   ├─core<br>
|  |  |  | |   |    |   |  ├─Heuristicv1.java<br>
|  |  |  | |   |    |   |  └Heuristicv2.java<br>
|  |  |  | |   |    |   ├─analyzer<br>
|  |  |  | |   |    |   |    ├─RequestWithObjectPatternAnalyzer.java<br>
|  |  |  | |   |    |   |    └RequestWithParameterPatternAnalyzer.java<br>
├─results<br>
├─conf<br>


## 部署方式    
```
git clone https://github.com/tteat/wukong.git
java -jar wukong-1.0.0-SNAPSHOT-jar-with-dependencies.jar jdkinfo.conf
```
the jar can be get from https://github.com/pdos-lab/Wukong/releases/download/v1.0.0/wukong-1.0.0-SNAPSHOT-jar-with-dependencies.jar

## 使用说明   

* Wukong/pom.xml ： 配置要分析的SDK包的依赖
* Wukong/conf ： 配置云服务的配置信息（仿照目录下的文件）
* Wukong/src/main/java/io/github/pdoslab/wukong/Classifier.java ： 修改对应的config，运行文件，得到分析结果
* Wukong/src/main/java/io/github/pdoslab/wukong/Main.java ： 修改27行、32行配置，运行文件的出结果


TABLE I: The list of supported System for VM service

|  Country  |   Type    |   Name    |  Offical  |  Version  |      Document       |
| :-------: | :-------: | :-------: | :-------: | :-------: |      :-------:      |
|  USA      |     VM    |   Amazon    |    Yes    |   aws-java-sdk-ec2(1.11.799692)                       | [AWS](https://docs.aws.amazon.com/zh_cn/AmazonECS/latest/developerguide/logging-using-cloudtrail.html)                    |
|  USA      |     VM    |   Azure     |    Yes    |   [azure](https://github.com/Azure/azure-sdk-for-java.git)(1.34.0)                                    | [Azure](https://docs.azure.cn/zh-cn/virtual-machines/linux/quick-create-portal?toc=%2Fvirtual-machines%2Flinux%2Ftoc.json)|
|  USA      |     VM    |   Google    |    Yes    |   [google-api-services-compute](https://github.com/google/apis-client-generator.git)(v1-rev235-1.25.0）   | [Google](https://cloud.google.com/compute/docs/reference/rest/v1/)  |
|  China    |     VM    |   Aliyun    |    Yes    |   aliyun-java-sdk-ecs(4.17.8)                      | [aliyun](https://help.aliyun.com/document_detail/25484.html)        |
|  China    |     VM    |   Tencent   |    Yes    |   tencentcloud-sdk-java(3.0.112)                   | [Tencent](https://intl.cloud.tencent.com/product/api)               |

![Alt Screenshot](https://github.com/tteat/wukong/raw/master/img/api.png)
