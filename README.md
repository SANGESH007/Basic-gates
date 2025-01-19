
# Basic Gates Schematic to Layout in 90nm

This repository Contains the Basic gates such as Not, Nand, Nor, Xor, Xnor, And & OR gates from schematic to layout generation using cadence virtuoso.

## Inverter

This is a Symmetric inverter where the Pmos and Nmos sizes are calculated.\
Pmos: \
W = 415n \
L = 100n

Nmos: \
W = 120n \
L = 100n 

### Schematic
![Screenshot 2025-01-20 001257](https://github.com/user-attachments/assets/068304d3-b323-4ab5-9225-7ab8c5766a15)

### Symbol
![Screenshot 2025-01-20 001325](https://github.com/user-attachments/assets/c2850920-df54-4425-a721-743e9af6312d)

### TestBench
![Screenshot 2025-01-20 001414](https://github.com/user-attachments/assets/bd402038-81c9-469e-bd66-5b7bc9a108c5)

### Layout
![Screenshot 2025-01-20 002117](https://github.com/user-attachments/assets/745c6253-f48f-48ff-98c2-cee7c20c69ab)

### DRC check
![Screenshot 2025-01-13 220416](https://github.com/user-attachments/assets/0f828849-3905-40cd-bba6-1912c3aafe58)

### LVS check
![Screenshot 2025-01-13 220619](https://github.com/user-attachments/assets/471da88d-33cd-4f3f-a5f5-1240219d642b)

### RC Extraction
![Screenshot 2025-01-13 220835](https://github.com/user-attachments/assets/f023c532-d13f-4a95-a692-9921ac263a6e)

![Screenshot 2025-01-20 002203](https://github.com/user-attachments/assets/b58e74fa-24d3-49e2-8be4-c790a5f67df8)

### Layout Vs Schematic

#### Dc Analysis
![Screenshot 2025-01-13 222753](https://github.com/user-attachments/assets/aeca650e-0d24-4629-ae08-f7fe807db62c)

### Transient Analysis
![Screenshot 2025-01-13 225003](https://github.com/user-attachments/assets/dd137174-0df3-48c8-9137-5d782093b88c)


Delay b/w Schmatic and Layout = 4.17852 ps
![Screenshot 2025-01-13 230025](https://github.com/user-attachments/assets/4b078536-0bd0-4948-9c0a-65286950b6e1)
