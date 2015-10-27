# piggsoft-spring
Spring MVC Maven archetype  
Spring MVC Maven 模板文件

使用下面的命令，即可创建一个全新的带依赖，带部分配置的项目

####使用方法
````
1. mvn archetype:create-from-project
2. cd target/generated-sources/archetype/
3. mvn install
4. mvn archetype:generate -DarchetypeCatalog=local
````
####在一行内使用命令
````
mvn archetype:create-from-project & cd target/generated-sources/archetype/ & mvn install & cd D:/ & mvn archetype:generate -DarchetypeCatalog=local
````