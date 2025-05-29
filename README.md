

# Finite Element Analysis (FEA) Case Studies

_A collection of advanced FEA simulations in structural analysis, material behavior, and engineering applications._

![banner - plane1](https://github.com/user-attachments/assets/02ff88d1-b9ff-4718-93c6-c814a003cbdd)


</header>

## Overview

This repository presents a comprehensive collection of **Finite Element Analysis (FEA) case studies**, demonstrating various engineering applications using **Ansys** and other numerical simulation tools. The examples include:

- Structural mechanics simulations
- Material failure analysis
- Thermal and fluid interactions
- Nonlinear and dynamic analyses
- Custom scripting and automation in FEA

## Featured Case Studies

### 1️⃣ **Beam Bending Analysis: Shear and Moment Diagrams**
- **Objective**: Evaluate deflection, shear, and moment in a simply supported I-beam under concentrated and distributed loads. Compare analytical and FEA results.
- **Methods**: Linear static analysis using line elements. Simply supported boundary condition on one end and roller support on the other.
- **Results**: Visualization of deflection, shear, and moment diagrams. Close agreement between analytical and FEA results.

![1_Beam shear and moment analysis](https://github.com/user-attachments/assets/697c0bd1-b032-4770-9d0b-d1740b6b47c8)


---

### 2️⃣ **Truss Bridge: Boundary Conditions**
- **Objective:** Analyze deflections at each joint of a wooden truss bridge under given loading conditions.
- **Methods:** Finite element analysis using truss and beam elements. Different boundary condition applications, including pinned and roller supports, are explored. Apply pinned support boundary conditions using three methods: simply supported, displacement, and remote displacement.
- **Results:** Comparison of deflections for different support conditions and validation with theoretical predictions.

![2_Wooden Truss bridge - Boundary Conditions](https://github.com/user-attachments/assets/6ab827c3-9cdd-409c-a6c6-fc5f394e2ec9)

- **Source:** Chen X, Liu Y. *Finite Element Modeling and Simulation with ANSYS Workbench.* CRC Press; 2018: Case Study 2.6.

---

### 3️⃣ **Steel Frame: Beams Alignment**
- **Objective:** Evaluate deformations and stresses in a two-story structural steel frame under uniform loading, with and without a deck on the first floor.
- **Methods:** 3D beam element analysis using Ansys Workbench. The importance of correct I-beam alignment in DesignModeler or SpaceClaim is highlighted.
- **Results:** Stress and deformation distributions. Comparison of frame deformations with and without a deck on the first floor.

![3_3D Steel Frame - Beams Alignment](https://github.com/user-attachments/assets/e98848fa-327c-42d6-83a7-edb782c84d47)

- **Source:** Chen X, Liu Y. *Finite Element Modeling and Simulation with ANSYS Workbench.* CRC Press; 2018: Case Study 3.6.

---

### 4️⃣ **Steel Wrench: 2D Plane Stress vs. 3D Model**
- **Objective:** Analyze the deformation and von Mises stress of a stainless steel wrench under applied torque.
- **Methods:** 2D plane stress vs. full 3D solid modeling for comparative evaluation.
- **Results:** 2D and 3D model results are compared, showing that stress differences are more significant than displacement variations.  

![4_Steel Wrench - 2D Plane Stress vs 3D model](https://github.com/user-attachments/assets/1f7f0ec0-034b-4e58-8c81-9efb3d3d0774)

- **Source:** Chen X, Liu Y. *Finite Element Modeling and Simulation with ANSYS Workbench.* CRC Press; 2018: Case Study 4.5.

---

### 5️⃣ **Axisymmetric Garden Fountain**
- **Objective:** Investigate deformation and von Mises stress in a concrete garden fountain under hydrostatic pressure.
- **Methods:** Axisymmetric finite element modeling using a 2D slice of the 3D geometry. Adaptive meshing is applied to improve solution accuracy and convergence.
- **Results:** Stress and deformation contours. Validation of axisymmetric approach.  

![5_Axisymmetric Garden Fountain](https://github.com/user-attachments/assets/50de0926-b482-4da4-a9e6-8ac9edac8d6f)

- **Source:** Chen X, Liu Y. *Finite Element Modeling and Simulation with ANSYS Workbench.* CRC Press; 2018: Case Study 5.8.

---

### 6️⃣ **Glass Vase**
- **Objective:** Assess structural integrity of a glass vase under hydrostatic pressure.
- **Methods:** Finite element analysis of a thin-walled glass structure with uniform thickness.
- **Results:** Maximum deformation and stress distribution under fluid pressure effects.  

![6_Glass Vase](https://github.com/user-attachments/assets/13e8dffa-a7bf-40be-b178-63c46df0a75f)

- **Source:** Chen X, Liu Y. *Finite Element Modeling and Simulation with ANSYS Workbench.* CRC Press; 2018: Case Study 6.5.


---

### 7️⃣ **Base Stand Assembly**
- **Objective**: Determine deformation and von Mises stress distributions in a base stand assembly under given load and boundary conditions.
- **Methods**: Apply no-separation contact conditions. Align pin with base leg for axisymmetric study.
- **Results**: Stress and deformation contours. Validation of contact conditions.
 
![7_Base Stand Assembly](https://github.com/user-attachments/assets/9abf35e2-9454-4356-80cd-ab72a1dabcc1)

- **Source:** Chen X, Liu Y. *Finite Element Modeling and Simulation with ANSYS Workbench.* CRC Press; 2018: Case Study 7.3.  

---

### 8️⃣ **Acoustic Guitar**
- **Objective**: Find natural frequencies, vibration modes, and frequency response of an acoustic guitar under harmonic pressure loading.
- **Methods**: Use 3D shell vs solid elements. Apply fixed boundary conditions and harmonic pressure load.
- **Results**: First ten natural frequencies. Visualization of first five vibration modes and frequency response.

![8_Acoustic Guitar](https://github.com/user-attachments/assets/c332af3a-adee-488e-9daf-feaa17bc432d)

- **Source:** Chen X, Liu Y. *Finite Element Modeling and Simulation with ANSYS Workbench.* CRC Press; 2018: Case Study 8.2.  

---

### 9️⃣ **Heat Sink: Steady and Transient Heat Transfer**
- **Objective**: Study steady-state and transient thermal responses of an aluminum heat sink under heat flux and forced convection.
- **Methods**: Apply heat flux and convective boundary conditions. Perform steady-state and transient analyses.
- **Results**: Temperature distributions and thermal stress responses. Transient thermal behavior over 180 seconds.

![9_Heat Sink - Steady and Transient Heat Transfer](https://github.com/user-attachments/assets/3b394d6c-ad35-4e4e-95f6-11c02f05f8f2)

- **Source:** Chen X, Liu Y. *Finite Element Modeling and Simulation with ANSYS Workbench.* CRC Press; 2018: Case Study 9.4.  

---

### 🔟 **Vehicle Aerodynamics**
- **Objective**: Analyze airflow patterns, pressure, and velocity distributions around a truck at 40 km/hr.
- **Methods**: Use CFX and Fluent for fluid analysis. Apply inlet, outlet, openning/symmetry, and wall non-slip boundary conditions.
- **Results**: Flow patterns, pressure, and velocity contours. Comparison of CFX and Fluent results.

![10_Vehicle Aerodynamics](https://github.com/user-attachments/assets/08ea3e60-6f42-46fa-9218-3a04f0af4b32)

- **Source:** Chen X, Liu Y. *Finite Element Modeling and Simulation with ANSYS Workbench.* CRC Press; 2018: Case Study 10.6.  

---

### 1️⃣1️⃣ **Optimization Study of L-Shaped Structure**
- **Objective**: Perform topology and parametric optimization to achieve 75% weight reduction while meeting deformation constraints.
- **Methods**: Apply downward force and fixed boundary conditions. Use topology and parametric optimization tools.
- **Results**: Optimized geometry with reduced weight. Validation of deformation constraints.
  
![11_Optimization Study of L-Shaped Structure](https://github.com/user-attachments/assets/7b2836da-2e6e-4225-8c2e-09a4e8e1793a)

- **Source:** Chen X, Liu Y. *Finite Element Modeling and Simulation with ANSYS Workbench.* CRC Press; 2018: Case Study 11.3.  

---

### 1️⃣2️⃣ **Static, Fatigue, and Buckling Failures**
- **Objective**: Evaluate static, fatigue, and buckling failures in a dog-bone-shaped specimen under static and cyclic loading.
- **Methods**: Apply static pressure and cyclic loads. Perform static, fatigue, and buckling analyses.
- **Results**: Plastic deformation, fatigue life, and buckling mode shapes. Validation of failure criteria.

![12_static fatigue and buckling failures](https://github.com/user-attachments/assets/2bbcfc41-e43f-44da-be33-2aec071ced6d)

- **Source:** Chen X, Liu Y. *Finite Element Modeling and Simulation with ANSYS Workbench.* CRC Press; 2018: Case Study 12.4.  


---

### 1️⃣3️⃣ **Control Box Cover Analysis**  
- **Objective:** Verify structural integrity of an aluminum control box cover under external pressure (1.0 MPa).  
- **Methods:** Static structural analysis using a STEP model to evaluate stress distribution.  
- **Results:** Assessment of deformation and safety factor.  

![13_Control Box Cover](https://github.com/user-attachments/assets/c7a61a27-2e94-4b5c-8240-3e05867641db)

- **Source:** ANSYS Mechanical Application Introductory Training Course (2015, ANSYS, Inc.)  

---

### 1️⃣4️⃣ **2D Gear and Rack Analysis**  
- **Objective:** Analyze the interaction between a spur gear and rack under a 2500 N hand press force.  
- **Methods:** Plane stress analysis (thickness = 12 mm), evaluating force on the rack or moment on the gear.  
- **Results:** Contact stress distribution and gear deflection.  

![14_2D Gear and Rack Analysis](https://github.com/user-attachments/assets/318d9092-2904-41c9-975f-56914699d7e7)

- **Source:** ANSYS Mechanical Application Introductory Training Course (2015, ANSYS, Inc.)  

---

### 1️⃣5️⃣ **Beam Connections Using Object Generator**  
- **Objective:** Simplify the creation of multiple beam connections between two plates using automation.  
- **Methods:** Object Generator in ANSYS Mechanical, applying a 1000 N force to the bottom plate.  
- **Results:** Efficiency comparison between manual and automated beam connections.  

![15_Beam Connections using Object Generator](https://github.com/user-attachments/assets/07be1e55-68e8-4ed9-a4ae-db50e6ea5eb3)

- **Source:** ANSYS Mechanical Application Introductory Training Course (2015, ANSYS, Inc.)  

---

### 1️⃣6️⃣ **Named Selections + Object Generator**  
- **Objective:** Optimize preprocessing time by using named selections and Object Generator.  
- **Methods:** Automating body sizing and fixed support conditions to improve model setup.  
- **Results:** Reduction in setup time and improved workflow efficiency.  

![16_Named Selections - Object generator](https://github.com/user-attachments/assets/ccc6e874-a722-4a37-be65-b095ffc6d5f7)

- **Source:** ANSYS Mechanical Application Introductory Training Course (2015, ANSYS, Inc.)  

---

### 1️⃣7️⃣ **Assembly Meshing**  
- **Objective:** Generate an optimized mesh for a symmetric assembly using multiple meshing techniques.  
- **Methods:** Patch Independent, Patch Conforming, Sweep, Hex Dominant, and Face Meshing methods.  
- **Results:** Mesh quality evaluation and efficiency comparison. 
 
![17_Assembly Meshing](https://github.com/user-attachments/assets/ec384838-f408-4deb-846a-82523f2e1db4)

- **Source:** ANSYS Mechanical Application Introductory Training Course (2015, ANSYS, Inc.)  

---

### 1️⃣8️⃣ **Sequential Meshing**  
- **Objective:** Analyze the effects of different meshing sequences on computational accuracy.  
- **Methods:** Comparing meshing order using various element types.  
- **Results:** Impact of meshing order on analysis convergence and accuracy.
  
![18_sequential meshing](https://github.com/user-attachments/assets/6bdfca34-3f2e-45a1-883d-8b31253ab1b5)

---

### 1️⃣9️⃣ **Meshing Methods: Automatic vs. Multi-Zone**  
- **Objective:** Compare meshing efficiency and accuracy using different methods.  
- **Methods:** Evaluating automatic meshing with slicing against multi-zone meshing without slicing.  
- **Results:** Element quality, computational time, and solution accuracy.  

![19_Meshing - automatic method with slicing](https://github.com/user-attachments/assets/22b2c5f2-2fcc-4715-830f-cf498dcd5572)

---

### 2️⃣0️⃣ **Meshing Methods: Sweep, Multi-Zone, and Layered Tetrahedrons**  
- **Objective:** Evaluate different meshing techniques for complex geometries.  
- **Methods:**  
  - Sweep without inflation  
  - Sweep with inflation  
  - Multi-zone  
  - Layered tetrahedrons  
- **Results:** Comparison of mesh refinement, accuracy, and computational cost. 
 
![20_Meshing methods](https://github.com/user-attachments/assets/8e9096be-d6f5-4989-98d8-e0e78dfc6f14)

---

### 2️⃣1️⃣ **Mesh Controls: Pinching and Virtual Topology**  
- **Objective:** Improve mesh quality in models with geometry defects using mesh controls.  
- **Methods:** Implementing pinch and virtual topology to refine meshing.  
- **Results:** Enhanced element quality and better stress convergence.  

![21_Mesh Controls - Pinching and Virtual Topology](https://github.com/user-attachments/assets/4c2fbc0f-02de-4f2c-9657-6dacd8a26199)

- **Source:** ANSYS Mechanical Application Introductory Training Course (2015, ANSYS, Inc.)  

---

### 2️⃣2️⃣ **Interference Treatment in a Piston Assembly**  
- **Objective:** Address non-physical results in a piston-valve assembly due to initial gaps.  
- **Methods:**  
  - Solve without interface treatment (baseline).  
  - Apply contact offset to close the gap and analyze results.  
- **Results:** Comparison of results with and without interface treatment. 
 
![22_Interference Treatment in a Piston Assembly](https://github.com/user-attachments/assets/6c656e98-038e-458f-845d-4badcd233cbf)

- **Source:** ANSYS Mechanical Application Introductory Training Course (2015, ANSYS, Inc.)  

---

### 2️⃣3️⃣ **Joints Connections of Assembly Parts**  
- **Objective:** Replace traditional contact definitions with joints in an assembly.  
- **Methods:** Using ANSYS automatic joint feature and modifying joint definitions before solving.  
- **Results:** Reduced computational cost and improved analysis efficiency.  

![23_Joints Connections of Assembly Parts](https://github.com/user-attachments/assets/4f092f1b-d9e2-4ce9-91d9-38a80b51a958)

- **Source:** ANSYS Mechanical Application Introductory Training Course (2015, ANSYS, Inc.)  

---

### 2️⃣4️⃣ **Jack Assembly: Remote Boundary Conditions**  
- **Objective:** Analyze the base of a vehicle jack under applied loads.  
- **Methods:**  
  - Simulating vehicle weight using a point mass.  
  - Applying lateral loads using remote forces.  
- **Results:** Structural response under realistic load conditions.  

![24_Jack Assembly - Remote Boundary Conditions](https://github.com/user-attachments/assets/c57a3c2c-a7e7-4505-8342-867acf95b118)

- **Source:** ANSYS Mechanical Application Introductory Training Course (2015, ANSYS, Inc.)  

---

### 2️⃣5️⃣ **Hook Fastener: Constraint Equations**  
- **Objective:** Simulate hook displacement using constraint equations.  
- **Methods:** Constructing an equation to relate Y-displacement to X-displacement.  
- **Results:** Prediction of hook deflection during assembly.  

![25_Hook Fastener - Constraint Equations](https://github.com/user-attachments/assets/0d01c669-d1a8-473f-86ec-bbde526412af)

- **Source:** ANSYS Mechanical Application Introductory Training Course (2015, ANSYS, Inc.)  

---

### 2️⃣6️⃣ **Impeller Pump: Linear Structural Analysis**  
- **Objective:** Evaluate the structural behavior of an impeller pump under load.  
- **Methods:**  
  - Applying a 100 N bearing load to the pulley.  
  - Checking impeller deflection and material stress limits.  
- **Results:** Deformation analysis and material safety assessment.  

![26_Impeller Pump - Linear Structural Analysis](https://github.com/user-attachments/assets/b055eda7-c001-4335-ac9b-fa04f29ee73f)

- **Source:** ANSYS Mechanical Application Introductory Training Course (2015, ANSYS, Inc.)  


---

### 2️⃣7️⃣ **Flange Mount: Beam Connections (Non-Linear Analysis)**  
- **Objective:** Simulate flange fasteners using beam elements and assess structural response.  
- **Methods:**  
  - Body-to-body bolt simulation.  
  - Applying a remote force (1000 N) at Z = 100 mm.  
- **Results:** Stress distribution and structural performance evaluation.  

![27_Flange Mount - Beam Connections](https://github.com/user-attachments/assets/6ebcf7ac-e014-4e41-a64d-28d7f5d29afc)

- **Source:** ANSYS Mechanical Application Introductory Training Course (2015, ANSYS, Inc.)  

---

### 2️⃣8️⃣ **Machine Frame: Free Vibration Analysis**  
- **Objective:** Investigate modal frequencies of a machine frame under different constraints.  
- **Methods:**  
  - Modal analysis with all 8 mounting holes constrained.  
  - Second analysis with only 4 corner holes constrained.  
- **Results:** Comparison of mode shapes and natural frequencies.  

![28_Machine Frame - Free Vibration Analysis](https://github.com/user-attachments/assets/826c3071-ed61-4463-8731-59a833b2c480)

- **Source:** ANSYS Mechanical Application Introductory Training Course (2015, ANSYS, Inc.)  

---

### 2️⃣9️⃣ **Pump Housing: Thermal Stress Analysis**  
- **Objective:** Compare heat transfer effects on a pump housing made of plastic vs. aluminum.  
- **Methods:**  
  - Applying boundary conditions:  
    - 60°C at the mounting face.  
    - 90°C internal temperature.  
    - Convection at 20°C external surface.  
- **Results:** Thermal expansion and stress comparison. 
 
![29_Pump Housing - Thermal Stress](https://github.com/user-attachments/assets/516fe527-852d-4cb2-91ef-78fa4c2a4f73)

- **Source:** ANSYS Mechanical Application Introductory Training Course (2015, ANSYS, Inc.)  

---

### 3️⃣0️⃣ **Pipe Clamp: Multi-Step Analysis**  
- **Objective:** Perform a sequential analysis of a pipe clamp under multiple loading steps.  
- **Methods:**  
  - Step 1: Bolt pretension (locked in later steps).  
  - Step 3: Internal pressure applied.  
  - Step 4: Axial force applied.  
- **Results:** Structural response under multi-step loading.  

![30_Pipe Clamp - Multistep Analysis](https://github.com/user-attachments/assets/f402da09-3448-420b-9317-38f0c20d5fb4)

- **Source:** ANSYS Mechanical Application Introductory Training Course (2015, ANSYS, Inc.)  

---


### 3️⃣1️⃣ **Mechanism Arm: Meshing Evaluation**
- **Objective:** Analyze how different mesh densities affect the quality of FEA results.
- **Methods:** Perform simulations using various mesh sizes to compare stress and deformation.
- **Results:** Evaluation of tensile and bending loads on the web section.

![31_Mechanism Arm - Meshing Evaluation](https://github.com/user-attachments/assets/959999d2-c17d-40bf-b5bf-d5a6fd368afe)

- **Source:** ANSYS Mechanical Application Introductory Training Course (2015, ANSYS, Inc.)

---

### 3️⃣2️⃣ **Steel Pipe: Linear Buckling Analysis**
- **Objective:** Verify linear buckling results for a steel pipe against handbook calculations.
- **Methods:** Apply a compressive load of 10,000 lbf to a fixed-free pipe model and determine its factor of safety.
- **Results:** Comparison of numerical and analytical buckling loads.

![32_Steel Pipe - Linear Buckling Analysis](https://github.com/user-attachments/assets/d344a824-de7c-4dcc-8bf4-f8deee91d410)

- **Source:** ANSYS Mechanical Application Introductory Training Course (2015, ANSYS, Inc.)

---

### 3️⃣3️⃣ **Submodeling**
- **Objective:** Improve accuracy by solving a full model (coarse mesh) and a submodel (fine mesh).
- **Methods:** Use ANSYS to extract a portion of the full model and refine the mesh for detailed analysis.
- **Results:** Comparison of coarse mesh full-model results with fine mesh submodel results.

![33_Submodeling](https://github.com/user-attachments/assets/c844af65-53c2-4e91-9c77-ffd6ea25f778)

- **Source:** ANSYS Mechanical Application Introductory Training Course (2015, ANSYS, Inc.)

---

### 3️⃣4️⃣ **Roll Cage: Structural Analysis**
- **Objective:** Assess the structural integrity of a roll cage under impact loading.
- **Methods:** Finite element simulation of impact forces and stress distribution.
- **Results:** Identification of high-stress areas and deformation under loading.

![34_Roll Cage - Structural Analysis](https://github.com/user-attachments/assets/68a7145a-064b-49cb-a9ae-e9e627d0148a)

---

### 3️⃣5️⃣ **Bridge: Transient Analysis**
- **Objective:** Study the dynamic response of a bridge structure under transient loading.
- **Methods:** Time-dependent simulation of varying loads and their effects on stress and displacement.
- **Results:** Visualization of transient response behavior.

![35_Bridge - Transient Analysis](https://github.com/user-attachments/assets/3fd073df-fa75-4131-82a4-35fcfaae2f8c)

---

### 3️⃣6️⃣ **Transmission Tower: Buckling Failure Analysis**
- **Objective:** Evaluate the risk of buckling failure in a transmission tower.
- **Methods:** Finite element analysis of compression-induced buckling.
- **Results:** Identification of weak points and safety factor assessment.

![36_Electricity Tower - Buckling Failure Analysis](https://github.com/user-attachments/assets/6946a9d8-e35c-4e0c-9b24-ec2659aea792)

---

### 3️⃣7️⃣ **Roll Cage: Modal vs Prestressed Modal**
- **Objective:** Compare natural frequencies in a roll cage with and without prestress effects.
- **Methods:** Modal analysis under two conditions: free vibration and prestressed state.
- **Results:** Influence of preloading on natural frequencies.

![37_Roll Cage - Modal vs Prestressed modal](https://github.com/user-attachments/assets/2d0abd57-01ff-46c9-95fe-037f82256e43)

---

### 3️⃣8️⃣ **Concrete Structure: Harmonic Analysis (Full vs Superposition)**
- **Objective:** Evaluate vibration response using full and superposition harmonic analysis.
- **Methods:** Conduct modal analysis followed by harmonic analysis.
- **Results:** Comparison of harmonic response in full mode and superposition approach.

![38_Concrete Structure - Harmonic Analysis](https://github.com/user-attachments/assets/4de8f945-0182-446c-b2c3-25309bc694db)

---

### 3️⃣9️⃣ **Compression Spring: Random Vibration Analysis**
- **Objective:** Analyze the effects of random vibration on a compression spring.
- **Methods:** Perform modal analysis followed by random vibration analysis.
- **Results:** Evaluation of spring deformation and stress distribution under random loading.

![39_Compression Spring - Random Vibration Analysis](https://github.com/user-attachments/assets/e095cf4b-7907-49da-929e-3830c6628925)

---

### 4️⃣0️⃣ **Steel Frame: Response Spectrum Analysis**
- **Objective:** Assess seismic response of a steel frame structure.
- **Methods:** Use response spectrum analysis to estimate peak responses.
- **Results:** Evaluation of structural stability under seismic loading.

![40_Steel Frame - Response Spectrum](https://github.com/user-attachments/assets/846a4afd-f8c8-41be-b880-24422d7c6e3b)

---

### 4️⃣1️⃣ **Crankshaft: Fatigue Failure Analysis**
- **Objective:** Predict fatigue life of a crankshaft under cyclic loading.
- **Methods:** Finite element analysis of stress cycles and damage accumulation.
- **Results:** Estimation of fatigue life and failure zones.

![41_Crankshaft - Fatigue Failure Analysis](https://github.com/user-attachments/assets/f6e82051-3dde-4982-b533-140ec36a9889)

---

### 4️⃣2️⃣ **Racing Car Frame Structure**
- **Objective:** Analyze deformation and stresses in a racing car frame.
- **Methods:** Finite element simulation of impact and loading conditions.
- **Results:** Identification of weak sections and structural improvements.

![42_CH3 Racing Car Frame Structure](https://github.com/user-attachments/assets/74c94ac9-2e4c-4e43-8846-970956d11e47)

- **Source:** Dechaumphai and Sucharitpwatskul. *Finite element analysis with ANSYS workbench*. Alpha Science International Limited, 2018, Ch.3.

---

### 4️⃣3️⃣ **Motorcycle Chain Wheel**
- **Objective:** Evaluate stress distribution in a motorcycle chain wheel.
- **Methods:** Apply torque and chain resistance force to analyze stress.
- **Results:** Identification of high-stress zones and failure risks.
  
![43_Ch4 Motorcycle Chain Wheel](https://github.com/user-attachments/assets/d2c967b7-c6da-4705-bfb6-d8386801aff0)

- **Source:** Dechaumphai and Sucharitpwatskul. *Finite element analysis with ANSYS workbench*. Alpha Science International Limited, 2018, Ch.4.

---

### 4️⃣4️⃣ **Shelf Angle Bracket**
- **Objective:** Assess deformation and stress in a shelf angle bracket.
- **Methods:** Simulate wall-mounted loading conditions.
- **Results:** Determination of maximum stress points and deformation.

![44_Ch5 Shelf Angle Bracket](https://github.com/user-attachments/assets/bd0c9a5d-5cc6-495d-83b9-5af5f1f70c04)

- **Source:** Dechaumphai and Sucharitpwatskul. *Finite element analysis with ANSYS workbench*. Alpha Science International Limited, 2018, Ch.5.

---

### 4️⃣5️⃣ **Aircraft Structural Component**
- **Objective:** Analyze an aircraft structural component under offset loading.
- **Methods:** Apply internal constraints and offset force, assess deflection and stress.
- **Results:** Structural integrity assessment and design verification.

![45_CH6 Aircraft Structural Component](https://github.com/user-attachments/assets/e872dad3-d4ab-4eeb-9ba1-315a8367879d)

- **Source:** Dechaumphai and Sucharitpwatskul. *Finite element analysis with ANSYS workbench*. Alpha Science International Limited, 2018, Ch.6.

---

### 4️⃣6️⃣ **Modal Analysis of Passenger Car Frame**
- **Objective:** Determine natural frequencies and mode shapes of a passenger car frame.
- **Methods:** Perform modal analysis using FEA.
- **Results:** Identification of primary vibration modes.

![46_Ch7 Modal Analysis of Passenger Car Frame](https://github.com/user-attachments/assets/8873a76e-451d-4d46-a919-4f9185016b82)

- **Source:** Dechaumphai and Sucharitpwatskul. *Finite element analysis with ANSYS workbench*. Alpha Science International Limited, 2018, Ch.7.

---

### 4️⃣7️⃣ **CBuckling of Detergent Bottle**
- **Objective:** Investigate the possibility of buckling in a detergent bottle.
- **Methods:** Analyze compressive loading and hydrostatic pressure effects.
- **Results:** Assessment of structural stability and design recommendations.

![47_CH8 Buckling of Detergent Bottle](https://github.com/user-attachments/assets/5b39c70e-7dc8-4ed8-8105-23894ca7eab6)

- **Source:** Dechaumphai and Sucharitpwatskul. *Finite element analysis with ANSYS workbench*. Alpha Science International Limited, 2018, Ch.8.

---

### 4️⃣8️⃣ **Fatigue and Life Prediction of Piston Rod**
- **Objective:** Estimate the lifespan of a piston rod under cyclic loading.
- **Methods:** Finite element fatigue analysis.
- **Results:** Prediction of failure locations and lifespan.

![48_Ch8 Fatigue and Life Prediction of Piston Rod](https://github.com/user-attachments/assets/54dcb1a4-27a9-4af7-8f36-fd6ccd957f89)

- **Source:** Dechaumphai and Sucharitpwatskul. *Finite element analysis with ANSYS workbench*. Alpha Science International Limited, 2018, Ch.8.

---

### 4️⃣9️⃣ **Thermal Stress in Combustion Engine Cylinder**
- **Objective:** Analyze temperature distribution, deformation, and thermal stresses in an engine cylinder.
- **Methods:** Simulate internal pressure, heat flux, and convection effects.
- **Results:** Evaluation of thermal stress and deformation.

![49_Ch9 Thermal Stress in Combustion Engine Cylinder](https://github.com/user-attachments/assets/e8c3af4d-68f3-4200-9dc4-71cc724c4564)

- **Source:** Dechaumphai and Sucharitpwatskul. *Finite element analysis with ANSYS workbench*. Alpha Science International Limited, 2018, Ch.9.

---




[➡ View Full List of Examples](#full-list)

## Getting Started

### 🔹 **Clone the Repository**
```bash
git clone https://github.com/a-dorgham/FEA_Ansys.git
cd FEA_Ansys
```

### 🔹 **Run the Simulations**
Each case study contains  input files, and results. Follow the **source** instructions to run the simulations in **Ansys Workbench, APDL, or Python scripting**.

## Contributions & Feedback
Contributions are welcome! Feel free to submit **feature requests**, **enhancements**, or **new case studies** via pull requests. If you encounter issues, open a discussion or raise an issue.

## License
This repository is licensed under the **MIT License**. See [LICENSE](LICENSE) for details.

<footer>

---

📌 Stay Connected: [LinkedIn](https://www.linkedin.com/in/abdeldorgham) | [GoogleScholar](https://scholar.google.com/citations?user=EOwjslcAAAAJ&hl=en)  | [ResearchGate](https://www.researchgate.net/profile/Abdel-Dorgham-2) | [ORCiD](https://orcid.org/0000-0001-9119-5111)
📧 Contact: a.k.y.dorgham@gmail.com

</footer>
