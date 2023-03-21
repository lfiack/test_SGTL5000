# Test SGTL5000
Test board for the SGTL5000 CODEC

## Notes
* SAI1_FS_A stands for frame synchronization, might be connected to CODEC's I2S_LRCLK pin (32/48/96kHz)
* SAI1_SD_A stands for serial data, connect to CODEC's I2S_DIN pin
* SAI1_SD_B is SAI B Synchronous Slave's serial data, connect to I2S_DOUT
* SAI1_SCK_A connect to I2S_SCLK (32/64 times FS frequency)
* SAI1_MCLK_A connecto to SYS_MCLK
    * "An integrated PLL is provided in the SGTL5000 that allows any clock from 8.0 to 27 MHz to be connected to SYS_MCLK"

* CODEC's CTRL_CLK is I2C SCL
* CODEC's CTRL_DATA is I2C SDA
