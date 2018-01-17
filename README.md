This is a device tree for BLU Iris X8 (MT6592) which is based on MT6592 SoC.
Based on Stock Kitkat kernel (3.4.67)


# Specifications:-
   * CPU	1.4GHz Octa-Core MT6592
   * Memory	2GB RAM
   * Android Version 4.4.2 & 5.1.1
   * Storage	16GB
   * Battery	2500 mAh
   * Display	5.0" 720 x 1280 DPI 320
   * Rear Camera	8MP
   * Front Camera	3MP


# Working
  * Dual SIM
  * Wifi
  * VPN
  * Bluetooth
  * Audio
  * Sensors
  * Camera (photo and video recording)
  * GPS
  * Screen Record
  * HD games
  * Tethering (Wifi, Bluetooth and USB)



# Build

  * repo init -u git://github.com/LineageOS/android.git -b cm-13.0
  * repo sync
  * git clone https://github.com/SamarV-121/android_device_BLU_Studio_X8_HD.git -b cm-13.0 device/BLU/Studio_X8_HD
  * git clone https://github.com/SamarV-121/proprietary_vendor_BLU.git -b cm-13.0 vendor/BLU
  * cd device/BLU/Studio_X8_HD/patches
  * source apply.sh 
  * source build/envsetup.sh
  * brunch iris_x8
  * Done :)
  
  # Credits/Thanks to:-
  * Fire855 
  * Axet
  * chrmhoffmann
  * DerTeufel1980
  * Al3XKOoL
  * xen0n
  * kashifmin
  * Santhosh M
  * ariafan
  * hyperion70
  * tribetmen
  * CyanogenMod Team
  * Tirth Patel
  * Kishan Patel
  * Yazad Madan 
  * & Me :)
