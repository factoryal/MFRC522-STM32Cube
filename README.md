# MFRC522-STM32-HAL
A C++ STM32 HAL library can handle MFRC522(or RC522 RFID module).
- Based on code Dr.Leong   ( WWW.B2CQSHOP.COM )
- Created by Miguel Balboa (circuitito.com), Jan, 2012.
- Rewritten by Soren Thing Andersen (access.thing.dk), fall of 2013 (Translation to English, refactored, comments, anti collision, cascade levels.)
- Ported to mbed by Martin Olejar, Dec, 2013 [mbed library](https://os.mbed.com/users/AtomX/code/MFRC522/)
- Ported to STM32 HAL by _0x4d from Factoryal Laboratory, March, 2022.


## Please Read Before Use
This library runs in blocking mode.
SPI instructions are not implemented using IT or DMA and also uses `HAL_Delay()`.
Using in ISR is not recommended.
