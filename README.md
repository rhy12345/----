# -小米手机改串

### 仅限高通骁龙865处理器以下有效
## 方法一
   重要提示：刷机改串号会带来风险，包括不限于成砖头，那就需要去售后换主板，售后换主板是收费的！很贵！自己做好承担此风险的准备！自己做好承担此风险的准备！自己做好承担此风险的准备！

1、解BL锁（因为要刷第三方系统），别问我怎么解，这步都不会，就不要看下面的了

2、去https://sourceforge.net/projects/xiaomi-eu-multilang-miui-roms/files/xiaomi.eu/MIUI-STABLE-RELEASES/MIUIv13/这个网址寻找符合你手机型号的miui系统，没有就别折腾了。

3、如果下载的包是卡刷包，优先寻找支持你机型的TWRP的recovery文件，如果没有TWRP，奇兔助手的版本也可以，利用recovery刷入第二步下载的系统包

4、如果下载的包结尾是fastboot，说明是线刷包，直接手机进入fastboot模式，然后运行包里面的windows_fastboot_first_install_with_data_format.bat这个，出来选项，输入Y回车，就开始跑刷机了，刷完会自动重启手机，全程保持链接别动它！

5、新系统开机后激活，不要连接wifi、也不要插卡，快速设置完激活界面，进入系统，安装“创建快捷方式”这个app（百度可以找到），安装方式推荐下载到电脑后，手机通过USB连接电脑，讲安装包拷贝进手机。

6、打开创建快捷方式，点击右上角三个点，选中“也显示系统应用”，然后搜索鲁班（MTB）（这步骤如果搜索不到，说明包刷的不对，回到第二步，重新找个包刷试试）7、打开鲁班（MTB），选择nv/efs配置管理工具，搜索框内搜索550，选择后面是bcd的，选择卡1，点默认值，下面ue imei会变成864376026015007，点写。选择卡2，下面ue imei改成你想要的串号，点写，最后点重启8、能正常进入系统，就淡定点了，这时候基本是成功了，拨号键盘输入*#06#，看看卡2的新imei是不是写好了，卡1统一为864376026015007，不可更改其他，改了会导致卡2更改失效。重要提示：刷机改串号会带来风险，包括不限于成砖头，那就需要去售后换主板，售后换主板是收费的！很贵！自己做好承担此风险的准备！自己做好承担此风险的准备！自己做好承担此风险的准备！

## 方法二
 利用lsposed框架 使用ModemPro模块提权 利用系统自带mtb（鲁班）修改 
 小白详见 哔哩哔哩视频--> https://www.bilibili.com/video/BV1W54y1w7En/
 
 ## 已测试机型
   Xiaomi 10     xiaomi 10青春版（可改双串）         Redmi k30pro 
 
