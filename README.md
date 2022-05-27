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


