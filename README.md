
This repository contains a robotics project developed using VAL3 and a Staubli TX60 industrial robot.
The objective of the project is to implement an automated pick-and-place assembly process for a mechanical part composed of a cylinder and a piston.

## Project Overview

The robotic system performs the following sequence:

1. Picks a cylinder from a dispenser using a lateral tool  
2. Places the cylinder on the assembly base  
3. Picks a piston from a pallet using a tip tool  
4. Inserts the piston into the cylinder  
5. Transfers the assembled part to a ramp  

This process is repeated 8 times using loop-based logic to handle multiple parts automatically.

## Tools and Hardware

- **Robot:** Staubli TX60  
- **Programming language:** VAL3  
- **Tools:**
  - Lateral gripper (for cylinders)
  - Tip gripper (for pistons)

## Key Features

- Tool definition and calibration  
- Position acquisition and management  
- Linear and joint movements  
- Digital input/output handling for the dispenser  
- Nested loops for automatic multi-part assembly  
- User interface messages for execution monitoring  

## Project Structure

/src->VAL3 source code

## Autors

Eva Matabosch

Iman Tarfass



