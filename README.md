## nasscom_vsd_soc_design
VLSI SOC Design Workshop with complete RTL2GDSII flow organized by VSD in collaboration with NASSCOM(Advanced Physical Design using Openlane with sky130nm. 

## Open Source EDA Tools
https://github.com/kunalg123/vsdflow.git

Openlane
https://github.com/The-OpenROAD-Project/OpenLane.git

Skywater 130nm PDK
https://github.com/RTimothyEdwards/open_pdks.git

## Day_1
## Practical Lab Sessions-1
## Design Preparation Stage
1. Running the OpenLane Flow Script in interactive
   
   `./flow.tcl -interactive`

2. Loading Openlane Package
   
   `package require openlane 0.9`
   ![openlane](https://github.com/user-attachments/assets/276bf6cc-0d22-48da-9ff5-98a2b9110e6b)
   
4. Design Preparation Stage
   
   `prep -design picorv32a`
   ![design_prep](https://github.com/user-attachments/assets/44218e20-525c-4b13-97ff-c954a171e62b)

5. Run Synthesis Stage

   `run_synthesis`
   ![synthesis](https://github.com/user-attachments/assets/ee3372c2-1b62-4a2e-baf4-f436948ebe25)

6. To Calculate flop ratio
   ![tcells](https://github.com/user-attachments/assets/3d9c7a45-3c62-46e4-a5a7-0b3c8e9f4b39)

   ![fcells](https://github.com/user-attachments/assets/dfbde265-f726-40de-a776-55968d6501e8)

   ![image](https://github.com/user-attachments/assets/bb627c2d-a748-45ca-a6eb-7e0cc717245f)

   Flop ratio = (Number of flop cells / Total number of cells) x 100
   Flop ratio = 10.84%


   


     

