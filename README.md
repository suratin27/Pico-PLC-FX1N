# Pico-PLC-FX1N
 Orange pi Pico PLC Firmware
 Technical specifictions
  
  1.Hardware
   - Raspberry pi Pico

  2.PLC Function compatibility
   - PLC Model : FX1N/FX1NC
   - Input 10 Input
   - Output 7 Output (Active low)
   - Ladder step : 2000 steps
   - Retentive memory : No
   - RS485 modbus : Yes
   - RS485 function
     - Modbus master
     - Modbus slave
   - Analog input 2 Input
  
  3.How to install firmware (ขั้นตอนการติดตั้ง FX1N Firmware)
   - กดปุ่ม boot บนบอร์ด Raspberry pi pico ค้างไว้พร้อมกับเสียบบอร์ด Raspberry pi pico เข้ากับ usb port ของคอมพิวเตอร์
   - จากนั้นบอร์ดจะเข้าสู่ โหมด Flash drive
   - จากนั้น copy ไฟล์ Firmware.ino.uf2 ไปวางไว้ใน drive นั้น
   - จากนั้น Raspberry pi pico จะ reboot 1 ครั้ง
   - จากนั้น Raspberry pi pico ของจะกลายเป็น FX1N ที่พร้อมสำหรับเชื่อมต่อกับ GXWork2 ได้ทันที

   *** ขอให้ทุกท่าน สนุกสนานกับการใช้งานครับ ***

  4.PLC Pinput
  ![Pico_PLC_Pinout_2023](https://github.com/suratin27/Pico-PLC-FX1N/blob/main/my%20files/Pico_PLC_Pinout_2023.png)

  5.Chinese HAT
  ![Chinese-HAT](https://github.com/suratin27/Pico-PLC-FX1N/blob/f9ee5f900fe66b66cfc3b8f3a552068f2e1f9e2e/my%20files/Chinese_HAT.jpg)
 
