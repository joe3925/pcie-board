# ARM Compute 
1. [ ] Add the actual chip component.
2. [ ] Wire the chips endpoints.
3. [ ] Add and fully model the DDR3L block and wire it properly to cpu + power.
4. [ ] Add and fully model the clock block and wire it properly to cpu + power. 
5. [ ] Add and fully model the boot block and wire it properly to cpu + power. 
6. [ ] Add and fully model the core power block and wire it to everything, it should take 5v + 3.3v in and will contain outputs to all blocks for there power 
7. [ ] add JTAG and UART for debugging, wire as needed to the cpus UART. 

## DDR3L
1. [ ] add the DDR3L block and figure out what supporting internal blocks it needs. (add todos here when done)

## Clock
1. [ ] add the Clock block and figure out what supporting internal blocks it needs. (add todos here when done)

## Boot
1. [ ] add the Boot block and figure out what supporting internal blocks it needs. (add todos here when done)

## Power 
1. [ ] add the Power block and figure out what supporting internal blocks it needs. (add todos here when done)

# Clocking (this is a seperate small subsystem for the pcie REFCLK) 
1. [ ] add a 100mhz clock to a small block this will then split into 2 outputs CPU_REFCLK_OUT and FPGA_REFCLK_OUT and a common ground, they go to the FPGAs REFCLK_IN and the ARMs REFCLK_IN.

# PCIE Upstream
1. [ ] Figure out rating needed for tx/rx capacitors

# FPGA 
1. [ ] add the FPGA block and figure out what supporting internal blocks it needs.

# PCIE Device 
1. [ ] create a small fpga device to act as the pcie x1 device to test with.