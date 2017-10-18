#项目初始化安装
***
##1、安装所需要的包
`npm install`

##2、运行指令
`npm run dev`

##3、预览效果
输入网址：<br>
   http://localhost:8888/
   
效果如下：<br>
   ![Image text](https://github.com/duanliang920/webpack-website/blob/master/dev.jpg)

##4、编译打包
`npm run build`
 
##打包文件目录mac 跟window不同配置 
var itemName  = pathname.split('src/') //根据系统路径来取文件名，MAC下的做法\
var itemName  = pathname.split('src\\') //根据系统路径来取文件名，window下的做法//


