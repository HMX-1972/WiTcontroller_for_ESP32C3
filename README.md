# WiTcontroller for ESP32C3

I modified Mr Peter Akers' WiTcontroller so that it can be used with ESP32C3.
I should express my respect for his great accomplishment.
I'm new to forking on GIthub.
I would be very grateful if you could point out any mistakes.

Mr Peter AkersさんのWiTcontrollerをESP32C3で使えるように修正しました。
彼の偉大な功績に感謝しています。
私はGitHubでフォークをするのは初めてです。
なにか誤りがあれば、指摘して頂けると大変助かります。

<h2>Basic Note</h2>
This project deals with two types of devices: <BR>
OLED Display 0.96" 128x64 Blue I2C IIC SSD1306 <BR>
and<BR> 
TFT LCD Display 1.44-inch 128x128 ST7735<BR>
For the latter, please refer to the branch.<BR> 
https://github.com/HMX-1972/WiTcontroller_for_ESP32C3/blob/ST7735-128x128-TFT/
<BR>
For operation instructions and menu expansion, please refer to the original URL below.<BR>
https://github.com/flash62au/WiTcontroller<BR>
<BR>
このプロジェクトでは<BR>
OLED Display 0.96" 128x64 Blue I2C IIC SSD1306<BR>
と<BR>
TFT LCD Display　1.44-inch 128x128 ST7735<BR>
の2種類を扱っています。<BR>
後者はbranchを参照してください。<BR>
https://github.com/HMX-1972/WiTcontroller_for_ESP32C3/blob/ST7735-128x128-TFT/
<BR>
操作方法やメニューの拡張などはオリジナルである次のURLを参照ください<BR>
https://github.com/flash62au/WiTcontroller<BR>
<BR>

<h2>Difference</h2>
* ESP32C3 *<BR>
Compared to ESP32, it has the following limitations:<BR>
- Not scalable due to limited number of I/Os.<BR>
- Returning from sleep requires turning the power back on.<BR>
* ST7735 *<BR>
There are some limitations compared to the 128x64 SSD1306:<BR>
- The LED power on the ST7735 cannot be turned off, so you must turn it off manually.<BR>
<BR>
* ESP32C3 *<BR>
ESP32とに比較として次の制限があります。<BR>
- I/Oの数が限定されるために拡張性がありません。<BR>
- スリープからの復帰には電源の再投入が必要です。<BR>
* ST7735 *<BR>
128x64 SSD1306と比較して次の制限があります。<BR>
- ST7735のLED電源はきれません。つまり手動でOFFしてください。<BR>

<h2>Hardware</h2>
have created several Wifi Throttles so far.<BR>
I have made this compatible with three of them.<BR>
<BR>
私はこれまでに複数のWifi Throttleを作成してきました。<BR>
そのうちの３種類に対応させています。<BR> <BR>



*Photo01 P004*
![Photo](HMX_P004_Photo01.jpg)

*Photo02 P008*
![Photo](HMX_P008_Photo01.jpg)

*Photo03 Diagram*
![Wire Drawing](HMX_P004_DWG.jpg)

*Photo04 P026*
![Photo](HMX_P026_Photo01.jpg)

*Photo05 Diagram*
![Wire Drawing](HMX_P026_DWG.jpg)

### V1.45
- Diverged from the original

### prior 
- various
