# RITOS

Real Internet Time Operation System (RITOS). An Esp8266 RTOS library of the esp8266 core for Arduino IDE.


即時互聯網時間操作系統（RITOS）。 一個基於Arduino IDE的Esp8266內核的Esp8266 RTOS庫。

————————————————

## Please download.zip and import

## 請下載.zip並導入

Arduino IDE

PlatformIO

Adapt for ( esp8266, esp8266-12f, esp8266-12e, esp01, esp01s )

適用於 ( esp8266, esp8266-12f, esp8266-12e, esp01, esp01s )

Add the source download esp8266 development board : 

http://arduino.esp8266.com/stable/package_esp8266com_index.json

新增該源下載esp8266開發板：

http://arduino.esp8266.com/stable/package_esp8266com_index.json

————————————————

Use RITOS Note the main points:

1. Declare the Ritos class before creating the thread

The format is: Ritos class name;

2. Create a thread in the following format: class name task(function name);

3. The delay() delay function cannot be used in the thread, because RITOS and delay() delay function call the same timer. If you want to use the delay function in the thread, please refer to Demo (RITOS-esp8266./examples/RITOSbasic/RITOSbasic.ino)


使用RITOS注意要點：

1. 建立線程前要先聲明Ritos的類

2. 格式為： Ritos 類名;

2.創建線程格式為：類名.task（函數名）;

3.在線程內無法使用delay（）延時函數，因為RITOS與delay（）延時函數調用的是同一個定時器，如果想要在線程內使用延時函數，請參考Demo (RITOS-esp8266./examples/RITOSbasic/RITOSbasic.ino)

————————————————

Thanks 鳴謝 :

Original Author : SanUSB grupo <http://sanusb.org/>

Github url : https://github.com/SanUSB-grupo/RITOS

Original Project Link : https://github.com/SanUSB-grupo/RITOS

————————————————

修改和打包

Fix & Pack by 0. Chun   <- a Runoob 一隻菜鳥
