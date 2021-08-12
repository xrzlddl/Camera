1.使用前 先使用文本编辑器(推荐使用VIM) 编辑该脚本  修改 IP  用户名  密码  存储位置等,运行方法 ./camera1 &  
2.支持同时采集多个监控   需要采集多个监控头时 将本程序 复制多个 如 camera1 camera2 camera3 然后在分别修改 头部配置信息即可.
3.如需开机运行执行  需要将本程序 加入到 /etc/rc.local中去 (切记需加 & ) 不然会阻塞其他自启项目

4.本程序依赖 nc  ffmpeg 程序
  使用前
  centos（需要EPEL源）  执行 
  yum install ffmpeg nc -y

  debian 执行
  apt install nc ffmpeg -y 

在玩客云中armdebian 通过
在Centos7中通过

理论上通用 

更新时间:2021年8月12日 于 临泉 天气:晴
