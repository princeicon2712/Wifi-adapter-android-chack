# Wifi-adapter-android-chack

how to check your Wi-Fi adaptor monitor mode packet injection and AP mode support or not [Android]

## Monitor mode type: 

sudo airmon-ng start wlan2

## Packet injection;

sudo aireplan-ng --test  wlan2

## AP mode support or Not ;

iw list | grep AP$

note: *AP Support 

## Blank Not support 

## AP mode working or Not;

airbase-ng -e 'test ap' -C 2 wlan2

>go your wifi setting and see a wifi the name is 'test ap'.. Have the name than you can sure to working AP.
