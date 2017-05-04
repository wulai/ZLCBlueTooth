## ZLCBlueTooth

### iOS与蓝牙交互demo


使用方式：   

1，首页为已链接设备列表，进入app后点击右上角‘scan’按钮进行设备扫描，成功扫描到设备后改设备将显示在首页   

2，点击设备后进行设备连接并进入设备详情描述页面   

3，在蓝牙设备详情页面会详细显示该设备的服务及特征信息（udid及权限）   

4，在蓝牙设备详情页面下部会有三个输入框及两个操作按钮。三个输入框从上至下可输入服务的udid、特征的udid、及想要发送的指令内容。按钮由上至下分别为写入和读取按钮。   

备注：每一个蓝牙设备会有很多服务，每个服务又有很多特征（说属性也罢），故与蓝牙设备进行交互时，需根据蓝牙设备的udid进行通信，为此在详情页拿到所有的udid信息以方便选择（直接点击会自动填充），至于发送的指令内容及需要向哪一个udid发送内容则需与蓝牙设备的开发者进行约定。   

![scan.png](http://upload-images.jianshu.io/upload_images/2312430-796c833c1566d2e4.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![detail.png](http://upload-images.jianshu.io/upload_images/2312430-b8f78d4fe29befa1.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

