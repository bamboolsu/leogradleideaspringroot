# leogradleideaspringroot
初始参考: http://blog.csdn.net/u013360850/article/details/53415005
    
    编译项目:   在命令行进入到该项目根目录下，输入 gradle build 进行编译
                       编译成功后输出build successful
         也可以在左侧的 gradle 中点击刷新按钮，效果是一样的
    
    启动项目: 在命令行中输入 gradle bootrun 进行启动项目
           也可以使用左侧的 gradle 中 Task 下的 application 中的 bootRun 按钮启动（参照上图）
           默认的会启动 tomcat，使用8080端口，如果端口被占用会报错
    
    通过浏览器访问该项目:    该项目因为配置的路径为根路径，所以直接访问localhost:8080即可
    
