The project was undertaken as a component of ECE 457, focusing on Microfabrication and Devices, within the nanoFAB - Fabrication and Characterization Facility - located in Edmonton.

# Objective
This project aimed to fabricate a variety of multilayer devices and test structures using conventional fabrication techniques for integrated circuits such as spin coating, photoresist baking, photolithography, and mask alignment. The devices and test structures were inspected and tested at intermediate points and when they were complete. The project utilized three
patterned layers to produce a variety of test structures, photonic structures, and electronic devices including some simple circuits.

#  Process flow overview
The first patterned layer (bottom layer) and third patterned layer (top layer) are aluminum (metal; electrically conductive). This second patterned layer (middle layer) is silicon nitride, which is electrically insulating.

<div align="center">

![image](https://github.com/NSaroya/Multilayer-Fabrication-Project-/assets/156468713/fa78102a-4ee1-43c7-b4af-21d4e781cfc4)
</div>

This three-layer structure is sufficient for making a variety of devices while allowing for the wiring formed by lines of aluminum in the bottom and top layers to cross laterally (in the x-y plane). Each of the layers will be patterned using standard microfabrication techniques. The substrate used is a silicon wafer. However, as the Si wafer is itself semiconducting, devices fabricated on the wafer need to be electrically isolated from one another. This is done by having a layer of silicon oxide (SiO2) between the Si wafer and the bottom Al layer.

### Step 1 — Wafer preparation
The Si wafer (∼500 µm) is cleaned using piranha solution before processing to remove any foreign materials that might be on the surface.
### Step 2 — Grow insulating layer of SiO2
A thin layer of SiO2(∼300 nm) is “grown” by a process called thermal oxidation. An alternate method would be to use plasma-enhanced chemical vapour deposition (PECVD), but thermal oxidation is more efficient.
### Step 3 — Deposit aluminum
Al metal (∼100 nm) is sputtered onto the surface of the Si wafer.
### Step 4 — Lithography: Apply resist
A layer of UV-sensitive material called photoresist is spin-coated onto the surface of the aluminum.
### Step 5 — Lithography: Align and expose
A patterned mask (metal pattern on glass) is brought into contact with the photoresist. The photoresist is exposed to UV light, through the mask. Areas covered by metal on the mask are protected, while uncovered areas are exposed to the UV light. The UV light exposure changes the chemical composition of the photoresist in the exposed areas.
### Step 6 — Lithography: Develop
The wafer is then placed in a developer solution that removes the resist in the regions where it has been exposed to the UV light.
### Step 7 — Etching
The photoresist acts as a protective layer and the Al is etched away until the underlying SiO2 layer is reached.
### Step 8 — Resist removal
The remaining photoresist is stripped with acetone leaving the wafer with a patterned aluminum layer.

Steps 3 through 8 are repeated twice with slight variations to deposit and pattern the silicon nitride (middle layer) and the top aluminum layer. Removal of material by etching and deposition of a subsequent layer of material (Step 3 in the next cycle) allows the top and bottom Al layers to come into contact with each other at different places across the wafer.

# Experimental Setup

**Session #1:** The aim of this session was to pattern the first (bottom) aluminum layer. Before the session, the preparation steps of wafer cleaning, thermal oxidation of silicon oxide layer, and sputtering of metal layer 1 had been completed. The wafer cleaning process is done using piranha etch solution which is a mixture of sulfuric acid and hydrogen peroxide in 3:1 ratio. The silicon wafer is first bathed in piranha solution for 15 minutes, followed by a 2-minute bath in
buffered oxide etch (BOE). Next, the SiO2 layer is deposited by thermal oxidation, followed by DC sputter deposition to deposit thin film of aluminum, roughly 100 nm, onto the surface of the substrate.

![image](https://github.com/NSaroya/Multilayer-Fabrication-Project-/assets/156468713/669f0ce4-e942-45dc-aeaf-a14e77105d9c)
<p align="center">
  <strong>Fig 1:</strong> Process flow for session #1: deposit aluminum, lithography: apply-resist, align, and expose, develop, metal wet etching, and resist removal. The final wafer layers consist of silicon base (~500 μ𝑚), insulating silicon dioxide layer (~300 𝑛𝑚) and bottom layer (85.05 nm).
</p>

**Session #2:** A 150 nm silicon nitride insulator layer was deposited using PECVD, maintaining low temperatures to preserve film properties. The wafer was then treated with HMDS for enhanced photoresist adhesion. AZ 1512 photoresist was applied using the same process as session 1. After alignment on an ABM mask aligner, the photoresist was developed, resulting in a thickness of 1315 nm. The nitride layer, initially measured at 156.99 nm, was dry etched using Trion RIE equipment for 100s at an etch rate of 0.145 nm/s. Post-etch, the photoresist was removed using acetone, IPA, DI rinse, and N2 dry, yielding a final nitride thickness of 145.6 nm.

![image](https://github.com/NSaroya/Multilayer-Fabrication-Project-/assets/156468713/42e20d9c-23e1-4320-a99f-24826c25af6a)
<p align="center">
  <strong>Fig 2:</strong> Process flow for session #2: deposit silicon nitride layer, lithography: apply resist, align and expose, develop, dry etching (RIE), and resist removal. Silicon nitride layer thickness measured to be 145.60 nm.
</p>

**Session #3:** The Al layer was sputtered, and we conducted photolithography and aluminum etching to pattern the topmost aluminum metal layer. Employing the AZ 1512 spin coating and baking process, a photoresist layer was applied. UV exposure for 2 seconds at an intensity of 75mJ/cm2 was followed by a 1 minute and 53 seconds development in AZ 400k 1:4 developer solution. After inspecting the features under a microscope, aluminum underwent wet etching in Al etchant for 6 minutes and 43 seconds. Following another inspection and satisfaction with feature appearance, the photoresist was removed with acetone and IPA. The final aluminum layer thickness measured 150.7 nm.

![image](https://github.com/NSaroya/Multilayer-Fabrication-Project-/assets/156468713/54534fa9-cae6-44c9-99ea-0adba3b186a9)
<p align="center">
  <strong>Fig 3:</strong> Process flow for session #3: deposit top metal layer, lithography: apply resist, align and expose, develop, wet etching, and resist removal. The top metal layer thickness is 150.70 nm.
</p>

**Session #4:** This lab session is the final one for the Multilayer project and focuses on characterization of the devices. Instruments you will use include the Wentworth probing station (to test device resistance across the devices), optical microscopy, and optical profilometry.

# Device Inspection and Characterization
### Session #1
![image](https://github.com/NSaroya/Multilayer-Fabrication-Project-/assets/156468713/82f9a9b1-bcbb-4ebd-8165-bc7104e67d64)
![image](https://github.com/NSaroya/Multilayer-Fabrication-Project-/assets/156468713/b8f32ebd-0f88-4acd-b20d-da55f072bbdc)
![image](https://github.com/NSaroya/Multilayer-Fabrication-Project-/assets/156468713/8138c19f-4c67-485e-850d-e2eac80fe611)
<p align="center">
  <strong>Fig 5:</strong> First layer of aluminum metal deposited - images showing bottom metal layer of greek cross, via chains, and kelvin cross.
</p>

### Session #2
![image](https://github.com/NSaroya/Multilayer-Fabrication-Project-/assets/156468713/80c61199-b7f3-4800-ba14-34e300c7021e)
![image](https://github.com/NSaroya/Multilayer-Fabrication-Project-/assets/156468713/984df287-f68d-456f-a985-d317b96c1a9b)
![image](https://github.com/NSaroya/Multilayer-Fabrication-Project-/assets/156468713/eae672eb-878d-4d38-b05f-610c91f2ab91)
<p align="center">
  <strong>Fig 6:</strong> Silicon Nitride Layer Deposition - Greek Cross and Via Chain structures
</p>

### Session #3
![image](https://github.com/NSaroya/Multilayer-Fabrication-Project-/assets/156468713/486d82a8-4de9-45a2-9b80-a87340bcae90)
![image](https://github.com/NSaroya/Multilayer-Fabrication-Project-/assets/156468713/2ad58de6-74c1-48a6-ac70-a2bc779108a8)
![image](https://github.com/NSaroya/Multilayer-Fabrication-Project-/assets/156468713/59e884a1-29e2-4a31-96a2-f9911e7844fa)
<p align="center">
  <strong>Fig 7:</strong> Greek Cross C2 Structure - showing missing metal deposit near interfacial surfaces
</p>

![image](https://github.com/NSaroya/Multilayer-Fabrication-Project-/assets/156468713/746dde8b-b1fa-406d-aec3-fa71e17ce6ba)
![image](https://github.com/NSaroya/Multilayer-Fabrication-Project-/assets/156468713/36d1fe99-b0c6-47ca-adc9-c756375b80cb)
![image](https://github.com/NSaroya/Multilayer-Fabrication-Project-/assets/156468713/ca5293e9-426d-41fa-be27-06c59adfb273)
<p align="center">
  <strong>Fig 8:</strong> Final Via Chain structures - shows some indication of misalignment
</p>

### Session #4

![image](https://github.com/NSaroya/Multilayer-Fabrication-Project-/assets/156468713/08650332-22bc-4376-b521-ca3c2c518167)
![image](https://github.com/NSaroya/Multilayer-Fabrication-Project-/assets/156468713/7200d6f9-eae3-4de5-89ee-e9494141f31a)
![image](https://github.com/NSaroya/Multilayer-Fabrication-Project-/assets/156468713/9d8bd38b-c77c-44e9-aa11-fb2e4085b7bb)
<p align="center">
  <strong>Fig 9:</strong> Wentworth probing station - setup uses a microscope and micro probes to connect devices and test the electrical properties of the devices
</p>

### Mask Layout

<div align="center">
  
![image](https://github.com/NSaroya/Multilayer-Fabrication-Project-/assets/156468713/19da2d5f-4496-4510-a309-c8ade40cb862)
</div>

<p align="center">
  <strong>Fig 10:</strong> An overview of one of the die (there are 9 copies on the wafer) for the Multilayer project. Colour key: blue = bottom Al layer; green = middle nitride layer; red = top Al layer. The co-ordinate system can assist
in locating different features.
</p>

# Conclusion
The project involved the fabrication of multilayer devices and test structures using conventional techniques. The final wafer, composed of three layers, enabled the creation of various devices and allowed for lateral wiring. Through the testing process, valuable insights were gained into the complexities of multilayer structure functionality. By identifying specific issues such as underetching and alignment errors, the project provided an opportunity to improve understanding and address challenges in the fabrication process. This knowledge can be leveraged to enhance future fabrication processes, leading to the development of more reliable and effective multilayer devices and test structures.

# Reference
[1] 	J. C. Sit, "ECE 457 lab manual — 2020–2021," Edmonton, 2023.
