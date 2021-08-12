# wmt_swm32_study
My SWM32 study  

## ref  
* https://gitee.com/pineconepi/PineconePi_ONE  
* https://shop550065076.taobao.com  
* https://github.com/PineconePi/PineconePi_ONE  
* https://www.synwit.cn/col.jsp?id=104  

## 点灯感想  
我把华芯微特的SWM320VET7-LQ100-32101最小系统板的GPIO例子跑通了，  
资料在synwit官网上有（不同系列提供不同的固件库，提供FLM算法用于J-Link烧录）。  
开发板类似ch32，键盘和LED灯是没焊死的，需要自己用杜邦线接。  
甚至电源的USB-TTL串口转换器的收发脚也是没焊死的。  
SWM32主打大屏幕LCD驱动，有兴趣可以了解，不过我暂时只研究简单外设驱动，  
LCD驱动问题暂时不会去研究（需要买另外的开发板接屏线）。  
另外网上除了官网的资料，还有一个很久以前的开源项目，叫松果派one，也是基于SWM32。  
另外，使用J-Link烧录（我用的是J-Link v9），需要接USB-TTL的电源，  
即需要两根USB线，否则keil4会找不到SWD设备  
