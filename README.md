# PRINT_CLEM_FILE_CRC41_FLASH_16MB_24BIT_NVM_64K_16BIT
This will print crc41 of clem file having flash and nvm data 
build method==>
gcc .\read_ClemFile_Print_CRC41_FLASH_16M_NVM64K_R01.c -o .\read_ClemFile_Print_CRC41_FLASH_16M_NVM64K_R0
Execution method==>
.\read_ClemFile_Print_CRC41_FLASH_16M_NVM64K_R01.exe .\0003812.j19
Expected Reply==>
21,2
Where 21= Decimal value of crc41 of nvm 64k data inside the file 0003812.j19 and is identified by starting byte zero.
      2= Decimal value of crc41 of flash 16MB 24 bit memory inside the file 0003812.j19 and is identified by starting byte 02.

