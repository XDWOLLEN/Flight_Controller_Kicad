# STM32F407 Flight Controller

## 🚁 Proje Özeti

STM32F407VGT6 tabanlı profesyonel otonom uçuş kontrol kartı tasarımı.

### Ana Özellikler:
- ✅ **STM32F407VGT6** - 168MHz ARM Cortex-M4 mikrodenetleyici
- ✅ **MPU9250** - 9-axis IMU (Gyro + Accel + Magnetometer)
- ✅ **MS5611** - Barometrik basınç sensörü
- ✅ **MAX7456** - OSD chip (FPV video overlay)
- ✅ **W25Q128** - 128Mbit SPI Flash (blackbox)
- ✅ **GPS Modülü** - UART GPS desteği
- ✅ **8x PWM Çıkışı** - Motor/servo kontrol
- ✅ **USB Programlama** - Micro USB port
- ✅ **4-Layer PCB** - 70mm x 50mm

## 📁 Dosyalar

- `stm32_flight_controller.kicad_pro` - KiCad proje
- `stm32_flight_controller.kicad_sch` - Şematik
- `stm32_flight_controller.kicad_pcb` - PCB layout
- `gerber/` - Üretim dosyaları
- `BOM.csv` - Malzeme listesi

## 🔧 Kullanım

1. KiCad 6.0+ ile açın
2. Schematic Editor'de şemayı görüntüleyin
3. PCB Editor'de layout'u inceleyin
4. Gerber dosyalarını export edin

## 📦 PCB Özellikleri

- Boyut: 70mm x 50mm
- 4-Layer: F.Cu / GND / PWR / B.Cu
- Kalınlık: 1.6mm
- Min Track: 0.15mm

## 💾 Firmware Desteği

- Betaflight
- iNav
- ArduPilot
- PX4

Başarılı uçuşlar! 🚁