# PCA9554 Arduino lib
Hey! This library has been designed to work with the Xserve Raid front panel board based on PCA9554.

###  Includes

List of libraries required for assembly:
1. Wire.h

### Pinning

1. It is necessary to connect A0, A1 and A2 pins of the right PCA9554 board. This is necessary for they receive different addresses.  
![image](https://user-images.githubusercontent.com/75093384/150637586-651527f2-f72e-4234-a266-b7d3f98d4886.png)
2. In the constructor of the class, create two objects and pass addresses to them. If you connected everything correctly, then the left board will receive the address 0x24, and the right board will receive the address 0x27.  
![image](https://user-images.githubusercontent.com/75093384/150638168-b07f4831-8b7a-4c78-8251-ae4e21fb6e20.png)
