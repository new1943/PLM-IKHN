# PLM-IKHN
Integration of KNX into HomeKit through Node-RED.
1. docker部署nodered，注意要host网络
   ![image](https://github.com/new1943/PLM-IKHN/blob/main/IMG/img_1.png)
2. 安装node-red-contrib-homekit-bridged和node-red-contrib-knx-ultimate插件
   ![image](https://github.com/new1943/PLM-IKHN/blob/main/IMG/img.png)
4. 导入相应的json
   ![image](https://github.com/new1943/PLM-IKHN/blob/main/IMG/WechatIMG1448.jpg)
6. 编辑KNX Gateway地址  
   ![image](https://github.com/new1943/PLM-IKHN/blob/main/IMG/WechatIMG1449.jpg)
   ![image](https://github.com/new1943/PLM-IKHN/blob/main/IMG/img_3.png)
7. 根据https://github.com/jerry-jho/PLMDeepSmart 项目中找出自己户型房间的KNX地址，按设备更改添加删除
8. Homekit中添加birdge
   ![image](https://github.com/new1943/PLM-IKHN/blob/main/IMG/img_4.png)
   ![image](https://github.com/new1943/PLM-IKHN/blob/main/IMG/img_5.png)
9. enjoy～


PS: 相比ha里的knx，能状态同步了，空调能显示温度，窗帘面板也能同步，需要的自取，改起来也不复杂，有兴趣的邻居一起维护开源。
