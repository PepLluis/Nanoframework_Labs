# Nanoframework_Labs
For old electronics
- Cerbeus / Cerbuino / Cerberus NET / CERB40 
steps
1) Xtal 32k Cerbuino : between D3/D4 / Cerberus Soket 5 P3/P4
2) Boot DFU Mode 
   - Short LDR Holes or push LDR Button) for cerbuino/cerberus boards
   - Short LDR and 3v3 for CERB40
3) Download boot/CLR from nanoframework community repositories
3) From STM Cube programmer : Full chip erase, Download nanoBoot.hex, restart and Download nanoCLR.hex
4) Check for a new virtual serial port for this device
5) Open Visual studio and send any "Hello World"

- Mountainer boards
  - USB/NET - Short 3v3 + P8 (Socket 8)
  - Follow the same previous procedure from steep 3
  
- STM32F4-Discovery
  - Use CubeProgrammer with ST-LINK to download nanoBoot.hex and nanoCLR.hex
