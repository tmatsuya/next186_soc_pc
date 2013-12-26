Next186 SoC PC
-----------------------------
[> Project URL
  http://opencores.org/project,next186_soc_pc

[> Directory Structure
 /HW/         HDL files
 /SW/         Softwares

[> Support Boards
1- Xilinx Spartan-3AN Starter Kit

[> Support SD Card
1- Akizuki Denshi K-05818 (Cixi Borui Technology Co., Ltd.)
   shop         http://akizukidenshi.com/catalog/g/gK-05818/
   data sheet   http://www.boruit.com/CHINESE/SDcard.htm

[> Building tools
You will need:
 - ISE 14.4

[> Building SD
1- dd if=SW/BIOS_Next186/BIOS_Next186.com of=/dev/sd? bs=512 seek=*(total block-16)

[> How to build
1- run ISE tool
2- open ddr_186.xise

