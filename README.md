# ProxyHelper

[![Join the chat at https://gitter.im/Nithmr/ProxyHelper](https://badges.gitter.im/Nithmr/ProxyHelper.svg)](https://gitter.im/Nithmr/ProxyHelper?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

A comprehensive command line utility to automate all your proxy settings.  
  
===

###Supports:-
  
1. **git**
2. **web-browsers**-firefox,chrome (Set option "Use System Proxy" in preference of browser)
3. **gnome proxy module**
4. **kde proxy module**
5. **apt**                                 
  

===

###Requirements:-
  
**Compulsary:-**  
  
1. Linux  
2. python3+  
3. git 
`sudo apt-get install git`  
  
===  
  
**Optional:-**  
  
1. pysocks, pip3 (required only for tor related utilities)  
  
===
  
###Installation:-  

```
git clone https://github.com/clearnote01/phelp.git ~/.proxyhelper && cd ~/.proxyhelper && 
sudo chmod +x ./phelp-installer.sh && ./phelp-installer.sh
```  

===  
  
  
###Usage:- 
  
1. Set best proxy  
  
`phelp -S`  
  
2. Evaluate best proxy  
  
`phelp -G`  
  
3. Clear all proxy  
  
`phelp -N`  
  
4. Set custom proxy  
  
`phelp -C 172.16.24.2:3128`** *(Replace the proxy by what you require*    
  
5. Show help  
  
`phelp -h`  
  
