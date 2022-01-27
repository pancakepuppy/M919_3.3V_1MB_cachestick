# M919_3.3V_1MB_cachestick
A 3.3V 1MB cache stick design for PCChips M919

(This design is only to be used with 3.3V processors. 5V/4V CPUs will violate the Absolute Maximum Terminal Voltage Relative to GND of the 3.3V SRAM chips which will likely result in permanent damage of the cache ICs.)

Design uses center power 0.400" 32-SOJ 128Kx8 3.3V SRAMs, which are available in speed grades of 8(less common)/10/12/15ns from several vendors. 
These parts should all fit this criteria:

71V124SA10/12/15Y

CY7C1019DV33-10VXI

CY7C1019BV33-10/12/15V

CY7C1019CV33-10/12/15V

IS63LV1024-8/10/12K

AS7C31025B-10/12/15J

AS7C31025C-10J


Bill of materials only has 3 different parts on it:

  Qty 18 - 0603 0.1uF 6.3V+ ceramic capacitors
  
  Qty 9 - SRAM parts as described above
  
  Qty 4 - 0603 33ohm convex 4resistor array
  
If you're experienced at hand soldering, the module is buildable this way (that's how I've built mine so far!)

I've been testing the module design with a 5x86-P75 (133MHz) at fastest L2 and DRAM settings and it has been very stable, running a number of DOS and Win95 benchmarks and tests (such as Quake, Doom, cachechk, Winstone 96, CPUmark99, Super PI) with no issues. 

If you want to have boards made with JLCPCB, upload the "UPLOAD_THIS_ZIP.zip" file in the /plotted_JLCsettings/ directory. It has the gerbers and drill files with their recommended plotting settings. Otherwise, plot however your board house recommends!
