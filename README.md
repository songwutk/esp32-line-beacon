# esp32-line-beacon

Hardware : ESP32 WROOM

Software : arduino for windows (ใน ubuntu มีปัญหาเรื่อง python serial)

Addon config : 

File ->Preferences [ Additional board url : https://dl.espressif.com/dl/package_esp32_index.json ]

Tools -> Boards -> Boards Manager [ Install ESP32 by espressif systems ]

Sketch -> Include Library -> Manage Libraries… [ ESP32 BLE Arduino by Neil Kolban ]



[ o  usb  (x) ]

กดปุ่ม Boot ค้างไว้ แล้วเสียบสาย USB 

ในโปรแกรม Arduino กด upload รอข้อความ connect ขึ้น ค่อยปล่อยปุ่ม Boot รอจนครบ 100% 


# การทดสอบ

ติดตั้ง App BLE Scanner จะสแกนพบ Mac address ก่อน 

จากนั้นกด RAW Data ตรง LEN 23 0x16 จะต่อด้วยเลข hwid ตรงกลางๆ 
