##Cwm-recovery中文源码

作者：[Xs](http://www.weibo.com/acexs)

源码说明

1、采用Ruby生成字库方法汉化

2、针对MTK进行了部分修改
```
* 修改mmcutils.c 支持MTK备份“其它平台请注释掉MTK相关”

* 添加MTK USB挂载代码以支持MTK平台USB挂载模式
```

3、中文字库调用要在Device里添加`BOARD_USE_CUSTOM_RECOVERY_FONT := \"fontcn_15x24.h\"`来调用中文字库

4、中文显示要在Device里添加`BOARD_RECOVERY_LANG_CHINESE := true`来显示中文界面
