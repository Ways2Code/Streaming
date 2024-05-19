# UART RX & TX along with Full-Adder

The final title was **Arty Z7-20 - Designing a CPU - UART TX & RX**

## Plan

1. Quick introduction
2. Looking up `XUartPs C module`
   1. Changing `xil_printf` with `XUartPs_Send`
   2. Use `XUartPs_Recv`
3. Full-Adder
   1. Binary Counting
   2. Binary Addition
   3. `AND`, `OR`, `NOR`, and `XOR` logic gates
   4. Implementing the Full-Adder
4. Testbench the Full-Adder

## Notes

* Remove my hand from my mouth when talking.
* I've been RAIDED!!! Need a Twitch cheatsheet to be able to raid other streamers.
  * RAID, when someone follow, subscribe, etc.
  * [Cheatography](https://cheatography.com/haywardgg/cheat-sheets/twitch/)
* Forgot to promote on **Thread** and **Reddit**.
* Had "a lot" of interaction, didn't had time to do the full adder - only the half-adder.
* Still a lot of *hummm*, also *sorry*.
* Not seeing the chat on stream is hard to follow my reaction
* Forget a lot of changing the right screen setup back

## Related link used in stream

* [RISC-V](https://riscv.org)
* [ARM Inc.](https://www.arm.com)
* [SiFive](https://www.sifive.com)
* [`XUartPs.c` source file](https://github.com/Xilinx/embeddedsw/blob/master/XilinxProcessorIPLib/drivers/uartps/src/xuartps.c)
* [Digilent Arty Z7 Shop Page - Not Affiliate](https://digilent.com/shop/arty-z7-zynq-7000-soc-development-board/) the shop page of the Arty Z7.
* [PCPartPicker](https://pcpartpicker.com/)
* [Amazon ECS F1 FPGA](https://aws.amazon.com/ec2/instance-types/f1/)

## Questions

* Can we really run RISC-V on low-cost FPGAÉ
  * Seem so : [Bonfire RISC-V softcore](https://bonfirecpu.eu/)
  * [Bit-by-bit implementation](https://www.youtube.com/watch?v=xjIxORBRaeQ)
  * [VexRiscV](https://github.com/SpinalHDL/VexRiscv)

