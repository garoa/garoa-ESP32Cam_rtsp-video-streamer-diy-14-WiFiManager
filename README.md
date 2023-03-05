# garoa-ESP32Cam_rtsp-video-streamer-diy-14-WiFiManager
ESP32Cam com RTSP para DVR do Garoa - WiFi set com WiFi Manager
baseado no excelente código diy14
 - adiconado WDT pois travava :'-( streaming após algum tempo ligado direto 
 - adicionado WiFi Manager
 - Leds de Status
   LED_GREEN -> Operando
   LED_RED piscando -> conectado enviando streaming por rtsp
   
Uso:

 - Para configurar WiFi / nova rede, conecte-se ao Acces Point "ESP32Cam" e configure user/pass rede WiFi
 - para ver streaming pelo software VLC, ou add no DVR use o link: rtsp://ESP32Cam.local:8554/mjpeg/1
( não é preciso entrar o IP do módulo, ao menos que sua rede não suporte mDNS, pois ele propaga o IP através de mDNS )



marcelo campos - GHC


