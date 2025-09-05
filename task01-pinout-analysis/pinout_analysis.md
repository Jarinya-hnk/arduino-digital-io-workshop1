## Pinout Analysis

- **Digital I/O Pins (0-13):** ใช้สำหรับรับหรือส่งสัญญาณดิจิทัล (HIGH/LOW) สามารถตั้งเป็น input หรือ output ได้
- **Analog Input Pins (A0-A5):** ใช้วัดแรงดันไฟฟ้าแบบแอนะล็อก (0-5V) และแปลงเป็นค่าดิจิทัล (ADC)
- **Power Pins:**
	- 5V: จ่ายไฟ 5 โวลต์ให้กับวงจรภายนอก
	- 3.3V: จ่ายไฟ 3.3 โวลต์ให้กับวงจรภายนอก
	- GND: ขา ground
	- Vin: รับไฟเลี้ยงจากแหล่งจ่ายภายนอก (7-12V)
- **Special Function Pins:**
	- PWM (~): ขาที่รองรับการส่งสัญญาณ PWM (Pulse Width Modulation) เช่น 3, 5, 6, 9, 10, 11
	- SPI: ขา 10 (SS), 11 (MOSI), 12 (MISO), 13 (SCK)
	- I2C: ขา A4 (SDA), A5 (SCL)
- **Hardware Interrupts:** ขา 2 และ 3 รองรับการใช้งาน interrupt จากฮาร์ดแวร์
