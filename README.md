# M919_3.3V_1MB_cachestick
A 3.3V 1MB cache stick design for PCChips M919

(This design is only to be used with 3.3V processors. 5V/4V CPUs will violate the Absolute Maximum Terminal Voltage Relative to GND of the 3.3V SRAM chips which will likely result in permanent damage of the cache ICs.)

Design uses center power 0.400" 32-SOJ 128Kx8 3.3V SRAMs, which are available in speed grades of 8(less common)/10/12/15ns from several vendors. Bill of materials only has 3 different parts on it:

  Qty 18 - 0603 0.1uF 6.3V+ ceramic capacitors
  
  Qty 9 - SRAM parts as described above
  
  Qty 4 - 0603 33ohm convex 4resistor array
  
If you're experienced at hand soldering, the module is buildable this way (that's how I've built mine so far!)

I've been testing the module design with a 5x86-P75 (133MHz) at fastest L2 and DRAM settings and it has been very stable, running a number of DOS benchmarks and Windows 95 + Super PI without any hiccups. The KiCad 6 project files and an archive ready to send to JLC for production will be uploaded once I receive revised boards to test and verify a minor change.

STAY TUNED! :)
