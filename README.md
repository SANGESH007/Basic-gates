
# Basic Gates Schematic to Layout in 90nm

This repository Contains the Basic gates such as Not, Nand, Nor, Xor gates from schematic to layout generation using cadence virtuoso.

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

## NAND

This is a Symmetric Nand where the Pmos and Nmos sizes are calculated.\
Pmos: \
W = 120n \
L = 100n

Nmos: \
W = 165n \
L = 100n 

### Schematic
![Screenshot 2025-01-18 193622](https://github.com/user-attachments/assets/84ece7b3-ceb0-45ad-a106-a9cf0ffd1695)

### Symbol
![Screenshot 2025-01-21 005501](https://github.com/user-attachments/assets/57ac037f-a349-466c-be71-57b420fff176)

### TestBench
![Screenshot 2025-01-21 005625](https://github.com/user-attachments/assets/c4a9c52c-3096-46a4-b13a-e0a670533b10)

### Layout
![Screenshot 2025-01-21 005202](https://github.com/user-attachments/assets/943b0531-6d31-405d-90b9-6293926c025d)

### DRC check
![Screenshot 2025-01-18 193255](https://github.com/user-attachments/assets/8d2e23d4-611a-4650-a728-f6821115c77f)

### LVS check
![Screenshot 2025-01-18 193504](https://github.com/user-attachments/assets/08bae571-571e-45a0-8cff-72255bcd5637)

![Screenshot 2025-01-18 193543](https://github.com/user-attachments/assets/8b2dcdba-ae59-4168-92a7-daf3cc1beb43)

### RC Extraction
![Screenshot 2025-01-18 193828](https://github.com/user-attachments/assets/59a1605a-4ae3-4c55-a7af-2162055c9933)
![Screenshot 2025-01-21 004844](https://github.com/user-attachments/assets/0b5e11e1-402c-4c74-91cb-78e1235de40f)

### Layout Vs Schematic

#### Dc Analysis
![Screenshot 2025-01-21 003828](https://github.com/user-attachments/assets/eb579c96-3259-4a65-92d7-3f68315b253b)

### Transient Analysis
![Screenshot 2025-01-21 004451](https://github.com/user-attachments/assets/40355bc2-0409-46de-8a10-004ee92b2a27)

![Screenshot 2025-01-21 004646](https://github.com/user-attachments/assets/220755e5-eac5-4fef-b14d-e3b939442416)

Delay b/w Schmatic and Layout = 5.3173 ps

## Nor

This is a Symmetric Nor where the Pmos and Nmos sizes are calculated.\
Pmos: \
W = 1.9u \
L = 100n

Nmos: \
W = 120n \
L = 100n 

### Schematic
![Screenshot 2025-01-21 010623](https://github.com/user-attachments/assets/706fa3da-ca7c-40fa-8441-5e07b59fc61d)

### Symbol
![Screenshot 2025-01-21 012426](https://github.com/user-attachments/assets/8a096cd9-3c0a-419c-ad80-88b64853f6c4)


### TestBench
![Screenshot 2025-01-21 012443](https://github.com/user-attachments/assets/07a3a556-4e74-48dc-86c8-b0f32c1c7fbe)

### Layout
![Screenshot 2025-01-21 010655](https://github.com/user-attachments/assets/33e1b21d-b995-48e3-b7a9-c9c640a1f459)

### DRC check
![Screenshot 2025-01-19 151747](https://github.com/user-attachments/assets/ac9225f7-c02d-4bfa-8394-59e5c2f8b353)

### LVS check
![Screenshot 2025-01-19 151841](https://github.com/user-attachments/assets/d477ac26-e145-47ba-ae8d-088b7f46c781)
![Screenshot 2025-01-19 151904](https://github.com/user-attachments/assets/e0b31791-34d0-447c-9601-77db0e7e805a)

### RC Extraction
![Screenshot 2025-01-19 152012](https://github.com/user-attachments/assets/e5abc4d8-5bb5-4f0d-9f41-b4935c2589a8)
![Screenshot 2025-01-21 010712](https://github.com/user-attachments/assets/173d8828-443f-4f58-8eca-29bda0f7632b)

### Layout Vs Schematic

#### Dc Analysis
![Screenshot 2025-01-18 235707](https://github.com/user-attachments/assets/41e33035-7192-46ee-936f-b34b5186aab6)

### Transient Analysis
![Screenshot 2025-01-21 011749](https://github.com/user-attachments/assets/49ff06b4-5989-4a8c-879f-5c41612224ea)
![Screenshot 2025-01-21 011932](https://github.com/user-attachments/assets/b549fe60-aca6-4315-90c9-7cbb9bb7df88)

Delay b/w Schmatic and Layout = 2.5987 ps

## XOR

This is a Symmetric Xor where the Pmos and Nmos sizes are calculated.\
Pmos: \
W = 120n \
L = 100n

Nmos: \
W = 120n \
L = 100n 

### Schematic
![Screenshot 2025-01-21 013731](https://github.com/user-attachments/assets/ada2ac64-0323-4801-b997-cd5d2459cb42)

### Symbol
![Screenshot 2025-01-21 013744](https://github.com/user-attachments/assets/a95531b8-e975-4ee4-8e92-d2b1cf40bb21)

### TestBench
![Screenshot 2025-01-21 014120](https://github.com/user-attachments/assets/1f7402e3-589c-4a37-9fc3-1d651e3242e9)

### Layout
![Screenshot 2025-01-21 013919](https://github.com/user-attachments/assets/fc14ea6b-5ded-4de1-ba28-af88601a06aa)

### DRC check
![Screenshot 2025-01-19 230429](https://github.com/user-attachments/assets/837f5df6-bd19-452f-9d0e-1084f5494abe)

### LVS check
![Screenshot 2025-01-19 230504](https://github.com/user-attachments/assets/6e2f1071-f58f-4f93-9ff6-97cc94561b9b)
![Screenshot 2025-01-19 230605](https://github.com/user-attachments/assets/39ee8d97-f68e-48e6-ad0b-d773433acd79)

### RC Extraction
![Screenshot 2025-01-21 013937](https://github.com/user-attachments/assets/72872f5c-5946-4934-8ae6-3ffec8191096)

### Layout Vs Schematic

#### Dc Analysis
![Screenshot 2025-01-21 015739](https://github.com/user-attachments/assets/514b5c56-0550-4e88-9616-d288ba13359a)

### Transient Analysis
![Screenshot 2025-01-21 014549](https://github.com/user-attachments/assets/f5312bb7-33fb-418b-ab36-e4799fe413e3)
![Screenshot 2025-01-21 014824](https://github.com/user-attachments/assets/8145aa06-25fa-4a98-903d-b4266e4f1556)
![Screenshot 2025-01-21 015013](https://github.com/user-attachments/assets/9a4d8b12-b307-4cd9-b837-1bce25361aca)

Delay b/w Schmatic and Layout = 14.23 ps
