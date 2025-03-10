# EXPERIMENT--01-ALP-FOR-8086
### Name : Beatrice Thomas
### Roll no: 212223110005
### Date of experiment : 10/3/2005





## Aim: To Write and execute ALP on fundamental arithmetic and logical operations
## Components required: 8086  emulator 
## Theory 
Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.


 ## Running the Emulator :
1.	Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory
2.	  Run  emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color 
 
 
3.		write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,  DIVISION operations 

4.	 Compile the program and check for the errors 
5.	Run (once there is no syntax error) 

6.	Click OK to see/view the output of your program on the Emulator screen. 


7.	After running the program, another menu screen will be displayed, where you have the option to “View” symbol table,
8.	 


![image](https://user-images.githubusercontent.com/36288975/189273263-d65baae9-4b8f-4723-afb3-c0ffa4052b04.png)











9.	Click on emulate to start emulation 








![image](https://user-images.githubusercontent.com/36288975/189273273-9bb36ec1-e2e8-4892-8d35-37707332bfdc.png)








10.	If no errors are found click on run the program and check the status of various flags in the flags tab as shown below 






![image](https://user-images.githubusercontent.com/36288975/189273277-113a2a33-4a40-4ff8-95a5-ecd3a1f504fe.png)







## Programs for arithmetic  operations

## Addition of 8 bit ALP 
```
MOV AL,74H
MOV BL,69H
ADD AL,BL
HLT

```
## Subtraction of 8 bit ALP 
```
MOV AL,74H
MOV BL,69H
SUB AL,BL
HLT
```
## Multiplication of 8 bit ALP 
```
MOV AL,75H
MOV BL,32H
MUL BL
HLT

```
## Division of 8 bit ALP  
```
ORG 100h
MOV AL,68H
MOV BL,18H
DIV BL
HLT
ret
```

##  And of 8 bit ALP 
```
MOV AL,33H
MOV BL,44H
AND AL,BL
HLT
```

## Or of 8 bit ALP 
```
Mov AL,33H
Mov BL,44H
OR AL,BL
HLT
```
## Not of 8 bit ALP 
```
MOV AL,65H
NOT AL
HLT
```

## Xor of 8 bit ALP 
```
MOV AL,66H
MOV BL,77H
XOR AL,BL
HLT

```
## Output 


![Screenshot 2025-02-28 083000](https://github.com/user-attachments/assets/ddb444ca-bcd2-4df4-a678-07e4f8ef94a7)

![Screenshot 2025-02-28 083339](https://github.com/user-attachments/assets/2597cced-a276-47e2-bcfe-b430e4a4e88b)

![Screenshot 2025-02-28 084618](https://github.com/user-attachments/assets/cec93071-406f-47fc-86bd-858663691dd7)

![Screenshot 2025-02-28 085824](https://github.com/user-attachments/assets/4582f5aa-9904-4187-afcb-25c5942fadc4)

![Screenshot 2025-02-28 090443](https://github.com/user-attachments/assets/8298586c-d4d4-48d5-867e-3e6878cbbb40)

![Screenshot 2025-02-28 091320](https://github.com/user-attachments/assets/613bb80f-b651-4dc4-89c9-bbf7f8dd7c9e)
 
![Screenshot 2025-02-28 085242](https://github.com/user-attachments/assets/57f0a3b8-29fd-40a1-93c6-861d8b9a791b)


## Result :

 Thus execution of ALP on fundamental arithmetic and logical operations is successfully verified.



 








