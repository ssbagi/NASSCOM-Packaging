# NASSCOM-Packaging


# MODULE 1 : Packaging Evolution

In this module we learnt the Packaging of Chips from basic SOT to Advanced 2.5D/3D Packaging. The Chips are fabricated on Wafer after this we cannot use the die directly in real world. In real world when an product is created there involves multiple chips communicating with each other on PCB. Protection of semiconductor devices on die(e.g. Corrosion, moisture and physical damage). As an example shown in the video lecture below image. 

![image](https://github.com/user-attachments/assets/b65406a9-2424-45df-bd6b-c8d900e4c709)

Packaging and Testing Industry
![image](https://github.com/user-attachments/assets/0ace4a92-377b-4e5e-95bf-bc1e255f1f4f)

## Product Requirements 

The Package depends on following factors : 
1. Application
2. Form factor
3. Reliability and Durability
4. Cost
5. Thermal Dissipation
6. Pin Count (I/O pins)

![image](https://github.com/user-attachments/assets/a96a2930-1e42-4df3-bde9-1681c5c30808)

The Package structure is composed of Mold compound, die, Carrier and System Board(PCB). In below image we can see the sandwich of the components on top of each other.

![image](https://github.com/user-attachments/assets/04c03211-b5e7-483f-8461-f8cf950b36b7)

### Packages Available 
There are various packages available following are different types : 
1. Through-hole Mounting : 
  - DIP : Dual In-line package
  - TO  : Through Hole
  - PGA : Plastic Grid Array
    
2. Surface Mount Technology (SMT) :
   - QFN    : Quad Flat No Lead
   - QFP    : Quad Flat Package
   - CSP    : Chip Scale Package
   - PBGA   : Plastic Ball Grid Array
   - LGA    : Land Grid Array
   - PoP    : Package on Package
   - MCM    : Multi-Chip Module
   - CoWoS  : Chip on Wafer on Substrate.

The CoWoS latest technology where multiple dies side-by-side interposer enabling 2.5D and 3D stacking. This is used for meeting high performance and efficiency. It provides TSVs and micro-bumps for interconnects, reducing power consumption and improving signal integrity.

## Anatomy of Packages
In below screenshot we can see the Leadframe, BGA and Advanced package anatomy. 

![image](https://github.com/user-attachments/assets/fad18d46-3a92-46ac-981b-07a6c36faa68)

In Leadframe-CSP, QFN, QFP the internal structure how the die I/O ports are connected to external I/O pins using gold wire. 

In the PBGA and BGA the package substrate is present in b/w the die and external I/O balls. 

In Advanced packages substrates we have RDL, Interposer (Si, Organic) for connecting multipl die in 2D, 2.1D, 2.3D and 2.5D. The Advanced and latest 2.5D is CoWoS. 

### Summary : Nomenclature of Packages

![image](https://github.com/user-attachments/assets/f155e25d-de33-40d8-a8f3-77181bc66e16)

### Comparison
Based on the application we choose the IC packages. As an example in below sceenshot we can see listed applications based on different IC package type. 

![image](https://github.com/user-attachments/assets/c2f44588-da63-4759-a251-f3ac89f0232f)


# MODULE 2 : Wafer to Package: Assmebly and Manfacturing Essentials 

The Supply Chain is composed of following steps : 

1. Design House
2. Wafer Fabrication.
3. Package Assembly and Test.
4. Board Assembly and Test.
5. Product Assembly and Test.

![image](https://github.com/user-attachments/assets/3c2f43b3-d516-434a-8710-a719fced48c4)

Introduction of a Package Manufacturing Unit : ATMP and OSAT.

![image](https://github.com/user-attachments/assets/95c78584-4a99-4596-bc45-fafce4f32c25)

The process happening inside the Cleanroom Area. The Amkor Manfucturing video shows the process from Wafer to Packaged die. 

![image](https://github.com/user-attachments/assets/7393d062-b7ba-4b48-91e8-2fe981f7774c)

The below image shows the steps from Bump formation on Si to Packaged. 

![image](https://github.com/user-attachments/assets/5e013faf-8d11-4ba0-b50d-779604941eb8)

![image](https://github.com/user-attachments/assets/5b64d164-2d04-4fed-87a6-a6d39c0b069a)


# Module 3 : Lab Session

Ansys Tool IcePack Design : 

![image](https://github.com/user-attachments/assets/6fc957bb-8c68-43f7-995d-b1850ecda768)

The Flipchip BGA Package Tool built in selection :
![image](https://github.com/user-attachments/assets/abced30c-bdf9-44cc-a7f7-0efcf1886cbf)

Dimension : 
![image](https://github.com/user-attachments/assets/ff218744-6127-4a46-b3f6-4c6244e6b221)

Die Dimension :
![image](https://github.com/user-attachments/assets/61eccf39-c088-4178-901e-f31c3331592d)

Substrate Option :
![image](https://github.com/user-attachments/assets/894c95b8-dafc-452b-918c-c5d252a64424)

Solder Option : 
![image](https://github.com/user-attachments/assets/106c26d4-08f9-40fe-bca8-1ec1b3b24dee)

The 3D Model gets created automatic : 
If we observe on left side we have Model option. In this Solids menu we have : 
1. Cu-Pure
2. FlipChip BGA1 Substrate material
3. FlipChip BGA1 Underfill material
4. FlipChip BGA1 via material
5. Si-Typical
6. Solder-pb50_sn50

![image](https://github.com/user-attachments/assets/ef62eb3b-8cee-46c2-8a44-eb2affd30d06)

The BGA1 ball :
![image](https://github.com/user-attachments/assets/4504eb67-776d-46f3-bdba-592f7bfbb5bb)

The Sandwich of Mold, die, substrate and BGA pins.
![image](https://github.com/user-attachments/assets/ad28cd7d-f75e-4b70-b8d3-cf40ba742420)

The Mesh Generation :
![image](https://github.com/user-attachments/assets/346f44f2-114b-4dcb-845a-1d87fc4c1291)

Validate the Design :
![image](https://github.com/user-attachments/assets/d44033db-efed-448a-9196-f004fa923788)

![image](https://github.com/user-attachments/assets/295a876f-b48d-499f-967e-91f17e453506)

Temperature Plot : 
![image](https://github.com/user-attachments/assets/ec34b993-870e-4272-8351-5d3b94524958)



# Module 4 

## Package Testing
The OSAT facility does the Testing at initial stage and then at the end of Package they do Electrical, burn-in and reliability chamber tests.
The Main Testing steps are : 
1. AOST        : Assembly Open and Short Test. If there are any opens or short happened during the Package which will lead to errornous output.
2. Burn-in     : Apply thermal and voltage stress to ensure early-life reliability. The Industry Grades like Automotive, Industrial and Commerical with varing different temperatures and voltages for each application. 
3. Final Test  : Cold and Hot test for validating functional, parametric and reliability specs across temperature. At the end few testcase scenarios are evalutaed. 

![image](https://github.com/user-attachments/assets/6c1ab656-bdac-4fdb-a36c-88feacf93cbb)

![image](https://github.com/user-attachments/assets/e139a59a-721c-48c0-808c-9cc2260b67f9)

### AOST - Functionality

![image](https://github.com/user-attachments/assets/60814c07-502d-4ab1-8393-1e3ea9b37889)

### Burn-in Test

![image](https://github.com/user-attachments/assets/c6358c7b-829b-458a-a2a3-896e85b4e913)

### Final Test

![image](https://github.com/user-attachments/assets/53371d7c-55e4-4f02-8ba3-73bf0f1d8cc7)

### Summary: ATE and Test categories

![image](https://github.com/user-attachments/assets/7e71209b-5f0f-4b59-81f3-c38f1539600d)





















