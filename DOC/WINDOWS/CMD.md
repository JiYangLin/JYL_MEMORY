# CMD

## path
path=%path%;C:\XXX

## help

+ help   **  
  显示所有命令的帮助文档

+ 命令   /?  
  显示命令的帮助文档
  
## type

+ type 1.txt  
  将文本文件内容显示出来

## echo

+ echo ***  
  显示内容***
+ echo off  
  在此语句后所有运行的命令都不显示命令行本身
+ echo *** >> 1.txt  
  将内容写入txt

## dir
 
+ /w  
  宽屏显示，一排显示5个文件名，而不会显示修改时间，文件大小等信息
+ /p  
  分页显示，在当前屏最后有一个“press any key to continue . . .”提示，表示按任意键继续。
+ /a
  显示具有特殊属性的文件
+ /s
  显示当前目录及其子目录下所有的文件

## cd

+ cd 路径  
 cd命令只能进入当前盘符中的目录，其中“cd\”为返回到根目录，“cd..”为返回到上一层目录

## md/mkdir

+ md   abc\def  
  在当前目录下建立abc并在下面建立def 

## rd  

+ rd  temp
 表示删除当前路径下的temp目录，此命令只能删除空目录

+ rd temp  /s  /q 	/s可以删除非空目录，/q代表不需要选择确定

## del  

+ del  *.dat  
  删除当前目录下所有扩展名为.dat的文件

+ del  *.dat  /s /f  /q  
  可以删除包括子目录下的文件以及只读文件

## copy	

+ copy c:\*.com   d:\  
  表示将c盘根目录下所有扩展名为com的文件拷贝到d盘根目录中

+ copy *.txt  ret.txt  
  将当前目录下所有txt内容放到ret.txt中

## xcopy  

+ xcopy /s  /q  /y /d  c:\abc d:  
  执行此命令后，将把c:\abc目录及其目录中的文件全部拷贝到d盘根目录下。/s对一个目录下的所有子目录进行拷贝。/y覆盖不进行提示选择。/q 文件覆盖时不提示。/d  只复制比当前文件新的（data）

## ren

+ ren *.txt *.csv  

## format

+ format D:  /s /q  
  此命令将格式化D盘，/q表示进行快速格式化，/s表示完成格式化后将系统引导文件拷贝到该磁盘，这样软件就可以作为dos系统启动盘了。格式化过程中，屏幕上会显示已经完成的百分比。格式化完成后，会提示为磁盘起    一个名字，最后还会报告磁盘的总空间和可利用空间等。 

## &  

+ echo abc  & echo def  
  让两条命令可以写一行


