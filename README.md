# FaceSignDemo
基于讯飞的人脸识别功能。可注册，可人脸校验登录

可以自己输入auth_id（在本项目中是用textfield输入），auth_id用来帮助区分不同的用户，可以是自身项目中服务端数据的id

也可以是这个项目当做签到使用，效果不错
在基础的签到登录人脸识别之上我又新加了一个功能--检索人脸功能，不去调用系统相机，在自己的相机中可以看到你的五官轮廓，
可以检测用户的面部是否居中，并让用户做出相应调整，

但是这个功能一定要先在appdelegate中执行配置方法
- (void)makeConfiguration
