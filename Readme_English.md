[![Build Status](https://travis-ci.org/freeeyes/PSS.svg?branch=master)](https://travis-ci.org/freeeyes/PSS)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![GitHub version](https://badge.fury.io/gh/freeeyes%2FPSS.svg)](https://badge.fury.io/gh/freeeyes%2FPSS)
[![coverity](https://scan.coverity.com/projects/14425/badge.svg)](https://scan.coverity.com/projects/freeeyes-pss)
[![Platform](https://img.shields.io/badge/platform-Linux,%20Windows-green.svg?style=flat)](https://github.com/freeeyes/PSS)
 
> this is a server framework. Support the way developers use plug-ins ( so or dlls ),
> develop logical services for related TCP and UDP. This service framework is based on ace and can be compiled and run adaptively under windows and Linux.  
> the purpose of this service framework is to peel off the relationship between network io and logical developers as much as possible, so that the logical developers are more focused on their own business, and the network io is fully implemented by the configuration file.  
> operation and maintenance manager can through the auxiliary management tools, to obtain the framework operation status, work thread, data flow status, connection status and other information.  
> auxiliary operation and maintenance management, troubleshooting.  
> in addition, developers can also be completely out of the framework, using the tools around the framework, pressure test their logic module, so as to minimize the possible problems before online.  
> before using the framework, you can use the framework to provide small tools, pressure test performance indicators of the current framework, as a basis for whether to adopt.  
> example has a special test case, can provide a developer reference.  
> the goal of this framework is not just a network io plug-in interface, but a complete set of development process, as far as possible to reduce the developer 's pay.  
> specification development process ( currently available on the SVN framework testing tools, specific functions please refer to other instructions MD )  
> hope to be able to step by step with you to improve the system, really do a valuable framework. My goal is, you use cool, is to succeed. And I hope you like it more and more.  
> in addition, the latest code will be released on the SVN, if you have a SVN, it is best to download directly from the SVN, I will regularly play version package in download to provide download.  

## [How does the PSS framework compile](./md/English/Install.md) 
## [Pss framework configuration instructions](./md/English/Configure.md)
## [Pss logical plug - in use case description](./md/English/examples.md)
## [Pss Background commands instruction](./md/English/PSSFrameCommand.md) 
## [How to Data dyeing](./md/English/Dyeing.md)
## [How to develop a logical plugin](./md/English/LogicPlugin.md) 
## [How to develop a parsing plugin](./md/English/PacketParsePlugin.md) 

>##Provides several piezometric data ( TCP pass tool available from PSS open source kit ) 

* * *  
> ###Windows  
> Test PSS IP:172.21.1.200, Port:10002. (Windows7 x64 DEBUG）  
* Test IO protocal:TCP  
* Begin Time: 2013-09-18 11:07:42  
* End Time: 2013-09-18 12:06:00  
* Thread counts:10  
* connect counts:10  
* send package counts:11675202  
* recv package counts:11675202   
* connect fails:0  
* send fails:0  
* recv dails:0  
* connect success rote:100.000000%  
* send success rote:100.000000%  
* recv success rote:100.000000%  

* * * 
> ###Linux  
> Test PSS IP:172.21.1.68, port:10002.（Linux ContOS6 x64 DEBUG）
* Test IO protocal:TCP
* Begin Time:: 2013-09-16 09:55:58
* End Time: 2013-09-16 10:38:09
* Thread counts:10
* connect counts:10
* send package counts:11514132
* recv package counts:11514132
* connect fails:3125
* send fails:0
* recv dails:0
* connect success rote:100.000000%
* send success rote:100.000000%
* recv success rote:100.000000%

* * *

author:
freeeyes

thanks:
凹凸man,w1w,乔戈,Bobo,弄香花满衣,崔,kz

QQ group: 260862613

