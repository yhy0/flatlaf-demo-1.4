Godzilla 依赖的 flatlaf-demo 库，官方没有jar包 https://github.com/JFormDesigner/FlatLaf/tree/main/flatlaf-demo 并且使用gradle生成的有点问题



重新使用 maven 构建,反编译好Godzilla后，pom.xml中

```xml
<dependency>
    <groupId>com.formdev</groupId>
    <artifactId>flatlaf-demo</artifactId>
    <version>1.4</version>
    <systemPath>${project.basedir}/lib/flatlaf-demo-1.4.jar</systemPath>
</dependency>
```

![image-20210804165513059](https://cdn.jsdelivr.net/gh/yhy0/PicGoImg@master/JavaFX/20210804165534.png)



Godzilla 源码

https://github.com/808Mak1r/GodzillaSource