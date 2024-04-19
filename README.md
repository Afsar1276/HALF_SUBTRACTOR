# HALF_SUBTRACTOR
# AIM:
To simulate and synthesis half subtractor using vivado.
# APPARATUS REQUIRED:
vivado 2023.2 software.
# PROCEDURE:
```
STEP:1 Start the vivado software, Select and Name the New project.
STEP:2 Select the device family, device, package and speed.
STEP:3 Select new source in the New Project and select Verilog Module as the Source type.
STEP:4 Type the File Name and module name and Click Next and then finish button. Type the code and save it.
STEP:5 Select the run simulation and then run Behavioral Simulation in the Source Window and click the check syntax.
STEP:6 Click the simulation to simulate the program and give the inputs and verify the outputs as per the truth table.
STEP:7 compare the output with truth table.
```
# Truth Table
![image](https://github.com/RESMIRNAIR/HALF_SUBTRACTOR/assets/154305926/d0d5980a-6bcf-4ede-a54e-6aae3fb5f5f2)
# Circuit Diagram
![image](https://github.com/RESMIRNAIR/HALF_SUBTRACTOR/assets/154305926/df70da69-5a12-4a0d-ab84-a98dad3f7e70)
![image](https://github.com/RESMIRNAIR/HALF_SUBTRACTOR/assets/154305926/2f2d6a4d-9eda-4165-8579-1d7490b5fe97)
# VERILOG CODE:
# HALF_SUBTRACTOR:
```
module half_subtractor (a,b,diff, borr);
input a,b;
output diff, borr;
wire x;
xor (diff,a,b);
not (x,a);
and (borr,x,b);
endmodule
```
# OUTPUT:
[image]![WhatsApp Image 2024-03-25 at 14 00 13_e169601e](https://github.com/Afsar1276/HALF_SUBTRACTOR/assets/161407741/938fe03a-5cec-4d7a-9c1f-d0ceee37c2fc)
# RESULT:
Thus the verilog program for half subtractor has been simulated and verified successfully.
