# 机器人主控制器A6 Series  
![主视图](https://github.com/MarkChen99/MainCtrl-A6/blob/main/3.Image/A6%20Pro%20Default%20View.PNG)

## 版本差异  
- 设计理念变更：主控放置点由机器人云台改为机器人底盘  
- 设计理念变更：主控分为基础版、升级版  
- 设计方案变更：板层由两层改为四层  
- 设计方案变更：防止插接件松动，SWD及UART调试集成为Type-C接口，线序自定  

|MODEL|A3|A6 Pro|
|:---:|:---:|:---:|
|MCU|STM32F405RGT6|STM32F767VIH6|
|FREQUENCY|MAX 168MHz|MAX 216MHz|
|FLASH SIZE|1024kB|2048kB|
|RAM TOTAL|192kB|512kB|
|SWD|USBType-C|USBType-C|
|IIC|1|2|
|CAN 2.0B|2|3|
|PWM|1|8|
|LED|2|4|
|UART|6|8|
|USER KEY|√|√|
|MICRO SD|×|√|
|ADJ OUTPUT|×|√|
|POWER MONITOR|×|√|
## 电气参数  
|PARA|DSCP|MIN|TYP|MAX|UNITS|
|:---:|:---:|:---:|:---:|:---:|:---:|
|Vin|Power Input Voltage|12.0|24.0|28.0|V|
|Iin|Power Input Current|||15.0|A|
|Vout1/2|Output Voltage 1/2|Vin-0.1|Vin|Vin|V|
|Iout1/2|Output Current 1/2|||15.0|A|
|Vadj|Adjust Output Voltage|5.0|5.0|12.2|V|
|Iadj|Adjust Output Current|||8.0|A|
|Iout(5V)|Output Current in 5V|||3.0|A|
|Iout(3V3)|Output Current in 3V3|||1.5|A|

These PARA only fit module A6 Pro.  
## 辅助模块 
- __[STLINK调试下载器](https://github.com/MarkChen99/Debugger-Insight)__  
## 资料 
- __[HI22X系列IMU资料](https://www.hipnuc.com/contact.html)__  
- __[Readme说明文档](https://github.com/MarkChen99/MainCtrl-A6/tree/main/5.Readme)__  
## 注意事项 
*近年来现货元器件货源极其不稳定，TB购买的芯片很多都是翻新、假货*  
*如需更换元器件请从正规代理商渠道购买！！！*  
*本项目仅用作学习交流，请遵循相关开源协议！*  
