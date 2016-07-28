# ProxyHelper

[![Join the chat at https://gitter.im/Nithmr/ProxyHelper](https://badges.gitter.im/Nithmr/ProxyHelper.svg)](https://gitter.im/Nithmr/ProxyHelper?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

A simple cli based system to automatically set fastest system-wide. 
  
===

###
  

===

###Requirements:-
  
1. **Linux**  -  ProxyHelper doesn't support for windows unfortunately (Yet)  
2. **Git**  -  You need to have git installed in your system   
```sudo apt-get install git```  
3. **Python3**  -  In Ubuntu based distributions since 14.04 it is already installed, otherwise you need to install this by yourself.

===

###Optional arguments:-
**The below are required only if you want to use **tor** related utilities:-**
  
4. **pip-3**  -  Again, this should come already installed with your OS, otherwise follow the step below.  
```sudo apt-get install python3-pip```
5. **socks python module**   
```sudo -H pip3 install pysocks```

===

###Installation  
1. Clone the repository to your machine home directory with the below command   
```git clone https://github.com/Nithmr/ProxyHelper ~/.proxyhelper```
2. Move to the directory "~/.proxyhelper" by   
```cd ~/.proxyhelper```
3. Make the installer script executable  
```chmod +x install.sh```  
4. Run the installer script  
```sudo ./install.sh```
    
===


###How to know if ProxyHelper is working?   

You may need to restart you terminal for this. Also, reconnect your interent connection to see ProxyHelper perform it's auto-proxy-set feature.    
  
1. You should be able to execute torpinger and zetproxy as a command in the shell. Type :-    
```zetproxy ```  
or      
```torpinger ```
3. Check the content of /var/tmp/torpingtest in interval of some time, if some lines are being added to the file automatically, then voila! your torpinging is working perfectly fine    
```cat /var/tmp/torpingtest ```
4. Check the content of your /etc/environment file, the best proxy for your network should be automatically set there.    
```cat /etc/environment ```

===


###Uninstallation
  
1. Go to the directory where you cloned ProxyHelper  
```cd ~/.proxyhelper```
2. Run the uninstallation script  
```sudo ./uninstall.sh```
   
===

###To reset the proxy  
1. Go to the directory where you cloned ProxyHelper  
2. Type the line below in the shell  
```sudo ./zetproxy None```

===
