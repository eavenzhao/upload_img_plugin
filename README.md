上传图片插件
使用requirejs,hammerjs
本插件支持图片定制尺寸的裁剪，放大，缩小旋转，修正了ios图片旋转bug。

界面仿微信上传头像
说明:Introduction:
adjustImg.html:裁剪一个已有的图片
adjustImg_file.html:上传手机相册图片裁剪

##v1.0.3 由于自由旋转裁剪算法有问题，暂时屏蔽手势旋转。
##v1.0.4 支持图片直接裁剪
##v1.0.5 恢复自由旋转：极坐标算法。
##v1.0.6 判断图片是否要修正角度改写,当orientation不为1时才去修正。
##v1.0.7 修复绑定imgSrc图片地址字符串时传值错误。