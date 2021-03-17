# esp32-line-beacon

Hardware : ESP32 WROOM

Software : arduino 

Addon config : 

File ->Preferences [ Additional board url : https://dl.espressif.com/dl/package_esp32_index.json ]

Tools -> Boards -> Boards Manager [ Install ESP32 by espressif systems ]

Sketch -> Include Library -> Manage Libraries… [ ESP32 BLE Arduino by Neil Kolban ]

===============
|   000000    |
|   oooooo    |
|             |
[ o  usb  (x) ]

กดปุ่ม Boot ค้างไว้ แล้วเสียบสาย USB 

ในโปรแกรม Arduino กด upload รอข้อความ connect ขึ้น ค่อยปล่อยปุ่ม Boot รอจนครบ 100% 
