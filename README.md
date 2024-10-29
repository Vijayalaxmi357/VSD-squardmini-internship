

# RISCV_VSD_SquadronMini internship
## Lab exercises of RISCV workshop by Kunal Ghosh
## Instructor : Kunal Ghosh

### PRE-REQUISITE: Installing the required applications for the workshop - Virtual Box, Ubuntu on VBBOX and VDI files

## TASK-1: 
## A: Write a simple C code and compile it with gcc comipler. 
## B: Compile the same code with RISCV comipler to generate the assembly code for the same. Further Evaluate RISCV assembly code for the sample C code with two different options of comiplation.

## NECESSARY INSTALLATIONS
### Step 1: Setting up the virtual environment to work on
- Install Oracle Virtual Box, VMBox<br/>
- Launch Virtual Machine on VMBox<br/>
- Attach the VDI file to the Virtual Machine instance in VMBox<b>
-open the Virtual oracle<br>
![image](C:\Users\vijay\Pictures\Screenshots\Screenshot 2024-10-26 120841.png)
click on  "Show"<br>
 you will Enter to "ubuntu"<br>
 ![image](C:\Users\vijay\Pictures\Screenshots\Screenshot 2024-10-26 121056.png)
 -Right click and click on "open terminal"<br>

### Step 2: Type the word "gedit"-a word "gedit" is editor

### TASK 1A - COMPILE AND EXECUTE A SIMPLE C CODE USING GCC COMPILER
    $   cd <br/>                           Navigate to home directory:<br>
    $   gedit filename.c & <br/>         This opens a blank file with filename.c, type the c code
    
![oracle VMBox](https://github.com/user-attachments/assets/ec510c91-5706-4d7f-abd5-e825ae070f5e)
![login](https://github.com/user-attachments/assets/e4a40158-1875-4eb2-adc1-0f23a57f1025)

Save the file<br> 
Come back to terminal<br>
Press entre to come to the home prompt<br>
To see the results Run the following commands

    $    gcc filename.c <br>
    $    ./a.out <br>
![open terminal](https://github.com/user-attachments/assets/0240e637-7e73-43dc-b563-30a3ee793034)
![gedit](https://github.com/user-attachments/assets/a6e3c9c5-35de-45fa-8165-34ea4e4307de)

Change the value of n in filename.c <br>
Recompile and see the results <br>
To see the code in terminal type as cat sum1ton.c<br>
![cat sum1ton](https://github.com/user-attachments/assets/615382a8-e491-41a4-affc-dbbf6eb0daa4)

To get riscv assembly code the command is<br>
![riscv](https://github.com/user-attachments/assets/a0d99dc6-5f12-4d19-92d0-357dc59c03b9)

for only required code type "less" and search for" /main"<br>
![assembly](https://github.com/user-attachments/assets/5451aea1-152f-4bed-91b2-22f2c9cfb19e)

![req assembly code](https://github.com/user-attachments/assets/ccbcd4eb-c58c-4d16-ba64-d64122d4416e)




