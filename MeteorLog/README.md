

# 解决iron:router出现organize your Meteor application
  
  app出现状态如图所示：

![iron](https://github.com/yanglong2/developLog/MeteorLog/img/Screenshot_2016-01-04-11-43-50_com.biku.dorasdrea.png)
  
  解决方案：
       * 确认加入了iron:router包
       * 切换server端，具体原因是它找不到服务端，即使在网页版能访问到，但是app是找不到server端的
