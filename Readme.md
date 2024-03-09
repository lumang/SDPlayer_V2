![image](https://github.com/lumang/SDPlayer_V2/assets/9112945/81d7443d-e2c6-4c42-8125-abf22849ad7f)# SDPlayer_V2
ESP32 SD-Player based on the Library ESP32-audioI2S. All music files of an SD card starting from a certain root directory are played recursively.  The encoder with button is used to control the volume and to jump to the next track or directory. When the unit is switched on or reset, it continues with the last track played at the set volume. In the event of a read error, the system continues with the next title.

# error 
```shell
begin() failed
Do not reformat the SD.
No card, wrong chip select pin, or wiring error?
SdError: 0X1,0X0
```
fix: replug sdcard 
