# Spring Boot starter测试题

## 练习描述
  本题要求通过完善Spring boot`build.gradle`文件里面的配置类成功启动项目以及成功执行。
  打开项目文件后，显示的如下结构：
  
  
  
  点击`build.gradle`文件，后：
  
```
  plugins {
    id 'org.springframework.boot' version '2.1.3.RELEASE'
    id 'java'
}

apply plugin: 'io.spring.dependency-management'

group = 'com.example'
version = '0.0.1-SNAPSHOT'
sourceCompatibility = '1.8'

repositories {
    mavenCentral()
}

dependencies {
    //TODO： 在此处编写出系统中需要的 starter
}

```


## 环境描述 
- java8
- Intellij-IDEA

## 如何开始
- 打开项目后，`build.gradle`中完成代码,并且启动下面两个命令

命令,执行测试文件：

```
 ./gradlew test    
```

命令启动项目：

```
./gradlew bootRun
```
- 均执行成功，截图即可。
