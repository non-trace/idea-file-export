# idea-file-export
计划实现类似eclipse中的export文件的功能，
主要是给一些有特殊需求比如导出文件目录结构等提供便利

## 1.下载项目，调试插件
将项目Clone到本地后，需要在相应的iml文件中的Module节点下，
添加项目标识,然后再运行，否则会导致运行时插件不成功
 ```xml
   <component name="DevKit.ModuleBuildProperties" url="file://$MODULE_DIR$/resources/META-INF/plugin.xml" />
   <component name="NewModuleRootManager" inherit-compiler-output="true">
 ```