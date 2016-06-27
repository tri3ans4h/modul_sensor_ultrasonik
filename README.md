# waterlevelclient

Modul A
Modul ini di gunakan pada sisi client

Rencana Hardware:
- arduino nano v3
- esp8266 v01
- sensor ultrasonik SHR-04
- battery lithium 3000 mAH 3.7 volt(Gunakan battery tablet)
- Boost StepUpConverter DC to DC 

Rencana Software :
- Esp8266 Client connect to router 
- Esp8266 wait data request from modul B



Konfigurasi PinOut

Arduino Nano    ------------------ Esp8266 --------------------BATTERY
PIN 11(digital) ------------------ TRX     --------------------
PIN 12(digital)         RCV
                        GND           ->      GND     
                        VCC           ->      VCC       
      
