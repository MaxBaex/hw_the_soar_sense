# Hardware_SOAR_Sense
Minimalistic very small temperature and humidity sensing device. Could also be used for differential pressure sensing. Two I2C interfaces are desired.  PCB shall be as small as possible. A couple of ADC inputs are desired e.g. for control input sensing (VDD as reference and a slightly protected input). 

Hours: 10 

## Facts
- SWD interface
- STM32F103 48LQFP C8304    Stock 07.01: 1621
- 8 MHz Crystal 
- CAN transceiver: MAX3051EKA+T   C112005  SOT-23-8
- 3.3V LDO: SPX3819M5-L-3-3/TR	C9055	Recommended Max + 16V	Absolute max +20V	SOT-23-5	Alternative:	LM1117IMPX	C23984  Recommended Max + 15V	Absolute max +20V	SOT-223
- SHT31-DIS-B2.5kS C80862 Alternative: SHT35-DIS-B  C90161


## TODOs:
- Discussion:   Slope Control CAN-Interface required  EMC?
- Missing SWD Interface
- Mountinholes  , Cableholes
