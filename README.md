## Description：
这是一个基于pyqt的gui客户端程序，主要用来展示人脸属性识别的结果。目前调用了face++旷视公司的接口，此后会改造成，调用自己队伍训练结果的接口。

## Project structure:
├─.idea  
├─dist   放置发行版  
├─docs   放置说明文档，在此项目无实际作用  
├─examples  放置样例，放置运行结果的picture
├─extras   放置额外文件，在此项目无实际作用   
├─faceA  
│  ├─.idea  
│  ├─logs  放置log文件  
│  ├─resource  放置静态资源文件     
│  └─ui       ui模块    
│      ├─ui_base   放置 qt designer的布局文件   
│      ├─ui_source 放置qtuic自动生成的文件  
├─scripts  放置可执行文件   
└─tests    放置测试样例  

  为了避免项目更加复杂，减去了一些目录模板，但是为了以后的项目架构，做出说明（这个项目README简直就是给我以后自己看的，逃）

## 目录额外说明：
不需要network目录 因为没有复杂的网络操作  
不需要dba目录，因为没有数据库。  
不需要examples。因为这里不是库，本身具有程序实现，不需要例子   
dist是发行版的文件夹  


## The Docs Link:
[TODOLIST](https://github.com/ThomasRaymond/faceA/blob/master/docs/todolist)

## How to install：
need the python version>3.0  
and then  
pip install -r requirements.txt  
Last,cd the faceA/faceA  
python main.py  

## How to use：
you can upload your pic which you want to get the information about.  
and then the program will show you the result after click the button.  
the result will just like  
[Example:Lenna.png](https://github.com/ThomasRaymond/faceA/blob/master/examples/testpic.png)


