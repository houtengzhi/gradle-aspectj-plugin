[ ![Download](https://api.bintray.com/packages/houtengzhi/maven/aspectj-plugin/images/download.svg) ](https://bintray.com/houtengzhi/maven/aspectj-plugin/_latestVersion)

# enhanced-adb-plugin
>Adb command gradle插件

### 更新
 1.0.1

### 集成

在项目根目录下的build.gradle文件中添加
```
buildscript {
    repositories {
        jcenter()
    }
    dependencies {
        classpath 'com.yechy.gradleplugin:adb-plugin:1.0.0'
    }
}
```

在mudule下的build.gradle文件中添加
```
apply plugin: 'com.yechy.adb-plugin'
```

### 配置项

|参数名|默认值|描述|
|-----|------|---|


