# spring-boot-runner  

1. add script to init.d
2. add daemon to startup
### Ubuntu/Debian  
add script to startup scripts via xx-rc.d:  
```update-rc.d scriptname defaults```  
### RedHat/Fedora  
add script to startup scripts via xx-rc.d:  
```chkconfig --add scriptname``` 	

