# SPI-Master-controller-in-Verilog

# SPI Master (Mode-0) in Verilog

## Description
Designed an SPI Master controller in Verilog supporting Mode-0 (CPOL=0, CPHA=0). Implemented FSM-based control, clock divider, and shift registers for full-duplex 8-bit data transfer. Verified functionality using a self-written testbench and EPWave waveform analysis in EDAPlayground.

## Features
- SPI Mode-0 support
- FSM-based control
- MSB-first data transfer
- Full-duplex communication
- EPWave waveform verification (EDAPlayground)

## Signals
- MOSI, MISO, SCLK, CS
- start, done handshake
- tx_data[7:0], rx_data[7:0]

## Tools Used
- Verilog HDL
- Icarus Verilog
- EDAPlayground
- EPWave

## Verification
Verified using a self-written testbench and waveform analysis in EPWave.
