Assignment1:

Pre requisite
Install below plugins 

1-Maven integration plugin 
2-Checkstyle Plug-in 
3-FindBugs Plug-in 
4-Static Analysis Collector Plug-in 
5-Cobertura Plugin 

https://github.com/shumail12345/jenassignment/blob/master/intsallplugin.png

Install below softwares under Global tool configuration 
 Maven | Maven 3.5.2

https://github.com/shumail12345/jenassignment/blob/master/maven.png

 Java | You need Oracle account for same | JDK 8u162

https://github.com/shumail12345/jenassignment/blob/master/jdk.png

              

Setup CodeStability Job
            
Choose Job type as MavenProject 
Provide git repository 

https://github.com/OpsTree/ContinuousIntegration 


Use clean compile as target 

https://github.com/shumail12345/jenassignment/blob/master/codestability.png


Setup static code analysis Job


Choose Job type as MavenProject 
Provide git repository 

https://github.com/OpsTree/ContinuousIntegration 
Use clean compile findbugs:findbugs checkstyle:checkstyle as target 
https://github.com/shumail12345/jenassignment/blob/master/staticcodeana.png



 Choose Job type as MavenProject 
Provide git repository

https://github.com/OpsTree/ContinuousIntegration 
Use clean compile cobertura:cobertura as target 
https://github.com/shumail12345/jenassignment/blob/master/codecoverage.png
