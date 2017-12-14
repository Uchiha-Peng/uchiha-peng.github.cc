---
layout: post
title: DotNet Core 常用命令
date: 2017-12-14
categories: blog
tags: [笔记]
---
1. dotnet --help

   > 查看常用指令

   |   命令    |                   用法                   |
   | :-----: | :------------------------------------: |
   |   new   |              初始化 .NET 项目。              |
   | restore |           还原 .NET 项目中指定的依赖项。           |
   |   run   |            编译并立即执行 .NET 项目。            |
   |  build  |              生成 .NET 项目。               |
   | publish |        发布 .NET 项目以进行部署(包括运行时)。         |
   |  test   |         使用项目中指定的测试运行程序运行单元测试。          |
   |  pack   |              创建 NuGet 包。               |
   | migrate | 将基于 project.json 的项目迁移到基于 MSBuild 的项目。 |
   |  clean  |                清除生成输出。                 |
   |   sln   |             修改解决方案(SLN)文件。             |
   |   add   |               将引用添加到项目中。               |
   | remove  |               从项目中删除引用。                |
   |  list   |               列出项目中的引用。                |
   |  nuget  |             提供其他 NuGet 命令。             |
   | msbuild |      运行 Microsoft 生成引擎 (MSBuild)。      |
   | vstest  |        运行 Microsoft 测试执行命令行工具。​        |

2. dotnet --version

   > 查看DotNet Core SDK版本

3. dotnet new --help

   > 查看可用的模板(常用模板如下)

   ​

   |             模板             |    短名称    |           标记           |
   | :------------------------: | :-------: | :--------------------: |
   |    Console Application     |  console  |        控制台应用年程序        |
   |     ASP.NET Core Empty     |    web    |      web page应用程序      |
   | ASP.NET Core Web App (MVC) |    mvc    |        mvc应用程序         |
   |    ASP.NET Core Web App    |   razor   | CShtml应用(不带Controller) |
   |    ASP.NET Core Web API    |  webapi   |       web api应用        |
   |         Web Config         | webconfig |        web配置文件         |
   |       Solution File        |    sln    |          解决方案          |


4. cd desktop

   > 进入到桌面文件夹

5. cd ../

   > 进入上级目录

6. mkdir dic

   > 创建创建新的文件夹

7. dotnet new console 

   > 直接在当前文件夹创建某个类型的项目

8. dotnet new console --name myApp

   > 在当前目录创建

9. cdoe .

   > 在VS Code中打开当前目录（最好是先进入项目的文件目录中，然后在执行此命令）

