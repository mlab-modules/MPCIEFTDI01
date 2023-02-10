# MPCIEFTDI01

MPCIEFTDI01 is a mini-PCI-E breadboard with a FTDI io and a 5V power supply. This board is intended for an easy and reliable source of UART/I2C/SPI or GPIO interface to a devices that are equipped with that mPCIe slot. MiniPCIe slot is often found in network devices (routers), single-board computers or other in other SOC systems. 

## Example of use
 * Extension of UART/GPIO Computer interface without having to use external hardware
 * Interface for obtaining precission time from GPS with support of PPS signal. 
 * 

## Known compatibile devices

### Turris Omnia router

### Turris MOX
System turris MOX contains modules ?? or ?? that provides mPCIe slot. Turris Mox contains itself a GPIO interface, which has only 1.8V logic and is introduced to the processor. With this Breadbord, you add a layer that can protect the processor itself under problems.

### RaspberryPi CM4
RaspberyPi CM4 is equipted with PCIE interface. With the motherboard equited with mPCIe slot, you can use this module with RaspberryPi CM4. 

#### ReTerminal
Reterminal is terminal device (computer, display+touchscreen in compact packing) from seedstudio. ReTerminal is based on RP CM4. For ReTerminal, there is extension module that provides mPCIe interface. Along this, extension module includes backed-up supply from LiIon acumulators, RS232, RS485, CAN interface and high-range voltage supply input. Extension also contains of POE input. 


