react-native

初始化项目的方式:
  1. react-native init projectName
  2. create-react-native-app project app
  第一种是在开发wewee的时候使用的方式,本次开发使用第二种形式
  PS:第一种方法要求的开发环境比较繁杂，需要 node / watchman / jdk / android sdk,android studio / xcode 等等。第二种可以摆脱android studio 和 xcode ，只要在手机上安装expo client就可以开发, 当然你也可以在android studio 和 xcode 查看项目效果

#create-react-native-app脚手架的使用:
  #全局安装 npm install -g create-react-native-app 
  #初始化项目 create-react-native-app program-name 
  #进入项目目录 cd program-name 
  #启动项目服务 npm start 

#create-react-native-app常用命令
  1. npm start  #启动本地开发服务器，这样一来你就可以通过Expo扫码将APP运行起来了
  2. npm run ios   #将APP运行在iOS设备上，仅仅Mac系统支持，且需要安装Xcode
  3. npm run android  #将APP运行在Android设备上，需要Android构建工具
  4. npm test # 运行测试用例
