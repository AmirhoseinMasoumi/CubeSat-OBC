# What is an OBC?
An OBC primarily consists of a microprocessor, memory banks, and an interfacing chip to connect the computer to other sub-systems.        
A range of standard and non-standard interface formats are in use (e.g. RS485, CAN, SpaceWire, SPI and I2C) and the OBC itself can be provided as an integrated unit in the satellite bus and avionics system, or as a modular device capable of working with various other pieces of multi-vendor equipment.     
The OBC plays several roles in the effective operation of a spacecraft or satellite. These functions usually include:       
- Attitude and orbit control
- Telemetry data management
- Telecommunication actions
- System housekeeping
- On-board time synchronization
- Failure detection, isolation, and recovery

### Processor:
-	STM32F429BI	
-	32bit
-	High-Performance MCU
-	Up to 180 MHz

### Operating system:
-	FreeRTOS
-	RTXRTOS
-	Other Real-Time Operating system

### Memory:
-	64MB Static RAM
-	1GB NAND Flash Memory for housekeeping data
-	32GB SD CARD Memory for Payload data

### Interfaces: 
-	2x CAN 2.0B bus interface up to 1Mbps
-	2x UART interfaces
-	3x USART interfaces
-	2x I2C interfaces
-	4x SPI 
-	Hi-Speed USB 2.0

### Physical Characteristics:
-	1.71 V to 3.6 V power supply
-	-40 °C to 85/125 °C temperature range
-	90 x 96 x 26.3 mm 
-	Less than 100g

---

![Tilted](https://github.com/AmirhoseinMasoumi/CubeSat-OBC/blob/main/Assets/Images/Tilted.png)

---

![Front](https://github.com/AmirhoseinMasoumi/CubeSat-OBC/blob/main/Assets/Images/Front.png)

---

![Back](https://github.com/AmirhoseinMasoumi/CubeSat-OBC/blob/main/Assets/Images/Back.png)

---

![Layers](https://github.com/AmirhoseinMasoumi/CubeSat-OBC/blob/main/Assets/Images/Layers.png)
