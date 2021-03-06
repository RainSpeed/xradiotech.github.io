
![](../../images/XRADIOTECHLOGO.png)

[[English]](index-en.md)

# 工具软件

| 工具 | 版本号 | 说明 | 链接 |
| ---- | ---- | ---- | ---- |
|phoenixMC|v3.1.0218a|工具简介：烧录工具，用于镜像文件的烧录<br><br>更新说明：<br>1、修复烧写单个bin文件时，会有数据丢失的问题。<br>2、烧写单个bin文件时，同时更新OTA区域<br><br>参考文档：[《XRADIO_PhoenixMC_Tool_User_Guide-CN》](../../download/4.SDK/document/XRADIO_PhoenixMC_Tool_User_Guide-CN.pdf)|[zip](../../download/4.SDK/tools/xradio_phoenixMC_v3.1.0218a.zip)|
|pack_tool|v1.23a|工具简介：打包工具，用于编译后进行镜像打包<br><br>更新说明:<br>1、增加合并固件的母片烧录所需要的裸固件生成功能<br><br>参考文档： N/A|[zip](../../download/4.SDK/tools/xradio_pack_tool_v1.23a.zip)|
|efuse_tool|v2.0.0930-p1|工具简介：efuse工具，用于读取写入efuse区域的数据<br><br>更新说明：<br>1、增加 HOSC/POUT CAL/SCR BOOT/CHIP ID/USER AREA 等区域的读写<br>2、增加帮助信息<br><br>参考文档：[《XRADIO_Efuse_Tool_User_Guide-CN》](../../download/4.SDK/document/XRADIO_Efuse_Tool_User_Guide-CN.pdf)|[zip](../../download/5.生产测试/xradio_efuse_tool_v2.0.0930-p1.zip)|
|sdd_editor_ex|v2.5.191212a|工具简介：SDD文件编辑工具，可修改SDD文件中的晶振频率、频偏、发射功率等设置<br><br>更新说明：N/A <br><br>参考文档：N/A|[zip](../../download/4.SDK/tools/xradio_sdd_editor_ex_v2.5.191212a.zip)|
|etf_tool|v1.0.8f|工具简介：RF测试工具包，用于RF性能测试及优化<br><br>更新说明：<br>1、ETF GUI Tools更新至v1.0.8f<br>a) 增加波特率选择<br>b) 修复1.5M波特率下connect失败的问题<br><br>2、ETF image更新至1.0.0-rel-20200302<br><br>参考文档：[《XRADIO_RF测试开发指导》](../../download/2.产品指导/XRADIO_RF测试开发指导_V1.0.pdf)|[zip](../../download/2.产品指导/xradio_etf_tool_v1.0.8f.zip)|
|Smart Config|v1.1.1v|工具简介：WLAN配网工具，通过WLAN信号完成配网信息传递<br><br>更新说明：<br>1、修复Android 6.0以上版本获取不到channel的问题<br>2、优化按键响应流程<br><br>参考文档：[《XRADIO_SmartConfig_Tool_User_Guide-CN》](../../download/4.SDK/document/XRADIO_SmartConfig_Tool_User_Guide-CN.pdf)|[zip](../../download/4.SDK/tools/xradio_smart_config_tool_v1.1.1v.zip)|
|Sound Config|v1.1.2s|工具简介：WLAN配网工具，通过声纹信号完成配网信息传递<br><br>更新说明：<br>1、修改默认不保存pcm数据，可通过menu菜单打开或关闭保存pcm数据功能<br><br>参考文档：[《XRADIO_SoundConfig_Tool_User_Guide-CN》](../../download/4.SDK/document/XRADIO_SoundConfig_Tool_User_Guide-CN.pdf)|[zip](../../download/4.SDK/tools/xradio_sound_config_tool_v1.1.2s.zip)|
|AirKiss|-|工具简介：WLAN配网工具，微信提供的配网工具，可在微信官网获取官方APK工具软件<br><br>参考文档：[《XRADIO_AirKiss_Tool_User_Guide-CN》](../../download/4.SDK/document/XRADIO_AirKiss_Tool_User_Guide-CN.pdf)|-|

----

# 固件镜像

## XR872

| 镜像 |版本号|说明 |链接|
| ---- | ---- | ---- | ---- |
| WLAN演示 |1.0.2|1.名称：xr872_wlan_demo.img<br>2.工程：基于project/demo/wlan_demo演示工程<br>3.评估板：<br>a) XR872AT_MD01 + XR872_EVB_AI<br>b) XR872AT_MD01 + XR872_EVB_IO| [下载](../../download/4.SDK/tools/xr872_wlan_demo_v1.0.2.img)|
| 音频演示 |1.0.2|1.名称：xr872_audio_demo.img<br>2.工程：基于project/demo/audio_demo演示工程<br>3.评估板：XR872AT_MD01 + XR872_EVB_AI| [下载](../../download/4.SDK/tools/xr872_audio_demo_v1.0.2.img)|
| WLAN功耗测试 |1.0.2|1.名称：xr872_wlan_power_test.img<br>2.工程：基于project/demo/wlan_demo演示工程<br>a) CPU频率改为160MHz<br>b) 启用外部32KHz低频晶振<br>3.评估板：XR872AT_MD01 + XR872_EVB_IO| [下载](../../download/4.SDK/tools/xr872_wlan_power_test_v1.0.2.img)|

## XR808

| 镜像 |版本号|说明 |链接|
| ---- | ---- | ---- | ---- |
| WLAN演示 |1.0.2|1.名称：xr808_wlan_demo.img<br>2.工程：基于project/demo/wlan_demo演示工程<br>3.评估板：<br>a) XR808CT0_MD01 + XR808_EVB_IO<br>b) XR808CT0_MD02 + XR808_EVB_IO| [下载](../../download/4.SDK/tools/xr808_wlan_demo_v1.0.2.img)|
| WLAN功耗测试 |1.0.2|1.名称：xr808_wlan_power_test.img<br>2.工程：基于project/demo/wlan_demo演示工程<br>a) 启用外部32KHz低频晶振<br>3.评估板：XR808CT0_MD02 + XR808_EVB_IO| [下载](../../download/4.SDK/tools/xr808_wlan_power_test_v1.0.2.img)|
| 冷启动快连 |1.0.2|1.名称：xr808_wlan_cold_start_fast_connection.img<br>2.工程：基于project/example/cold_start_fast_connection示例工程<br>3.评估板：<br>a) XR808CT0_MD01 + XR808_EVB_IO<br>b) XR808CT0_MD02 + XR808_EVB_IO| [下载](../../download/4.SDK/tools/xr808_wlan_cold_start_fast_connection_v1.0.2.img)|
