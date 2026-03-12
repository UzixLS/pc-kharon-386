## ROM files

* **M6117 - award+ami.bin** — for the main PCB (U14) - system BIOS. Two alternative variants are included and can be selected using SW3. The AMI BIOS is recommended.
* **tvga9000i - D3.51 + D4.01E.bin** — for the top PCB (U7); video BIOS. Two alternative variants are included and can be selected using SW1.1.
* **AT93C66-dump.bin** — for the top PCB (U10); sound card PnP options. This ROM is optional, use it only if you experience problems with IRQ/DMA resource assignment.

All ROMs must be flashed before being soldered onto the PCB; in-circuit programming is not possible.

You can use any suitable ROM programmer (for example, TL866II). For detailed instructions, refer to the manufacturer’s manual.
