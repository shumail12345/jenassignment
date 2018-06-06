
Assignment1

 1-Installed:
  nginx.x86_64 1:1.12.2-2.el7                                                   

Dependency Installed:
  gd.x86_64 0:2.0.35-26.el7                                                     
  gperftools-libs.x86_64 0:2.6.1-1.el7                                          
  libXpm.x86_64 0:3.5.12-1.el7                                                  
  nginx-all-modules.noarch 1:1.12.2-2.el7                                       
  nginx-filesystem.noarch 1:1.12.2-2.el7                                        
  nginx-mod-http-geoip.x86_64 1:1.12.2-2.el7                                    
  nginx-mod-http-image-filter.x86_64 1:1.12.2-2.el7                             
  nginx-mod-http-perl.x86_64 1:1.12.2-2.el7                                     
  nginx-mod-http-xslt-filter.x86_64 1:1.12.2-2.el7                              
  nginx-mod-mail.x86_64 1:1.12.2-2.el7                                          
  nginx-mod-stream.x86_64 1:1.12.2-2.el7                                        

Complete!
 
 2-install below listed plugins 
   
    (a) SSH plugin

    (b) Git plugin

   

 Assignment2:
 Enable password less login between jenkins & root user
 [vagrant@localhost ~]$ sudo su jenkins
 bash-4.2$ ssh root@192.168.33.68
 Last login: Wed Jun  6 14:29:28 2018
 [root@localhost ~]# logout
 Connection to 192.168.33.68 closed.
 bash-4.2$ exit
 exit
 [vagrant@localhost ~]$ sudo su jenkins
 bash-4.2$ ssh root@192.168.33.68
 Last login: Wed Jun  6 14:30:08 2018 from 192.168.33.68
 [root@localhost ~]# exit
 logout
 Connection to 192.168.33.68 closed.
 bash-4.2$ exit
 exit
 [vagrant@localhost ~]$ 

