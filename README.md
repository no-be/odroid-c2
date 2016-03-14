# odroid-c2

## Files  

.log files are console output during xen boot  
.txt files are the DT nodes used for the test  
.debug files show addr2line command output  

## timer

meson : currently upstream timer  

26_30 : means that the IRQs tested for the timer are between 26 and 30  
10_14 : means that the IRQs tested for the timer are between 10 and 14  

ff01 : IRQ type edge rising  
ff08 : IRQ type level low  

## gic

meson   : currently upstream gic  

400_c43 : gic: interrupt-controller@c4301000 {  compatible = "arm,gic-400";  
400_2c  : gic: interrupt-controller@2c001000 {  compatible = "arm,gic-400";  
