# SeniorProjectDocs
Documents and Resources 
STICKIED:
  - https://www.linux-mips.org/
  - https://imgtec.com/
  - http://www.edaboard.com/forum.php
  - http://opencores.org/project,plasma
  - http://opencores.org/project,ion
  - https://reference.digilentinc.com/_media/nexys4-ddr:nexys4ddr_rm.pdf

1. Porting Linux
  a. A guide doing similar to what we want to do, but with different hardware:    http://www.tldp.org/LDP/cpg/Custom-Porting-Guide.pdf 
    -Read the First two sections and it gave a good outline of what is needed ot port and usefull software.
  b. Linux to MIPS Port website: https://www.linux-mips.org/wiki/Linux/MIPS_Porting_Guide#Setup_a_cross-development_environment
    - This appears to be the real deal, has alot of info check out the guide
  c. Good answers on how to port Linux, list of neccessary things to do: http://unix.stackexchange.com/questions/56550/running-the-linux-kernel-and-ubuntu-on-custom-processor
  d. Bootloader? : http://www.linux-mips.org/wiki/U-Boot 
  e. 
2. MIPS
  a. List of MIPS microcomputers: https://en.wikipedia.org/wiki/List_of_MIPS_microarchitectures 
  b. Imagination Tech (Owns MIPS) References: https://imgtec.com/mips/architectures/mips32/ 
  c. Example Imgetec uComputer DataSheet: https://imagination-technologies-cloudfront-assets.s3.amazonaws.com/documentation/MD01024-2B-P5600-DTS-01.00.pdf
  d. Trap unimplmented opcodes, this shows a method but isn't great: http://archive.6502.org/publications/dr_dobbs_journal_selected_articles/trap_vector_for_unimplemented_opcodes.pdf 
  e. Complete 32 bit MIPS uCPU (VHDL): http://opencores.org/project,plasma 
  f. Work in progress 32b MIPS CPU: http://opencores.org/project,ion
  g. Basic MIPS ISA: http://www.mrc.uidaho.edu/mrc/people/jff/digital/MIPSir.html 
3. GCC
  a. GCC can be used to output Binary or Assebly object code: http://stackoverflow.com/questions/1289881/using-gcc-to-produce-readable-assembly 
  b. GCC supports compilation of C to MIPS Object Code: https://gcc.gnu.org/onlinedocs/gcc/MIPS-Options.html
  c. Small primer on GCC, then shows redhats improvments to GCC: https://www.redhat.com/magazine/002dec04/features/gcc/ 
4. BCD and 7 Seg Decoder
  a. Verilog exmaple code: http://www.delorie.com/electronics/bin2seven/
  b. Less good example: http://ece353.ecs.umass.edu/verilog/verilog_files/seg7.v 
5. FPGA Development
  a. Xilinx FPGA vs. ASIC: http://www.xilinx.com/support/documentation/white_papers/wp213.pdf , http://www.xilinx.com/fpga/asic.htm 
  b. Thourough CPU in VHDL: http://www.cl.cam.ac.uk/teaching/1011/SysOnChip/socdam-notes1011.pdf 


###Piplining example:
(/Jam-G/MIPS): https://github.com/Jam-G/MIPS

[building own 16 bit microcomputer](https://archive.org/stream/tibook_how-to-build-your-own-working-16-bit-microcomputer/how-to-build-your-own-working-16-bit-microcomputer#page/n7/mode/2up)
