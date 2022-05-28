# Open-FPGA_RISC-V based MYTH
<br />OSFPGA RISC-V Workshop
<br />**Day 1**
<br />Introduction to RISC-V ISA and GNU compiler toolchain

<br />**1. Introduction to RISC-V basic keywords**
<br />![1](https://user-images.githubusercontent.com/66528639/170438295-96af3bc3-55a1-4f7b-b473-2ce3fbf7c3d0.jpg)
<br />
<br />![2](https://user-images.githubusercontent.com/66528639/170438416-7b6a3424-0de7-413a-8b01-591a59aaa0b6.jpg)
<br />
<br />![3](https://user-images.githubusercontent.com/66528639/170438500-1e7dbad3-1ac3-46dc-80e2-636be594ad94.jpg)
<br />
<br />![4](https://user-images.githubusercontent.com/66528639/170438544-119bd6f4-9a3f-48a3-a08d-92f31fa23040.jpg)
<br />
<br />![7](https://user-images.githubusercontent.com/66528639/170438772-3f784bc8-d685-4691-a2d1-21220521a2a9.jpg)
<br />
<br />Pseudo Instructions
<br />
<br />![8](https://user-images.githubusercontent.com/66528639/170438919-a7693724-5dc3-43b0-8665-453052dcaa2e.jpg)
<br />
<br />Base Integer Instructions
<br />
<br />![9](https://user-images.githubusercontent.com/66528639/170439012-d6e3a867-f7a5-4bd4-ae28-a7982de60c50.jpg)
<br />
<br />Multiply Extension RV64M Instructions
<br />
<br />![10](https://user-images.githubusercontent.com/66528639/170439188-bf4792e9-ce55-4489-a08e-081c1c9acafd.jpg)
<br />
<br />Single and Double Floating Point Instructions (RV64F and RV64D)
<br />
<br />![11](https://user-images.githubusercontent.com/66528639/170439385-78e9a10c-9416-4db1-8991-d0eca851c05d.jpg)
<br />
<br />Application Binary Interface Instructions
<br />
<br />![12](https://user-images.githubusercontent.com/66528639/170439483-e60fe255-1148-4241-8c8f-29b53587d6ae.jpg)
<br />
<br />Memory Allocation and Stack Pointer Instructions
<br />

<br />**2. Labwork for RISC-V software toolchain**
<br />
<br />![lab_1](https://user-images.githubusercontent.com/66528639/170440498-dd8c2a10-308e-4b86-95ca-ba00cbdd6ca1.jpg)
<br />
<br />Command to invoke text editor for C Program
<br />
<br />![Lab_2](https://user-images.githubusercontent.com/66528639/170440683-bbcfceae-52f3-43b0-979d-64e68380f574.jpg)
<br />
<br />Program to calclulate sum of N numbers
<br />
<br />![lab_3_object_file_main](https://user-images.githubusercontent.com/66528639/170440881-5afeb324-de14-4ae5-9b7d-2fa180fda657.jpg)
<br />
<br />Object file when "O1" is used, the number of instruction required is 15
<br />
<br />![lab_4_object_file_main](https://user-images.githubusercontent.com/66528639/170441329-958201bd-6818-4cac-92c1-2f16639bde54.jpg)
<br />
<br />Object file when "Ofast" is used, the number of instruction reduced to 12
<br />

<br />**3. Integer number representation - Signed and unsigned arithmetic operations**
<br />
<br />![Lab_3_Unsigned_Max](https://user-images.githubusercontent.com/66528639/170441738-c7b7864d-79c9-4b64-ba5c-a48b33098f21.jpg)
<br />
<br />Max value for Unsigned Data type with C program and commands
<br />
<br />![Lab_3_Unsigned_Max_Limit_Exceed](https://user-images.githubusercontent.com/66528639/170442594-505b720e-c03f-47ca-a01a-5ba3e3b5f8a7.jpg)
<br />
<br />Max limit value for Unsigned Data type exceed with C program and commands
<br />
<br />![Lab_3_Unsigned_Max_Lowest](https://user-images.githubusercontent.com/66528639/170442763-dcabf34e-353a-4c1c-ad80-f2d71ef96b98.jpg)
<br />
<br />Min value for Unsigned Data type with C program and commands
<br />
<br />![Lab_3_Unsigned_Max_Within_Limit](https://user-images.githubusercontent.com/66528639/170442956-2ec2a2ad-996e-4443-80de-4fb63c5f4eeb.jpg)
<br />
<br />Unsigned Data type with C program and commands within the limit
<br />
<br />![Lab_3_signed_value](https://user-images.githubusercontent.com/66528639/170443120-9dac9309-c588-4f26-95a5-08d27c3709be.jpg)
<br />
<br />Signed Data type with C program and commands 
<br />
<br />![Lab_3_signed_max_min](https://user-images.githubusercontent.com/66528639/170443290-58d30297-dfe9-48ea-82bd-65df4107fa97.jpg)
<br />
<br />Signed Data type with C program and commands with Max and Min limit
<br />
<br />**Day 2**
<br />
**<br />1.Application Binary interface (ABI)**
<br />![1](https://user-images.githubusercontent.com/66528639/170626363-66fe065c-f95a-42e0-9b84-842684ad209e.jpg)
<br />
<br />Application Binary Interface
<br />![2_ABI](https://user-images.githubusercontent.com/66528639/170626388-46b16aa8-c56e-419d-a109-ef19c95c2575.jpg)
<br />
<br />Application Binary Interface overview
<br />
<br />![3_Memory](https://user-images.githubusercontent.com/66528639/170626415-b0f27766-15ab-4189-b141-b8e77ffbba0d.jpg)
<br />
<br />Application Binary Interface Registers
<br />
<br />![4_32bit_register](https://user-images.githubusercontent.com/66528639/170626600-4dbce797-97d6-4dd5-83a0-baf7326b7487.jpg)
<br />
<br />Application Binary Interface Registers Type
<br />
<br />![4_I_type_Instruction](https://user-images.githubusercontent.com/66528639/170626748-f829c2b7-f401-48a3-8679-291fc2268789.jpg)
<br />
<br />Application Binary Interface Registers Type-I
<br />
<br />![4_R_type_Instruction](https://user-images.githubusercontent.com/66528639/170626807-9fac6fe8-a37a-49a1-bcff-1dbb5895e2a8.jpg)
<br />
<br />Application Binary Interface Registers Type-R
<br />
<br />![4_S_type_Instruction](https://user-images.githubusercontent.com/66528639/170626874-41950665-f0b4-4c6a-b45a-1528c4407d06.jpg)
<br />
<br />Application Binary Interface Registers Type-S
<br />
<br />![5_Registers](https://user-images.githubusercontent.com/66528639/170626981-35586fe7-b5eb-4949-bd8e-7ca9b4a46a12.jpg)
<br />
<br />Application Binary Interface Registers register usage
<br />

**<br />2. Lab work using ABI function calls**
<br />
<br />![6_CtoASM_Program](https://user-images.githubusercontent.com/66528639/170627095-7f49ba4d-2c38-4576-ba7d-8998a2bf6c46.jpg)
<br />
<br />Flow diagram for C program using ASM language
<br />
<br />![7_lab_CtoASM_results](https://user-images.githubusercontent.com/66528639/170627210-dcb342bd-70d8-4af6-9f2d-036b4ec8b708.jpg)
<br />
<br />C program and ASM program with commands and results
<br />
<br />![8_lab_object_CtoASM_results](https://user-images.githubusercontent.com/66528639/170627300-1c0eab8e-beea-4d3f-bdcb-a3b16724f2ee.jpg)
<br />
<br />Object program C to ASM
<br />
<br />![9_CtoRISCV_Conversion](https://user-images.githubusercontent.com/66528639/170627436-235bfaf3-6b80-4a25-b655-c16a422d6110.jpg)
<br />
<br />C porgram on RISCV CPU

**<br />3. Basic verification flow using iverilog**
<br />
<br />![10_Program_to_convert_Hex](https://user-images.githubusercontent.com/66528639/170631345-080f1e80-f4da-497f-a122-22e691431fc7.jpg)
<br />Program to convert C program to Hex
<br />
<br />![10_results](https://user-images.githubusercontent.com/66528639/170631421-e65c89f6-70f6-44e6-87f3-f4193d2205c2.jpg)
<br />
<br />Results of program to find sum of N=2
<br />
<br />![10_Hex_data](https://user-images.githubusercontent.com/66528639/170631600-3aa00698-cf92-44ed-bb66-6c0e711b2d64.jpg)
<br />
<br />Hex converted file
<br />
<br />**Day 3**
**<br />Combinational logic in TL-Verilog using Makerchip**
<br />
<br />![1_Makerchip_start](https://user-images.githubusercontent.com/66528639/170826090-2d6fea4d-ae88-4062-8e5d-f062fc8385ed.jpg)
<br />
<br />![2_Add_vectors](https://user-images.githubusercontent.com/66528639/170826102-cc8c9553-efa0-492c-bb8d-e5c8ec4568c9.jpg)
<br />
<br />Addition of 2 vectors
<br />![2_Sub_vectors](https://user-images.githubusercontent.com/66528639/170826174-6757ccb2-bd6b-43d8-a8c5-f6449c716347.jpg)
br />Substraction of 2 vectors
<br />![2_and_gate](https://user-images.githubusercontent.com/66528639/170826116-d47dde2e-740a-4cda-b522-1cfabfef0fcf.jpg)
<br />AND gate implementation
<br />![2_Or_gate](https://user-images.githubusercontent.com/66528639/170826158-cb8903db-5e91-44e9-809d-f08905454345.jpg)
br />
<br />![3_calculator_editor](https://user-images.githubusercontent.com/66528639/170826199-c6c486af-54f6-4cd5-914b-381b949c4a49.jpg)
<br />Claculator Editor
<br />
<br />![3_Calculator_Log_file](https://user-images.githubusercontent.com/66528639/170826208-ab10ff79-f612-4c02-b6cf-a781087e4154.jpg)
<br />Claculator Log file
<br />
<br />![3_calculator_TLV](https://user-images.githubusercontent.com/66528639/170826220-39667810-c238-4602-a671-31dd2179b9c0.jpg)
<br />Claculator TLV file
<br />
<br />![4_fibbonaci_series](https://user-images.githubusercontent.com/66528639/170826240-75d11e01-5053-48f5-8b36-b4a4fd7bdb12.jpg)
<br />Fibonacci series
<br />
<br />![5_Counter](https://user-images.githubusercontent.com/66528639/170826261-77c7ff32-037a-4a60-8ac3-2f589fedac48.jpg)
<br />Counter
<br />
<br />![6_Real_calculator_TLV](https://user-images.githubusercontent.com/66528639/170826267-f7134986-2141-4fe7-bb6a-d6aa1a959c1f.jpg)
<br />Real Calculator
<br />
<br />
**<br /> Sequential and pipelined logic & Validity **
<br />
<br />![8_Pythagorus_theorem](https://user-images.githubusercontent.com/66528639/170826360-52fdb96c-0e1b-4403-b71e-fce0f5fbb057.jpg)
<br />Pythagours Theorem
<br />
<br />![9_Pipeline_error](https://user-images.githubusercontent.com/66528639/170826377-74b45d7d-f674-4fab-8fa9-8daea67aaf44.jpg)
<br />Pipeline Error
<br />
<br />![10_Cycle_Calculator](https://user-images.githubusercontent.com/66528639/170826392-1fc446e2-b649-4ae5-80a1-9331a89fe918.jpg)
<br />Cycle Calculator
<br />
<br />![11_validate_phy](https://user-images.githubusercontent.com/66528639/170826415-a101117f-f2c3-47aa-8330-7447ee1b0855.jpg)
<br />Validate of Phythagorus
 
 
 <br />**Day 4**
 ** <br />Basic RISC-V CPU micro-architecture** <br />
 <br />Implementation on TL-Verilog
 <br />
 <br />![CPU_Design](https://user-images.githubusercontent.com/66528639/170826769-1ff21b6b-cd1f-41f6-a782-0fec73b43832.jpg)
 <br />CPU Design
 <br />![1_PC](https://user-images.githubusercontent.com/66528639/170826566-3a757611-9765-4379-8006-793f025cfbac.jpg)
 <br />Program Counter
 <br />![2_Fetch_logic](https://user-images.githubusercontent.com/66528639/170826594-21422141-77e2-49e6-8afd-3dcd12506993.jpg)
 <br />Fetch Logic
 <br />
 <br />![3_Instruction_Decode_logic](https://user-images.githubusercontent.com/66528639/170826602-339c2008-1bd2-4d5d-b7aa-d01ec051f45c.jpg)
 <br />Instruction Decode Logic
 <br />
 <br />![4_Instruction_imm_decode](https://user-images.githubusercontent.com/66528639/170826611-ef14cb66-1c2a-4db8-b739-231c55e9adcb.jpg)
 <br />Instruction Immediate Decode
 <br />![5_instruction_decode](https://user-images.githubusercontent.com/66528639/170826623-ee832032-51a4-4874-bba0-5e1948f7907e.jpg)
 <br />Instruction Decode  <br />
 <br />![6_Instruction_Field_decode](https://user-images.githubusercontent.com/66528639/170826637-8c60e630-f457-4924-a724-e7e531a84dc0.jpg)
  <br />Instruction Field Decode
  <br />
  <br />![7_instruction_Decode](https://user-images.githubusercontent.com/66528639/170826649-690b17ed-489e-40e5-802e-75761c4eff61.jpg)
  <br />Instruction Decode
  <br />
  <br />![8_reg_file_read](https://user-images.githubusercontent.com/66528639/170826661-15880bb7-1055-4baf-a028-d17e66d6e827.jpg)
  <br />Register Field Read
  <br />
  <br />![9_ALU](https://user-images.githubusercontent.com/66528639/170826683-ddfe0159-e89f-4b0d-a606-728009edeeeb.jpg)
  <br />ALU
  <br />
  <br />![10_Branch_Instructions](https://user-images.githubusercontent.com/66528639/170826694-549e62e5-c47d-4463-810a-190a41a107e7.jpg)

   <br />Branch Instruction
   <br />
   <br />![11_CPU](https://user-images.githubusercontent.com/66528639/170826715-5f17e850-35e3-4374-9ba8-8e67e033e450.jpg)
   <br />RISC V CPU Design






