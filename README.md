# WeChirp - Chrome科学上网插件

无需任何繁琐设置，只需安装好插件，即可畅游互联网。智能区分墙内墙外地址，对用户来说此操作是透明的，系统自动判断是否需要开启代理，真正实现按需科学上网。基于目前市面上的chrome科学上网插件有大量的安全问题，容易被GFW探测到。本插件使用了chrome的 Native Messaging APIs 相关技术，结合自研的本地加密应用的安装(只需首次安装即可)，可以将信息安全加密并且代理出去。从而实现科学上网。同时WeChirp还提供了网址收藏功能，将喜欢的页面保存在云上，此功能是免费开放的。
## 安装说明
  先下载Webchirp的chrome插件安装文件包，包含相应的系统应用，目前支持mac和windows系统。
  mac系统的插件[下载地址](https://github.com/wechirp/wechirp/releases/download/1.0/wechirp-mac-1.0.zip)，windows系统的插件[下载地址](https://github.com/wechirp/wechirp/releases/download/1.0/wechirp-windows-1.0.zip)。
  如果以上地址下载不了，请使用云盘下载[下载地址](https://cowtransfer.com/s/b736927e52704b) 提取码：dcqpzy
## MAC/Windows安装插件演示
* 1.解压.zip文件到任意位置
* 2.打开chrome,点击右上角菜单，选择“更多工具”下的“扩展程序”。或者浏览器地址栏输入chrome://extensions 也能打开扩展程序界面
* 3.在扩展程序界面，右上角点击开发者模式。
* 4.左上角点击“加载已经解压的扩展程序”
* 5.找到第一步zip文件解压的位置，选择dist文件
* 6.插件加载好了，保存复制插件的ID,后面需要用到
![image](https://raw.githubusercontent.com/wechirp/wechirp/master/f3.gif)

## MAC安装本地应用
* 1.解压.zip文件里面有一个webchirp的应用程序，不要直接打开
* 2.打开Mac终端命令行工具，cd 到解压文件的那个目录下
* 3.安装应用执行命令：webchirp -install -chromeExtID=(将拷贝的插件id放在这里)                                 
![image](https://raw.githubusercontent.com/wechirp/wechirp/master/f4.gif)
* 4.卸载应用执行命令：wechirp -uninstall   

## Windows安装本地应用
* 1.解压.zip文件里面有一个webchirp.exe的应用程序，不要直接打开
* 2.在菜单搜索“cmd”找到命令行工具, cd 到解压文件的那个目录下
* 3.安装应用执行命令：webchirp.exe -install -chromeExtID=(将拷贝的插件id放在这里)                                 
![image](https://raw.githubusercontent.com/wechirp/wechirp/master/f5.gif)
* 4.卸载应用执行命令：wechirp.exe -uninstall 

## 说明
安装好以上程序，就可以打开chrome,点击插件小图标，注册即可实现科学上网。注意以上安装只需要一次。后续只管使用就好了。
![image](https://raw.githubusercontent.com/wechirp/wechirp/master/f6.gif)
