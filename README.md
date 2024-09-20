java c
CIV 5888  CIV6888 - Advanced
Computational Methods: Assignment II
· You need to attach the marking scheme sheet given on this page to the first page of your report.
· You must submit your report by 11:55 PM, Fri, 20 Sep (Week 9), 2024 in Moodle.
· For modelling parts: A summary of the procedure taken to model structures in ABAQUS must be provided. Items include snapshots of the model geometry, material definition, applied loads and meshes. Students must also provide the *.inp files.
· The report should be structured with clarity, featuring distinct and logically numbered sections and subsections where necessary. Every graph and table must be sequentially numbered and consistently referenced within the text. Additionally, each graph and table must be accompanied by a descriptive caption.
· No handwriting. Only typed assignment will be accepted.
Name
Student ID


The below table will be filled by the assessor and for marking purposes
Items
Assessor's comments
a

b

c

d

Report readability and
quality
Consider a soil layer with infinite extension horizontally in the x-direction, fully saturated, and with a defined height of 50 mm. This layer is subjected to a strip load (a plane strain problem) that is 50-mm-wide and has a uniform. pressure of 3.45 MPa. This configuration is depicted in Figure 1. The soil layer's base is supported by a frictionless rigid surface, allowing it to slide freely in the horizontal direction. In addition, the bottom boundary is impervious.Assume the void ratio of the soil layer is 0.5, and the soil displays linear elasticity characterised by the following parameters:
§ E = 690 GPa (The high elastic modulus is used to reduce the time step required for accurate simulation of the initial transient response immediately following a load change)
§ v = 0
§ K = 5.08 x 10-7 day
with v and k representing Young's modulus, Poisson's ratio, and permeability coefficien代 写CIV 5888 & CIV6888 - Advanced Computational Methods: Assignment IIMatlab
代做程序编程语言t, respectively. Furthermore, the pore fluid in the soil has a specific weight of 272.9 kn/m3.
Note that a theoretical analysis of this plane strain consolidation problem can be found in Gibson et al. (1970). To clarify, the material parameters utilised in this example are illustrative and may not represent the behaviour of actual soil and pore fluid. They are chosen based on Gibson's solution.
Analysis Tasks:
(a) Calculate the consolidation settlement at the center of the strip over time using Abaqus. Compare your results with the theoretical curve from Figure 2, using data digitised via WebPlot Digitizer.You may follow this suggestion in your modelling:§ In the initial step, the load is applied with no drainage permitted across the soil's top surface.§ Subsequently, the consolidation is executed over five distinct time steps and the top surface's hydraulic boundary condition is modified to a pervious boundary with  (u is the pore water pressure).§ Fixed time stepping may be considered. The durations of these steps may be considered as follows: , 0.01, and 0.1 day.
(b) From the numerical results, plot the degree of consolidation versus time at depths of (0.1+0.1 the last digit of your ID) mm, (5+0.1 the last digit of your ID) mm, and (10+0.1 the last digit of your ID) mm below the center of the loaded area.
(c) Repeat your simulations with E = (100 + the last two digits of your ID) GPa while keeping all other parameters the same as part (a). Discuss whether consolidation occurs faster or slower and explain why. Note that you need to compare the two cases (i.e., parts b and c) in terms of the degrees of consolidation versus time at points given in part (b).
(d) Repeat your simulations with v = 0.3d while keeping all other parameters the same as part (a). Will you see more settlement or less at the end of the consolidation? Why?
Fig 1. The problem geometry.Fig. 2. Theoretical solution.





         
加QQ：99515681  WX：codinghelp
