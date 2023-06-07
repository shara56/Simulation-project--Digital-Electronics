# TITTLE

Design and simulate 7bit gray to binary coverter using verilog

# Equipments Required:

Hardware – PCs, Cyclone II , USB flasher Software – Quartus prime Theory Adders are digital circuits that carry out addition of numbers.

# ALGORITHM:
```
STEP 1:
Launch Quartus and create a new project.

STEP 2:
Specify the project name, location, and target device family and device.

STEP 3:
Choose a new empty project or import existing files if you have any.

STEP 4:
Click "Finish" to create the project.

STEP 5:
In the project window, right-click on the project name and select "New > Verilog HDL File."

STEP 6:
Provide a name for the Verilog file (e.g., gray_to_binary.v) and click "OK."

STEP 7:
In the text editor that opens, write the Verilog code for the Gray to Binary code converter, as shown earlier.

STEP 8:
Save the Verilog file.
```
# PROGRAM
```
DEVELOPED BY: SHARANGINI T.K
REFERENCE NO: 212222230143
```
# CODE:
```
module model (
  input wire [3:0] gray,
  output reg [3:0] binary
);

  always @* begin
    binary[3] = gray[3];
    binary[2] = binary[3] ^ gray[2];
    binary[1] = binary[2] ^ gray[1];
    binary[0] = binary[1] ^ gray[0];
  end

endmodule
```
# LOGIC DIAGRAM

![image](https://github.com/shara56/Simulation-project--Digital-Electronics/assets/113497104/b6a6220e-a176-496a-ba7c-878ce9715bde)


# TIMING DIAGRAM

![image](https://github.com/shara56/Simulation-project--Digital-Electronics/assets/113497104/534e54b0-da6d-4e0c-9924-de8312754f87)


# TRUTH TABLE:

![image](https://github.com/shara56/Simulation-project--Digital-Electronics/assets/113497104/2161c512-319b-450c-b8b8-986a67d8a06f)


# RESULT:

Thus the Implementation of gray to binary code are studied and the truth table are verified.
