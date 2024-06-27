
# 大气层九夏整合包自动构建
- 本整合包永久开源免费，禁止任何人二次贩卖本整合包
- 特斯拉菜单按键：L+↓，hbmenu插件菜单按键：直接点击相册
- 整合包二改定制@huangqian8脚本后打包而成，加入了一些原有脚本未包含的内容并且会持续更新
- 整合包自动构建，请下载最新release使用。所有大气层相关组件与插件自动同步上游最新版本，构建过程全公开不夹带私货，安全放心开箱即用
## 免责声明
本站所发布的一切补丁、整合包及插件仅限用于学习和研究目的；不得将上述内容用于商业或者非法用途，否则，一切后果请用户自负。整合包所包含的内容均来源于网络收集整理，版权争议与本站无关。您必须在下载后的24个小时之内，从您的电脑中彻底删除上述内容。如果您喜欢，请支持正版软件，购买注册，得到更好的正版服务。如有侵权请与我们联系处理。
## 更新日志
- 2024-04-01
  
  更新月光串流 熔断补丁 图标包和中文引导 (@naixue233)
  
  更新AIO-Toolbox 0.1.1 (@JiuXia2025)
- 2024-03-31 添加SxGear的boot.dat，修复软破机无法启动的问题
- 2024-03-30 将Atmosphere更换为AtmosphereNX的最新构建，恢复Sys-clk-OC原仓库的下载源
- 2024-03-28

  添加 AIO-Toolbox 多合一实用工具

  替换 UltraPaw 为 Ultrahand 菜单
  
  增加 脚本环境初始化模块
- 2024-03-27

  替换 Tesla-Menu 为 UltraPaw 菜单
  
  添加 OC-Toolkit 极限超频插件
  
  添加 Ultra Tuner 极限超频插件
  
  添加 Cool Curves 风扇调整插件
  
  添加 Broomstick Mod 插件管理器
  
  更新 Tesla ovl插件包
  
  更换 Atmosphere 仓库为 [Atmosphere-NX/Atmosphere](https://github.com/Atmosphere-NX/Atmosphere)
- 2024-02-16
  删除 色彩调节 插件
  
  删除 内存测试 插件
  
  删除 AIO Updater nro插件
  
  汉化 QuickNTP 插件
  
  添加 Goldleaf 插件
  
  调整 仓库文件结构 ，部分资源本地化
- 2024-02-05 
  添加 Switchfin nro插件
  
  添加 SimpleModDownloader nro插件
  
  更换 Atmosphere 仓库为 [borntohonk/Atmosphere](https://github.com/borntohonk/Atmosphere)
- 2024-01-27
  添加 HB-Appstore-v2.3.2 nro插件
  
  添加 Tinfoil-17v3 nro插件
  
  添加 Wiliwili-v1.3.0 nro插件
  
  添加 warmboot_mariko 忽略熔断补丁
  
  更新 SigPatchers 最新版本，提高兼容性
  
  更新 品技Z大最新版本特斯拉插件整合包
  
  修改 菜单入口，特斯拉菜单按键：L+↓，hbmenu插件菜单按键：直接点击相册
  
- 2024-01-14 添加 picofly-toolbox 树莓派芯片工具箱插件
- 2024-01-13 添加 DBI 中文汉化配置
- 2024-01-12 

  添加 Hekate 安卓系统启动引导，位于hetake首页-更多设置中
  
  添加 Hekate 引导图标与启动图资源，添加hbmenu.nsp
  
  添加 hwfly-toolbox 国产芯片工具箱插件
- 2024-01-11 添加 Hekate + Nyx繁简汉化版 仓库链接
- 以下为旧更新日志 （From @huangqian8）
- 2024-01-09 更新 Tesla3 仓库链接
- 2023-12-15 更新 Lockpick_RCM 仓库链接
- 2023-12-04 删除 Safe_Reboot_Shutdown.nro 插件，添加3个 Ovl 插件
- 2023-12-03 添加 Atmosphere-OC-Suite 插件
- 2023-11-25 添加 SwitchTime 插件
- 2023-11-09 更新 Lockpick_RCM 仓库链接
- 2023-10-13 更新脚本，修正 SigPatches 链接更新造成的运行错误；新增2个Nro插件
- 2023-05-11 更新脚本，修正 Lockpick_RCM 仓库失效造成的运行错误；每天16点定时生成整合包
- 2023-05-04 更新脚本
- 2023-04-28 更新脚本，自动生成 Release 内容
- 2023-04-27 添加 Github Action 自动打包代码

整合包内包含的内容详见 `release` 页面

## 手动构建:
  - 运行switchScript.sh脚本，支持Windows/macOS/Linux

## 安装整合包（与其他整合包的安装方法一致）:
  - 删除原有大气层整合包相关文件夹
  - 下载本仓库release页面最新构建中的SwitchSD.zip并解压至内存卡目录
