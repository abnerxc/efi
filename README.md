# 微星B460M+10700+RX5500xt
> 申明：配置并非本人原创，本人也是初学者，全部配置文件收集于远景论坛

## 硬件配置

|  配置   | 型号  |
|  ----  | ----  |
| CPU  | I7-10700 |
| 主板  | B460M 迫击炮 |
| 内存  | 海盗船3000 16G*2 |
| 固态1  | 海康C2000PRO 1T(macos)  |
| 固态2  | 金士顿A2000 512G(windows)  |
| 显卡  | 蓝宝石RX5500XT 8g 超白金  |
| wifi  | FV-T919 bcm94360cd  |
| 电源  | 长城金牌全模组650W  |


## 主板配置
主板版本 7C82v11 更新主板BISO ：https://cn.msi.com/Motherboard/support/MAG-B460M-MORTAR#down-bios

- Fast Boot：关闭
- Secure Boot：关闭（默认关闭的）
- CFG lock 关闭（重要）
- Intel SGX 如果有，关闭，默认关闭的
- VT-x 开启
- Above 4G decoding 开启（重要）
- Hyper-Threading 开启（默认都开的）
- EHCI/XHCI Hand-off 开启 默认都开的）
- 显存: 64MB

# win和mac双系统时间不一致问题
win修改注册表
```shell
Reg add HKLM\SYSTEM\CurrentControlSet\Control\TimeZoneInformation /v RealTimeIsUniversal /t REG_DWORD /d 1
```

## GeekBench 跑分
![显卡跑分](http://ww1.sinaimg.cn/large/007lnJOlgy1ggjxexjn7kj30o10f0q46.jpg)
![CPU跑分](http://ww1.sinaimg.cn/large/007lnJOlgy1ggjxex385fj30nr0ebwfp.jpg)


## 系统预览
![概览](http://ww1.sinaimg.cn/large/007lnJOlgy1ggjxcm2htij30he0apdin.jpg)
![电源](http://ww1.sinaimg.cn/large/007lnJOlgy1ggjxclxuqsj30l40egq5l.jpg)
![核显加速](http://ww1.sinaimg.cn/large/007lnJOlgy1ggjxclzlujj30oo0gfq5l.jpg)
![显卡](http://ww1.sinaimg.cn/large/007lnJOlgy1ggjxcm00alj30me0evwhw.jpg)
![airdrop](http://ww1.sinaimg.cn/large/007lnJOlgy1ggjxcm3s4fj30le0c442q.jpg)
![imessage](http://ww1.sinaimg.cn/large/007lnJOlgy1ggjxcm2fvwj30k50ebn27.jpg)
![USB](http://ww1.sinaimg.cn/large/007lnJOlgy1ggjxcm8m0ej30kx0f1tbe.jpg)

