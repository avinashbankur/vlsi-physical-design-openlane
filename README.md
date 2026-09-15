<div align="center" style="border: 2px solid ccc; padding: 20px; border-radius: 12px; width: 80%; margin: auto; box-shadow: 0 0 10px rgba(0,0,0,0.15);">



<img

&#x20;   width="180"

&#x20;   height="220"

&#x20;   alt="Logo - SURE ProEd"

&#x20;   src="https://github.com/user-attachments/assets/88fa5098-24b1-4ece-87df-95eb920ea721"

&#x20;   style="border-radius: 10px;"

/>



<h1 align="center" style="font-family: Arial; font-weight: 600; margin-top: 15px;">

SURE ProEd (formerly SURE Trust)

</h1>



<h2 style="color: 2b6cb0; font-family: Arial;">

Skill Upgradation for Rural youth Empowerment Trust

</h2>



</div>



<hr style="border: 0; border-top: 1px solid ccc; width: 80%;" />



<div style="padding: 20px; border: 2px solid ddd; border-radius: 12px; width: 90%; margin: auto; background: fafafa; font-family: Arial;">



<h2 style="color:333;">Student Details</h2>



<div align="left" style="margin: 20px; font-size: 16px;">



<p><strong>Name:</strong> Avinash Bankur</p>



<p><strong>Email ID:</strong> avinashbankur48@gmail.com</p>



<p><strong>College Name:</strong> BEARYS INSTITUTE OF TECHNOLOGY</p>



<p><strong>Branch/Specialization:</strong> VLSI / Physical Design</p>



<p><strong>College ID:</strong> 4BP22EC005</p>



</div>



<hr style="border: 0; border-top: 1px solid ccc; width: 80%;" />



<h2 style="color:333;">Course Details</h2>



<div align="left" style="margin: 20px; font-size: 16px;">



<p><strong>Course Opted:</strong> Physical Design (VLSI)</p>



<p><strong>Batch:</strong> G4-25-VLSI</p>



<p><strong>Duration:</strong> 6 Months</p>



</div>



<hr style="border: 0; border-top: 1px solid ccc; width: 80%;" />



<h2 style="color:333;">Mentor Details</h2>



<div align="left" style="margin: 20px; font-size: 16px;">



<p><strong>Mentor Name:</strong> Veeramani R</p>



<p><strong>Mentor Email ID:</strong> veeramani_r@outlook.com</p>



<p><strong>Mentor Designation:</strong> Staff Engineer - Synopsys Inc.</p>



<p><strong>Education:</strong> MTech in VLSI - NITG | MTech in AI - IISc</p>



</div>



</div>



<hr style="border: 0; border-top: 1px solid ccc; width: 80%;" />



&#x20;Table of Contents



\- \[Overall Learning](overall-learning)

\- \[Projects Completed](projects-completed)

\- \[Project 1](project-1)

\- \[Project 2](project-2)

\- \[Project 3](project-3)

\- \[Technologies Used](technologies-used)

\- \[Roles and Responsibilities](roles-and-responsibilities)

\- \[Project Report](project-report)

\- \[Learnings from LST and SST](learnings-from-lst-and-sst)

\- \[Community Services](community-services)

\- \[Certificate](certificate)

\- \[Acknowledgments](acknowledgments)



\---



&#x20;Overall Learning



During this course, I gained practical knowledge of VLSI Physical Design and learned how an RTL design is taken through different stages of the RTL-to-GDSII flow.



I developed hands-on experience with OpenLane, OpenROAD, SKY130 technology, Linux commands, TCL scripting, static timing analysis, floorplanning, placement, Clock Tree Synthesis (CTS), routing, power analysis, area analysis and IR-drop analysis.



The course started with basic Linux and tool-environment learning and gradually progressed to physical-design implementation and analysis. I worked on a 4-bit up/down counter and later worked on a 32-bit RISC-V PicoRV32 design.



The assignments helped me understand how design constraints such as clock period, clock uncertainty, timing derate, utilization and floorplan parameters affect the physical implementation of a digital design.



Along with technical knowledge, the LST and SST sessions helped me improve my communication, confidence, teamwork, time management and professional skills.



\---



&#x20;Projects Completed



<div align="left" style="margin: 20px; font-size: 16px;">



<p>

<strong><a href="project-1">Project 1:</a></strong>

OpenLane Environment, Linux Commands and TCL-Based Design Analysis

</p>



<p>

<strong><a href="project-2">Project 2:</a></strong>

4-bit Up/Down Counter Physical Design

</p>



<p>

<strong><a href="project-3">Project 3:</a></strong>

32-bit RISC-V PicoRV32 Physical Design

</p>



</div>



\---



&#x20;Project 1



<h3 id="project-1">

OpenLane Environment, Linux Commands and TCL-Based Design Analysis

</h3>



&#x20;Project Introduction



The first assignment focused on understanding the OpenLane environment, Linux commands, VI editor, file permissions, text-processing commands and TCL scripting.



The objective was to become familiar with the environment required for VLSI Physical Design and to understand how reports and design data can be analyzed using command-line tools and TCL.



&#x20;Linux Commands



The following Linux commands were practiced:



| Command | Purpose |

|---|---|

| `pwd` | Display current directory |

| `ls` | List files and directories |

| `cd` | Change directory |

| `mkdir` | Create a directory |

| `rm` | Remove files |

| `cp` | Copy files |

| `mv` | Move or rename files |

| `chmod` | Modify file permissions |

| `grep` | Search patterns in files |

| `awk` | Process and analyze structured text |



&#x20;VI Editor



The VI editor was used to edit configuration files and scripts.



Important commands practiced included:



\- `i` – Insert mode

\- `:w` – Save

\- `:q` – Exit

\- `:wq` – Save and exit

\- `:q!` – Force quit



&#x20;TCL-Based Wire Length Analysis



Wire-length analysis was performed using the available reports and OpenROAD.



The recorded values were:



| Parameter | Value |

|---|---:|

| Total Wire Length | 6716.82 |

| Clock Wire Length | 784.48 |

| Data Wire Length | 5932.34 |



This activity helped me understand the relationship between clock routing, data routing and total wire length.



&#x20;IR-Drop Analysis



IR-drop analysis was performed using the signoff power reports.



The analysis used the SKY130 nominal supply voltage of 1.8 V.



One of the recorded results was:



\- Minimum voltage = 1.79972 V

\- Nominal VDD = 1.8 V

\- Worst IR Drop = 0.00028 V

\- Percentage degradation ≈ 0.0156%



This helped me understand how voltage variation across the power distribution network is analyzed.



&#x20;Levels of Logic Analysis



TCL scripting was used to process timing reports and extract:



\- Startpoint

\- Endpoint

\- Slack

\- Levels of Logic (LoL)



Example results:



| Path | Startpoint | Endpoint | Slack | LoL |

|---|---|---|---:|---:|

| 1 | `rst` | `\\\\\\\_445\\\\\\\_` | 7.78 ns | 6 |

| 2 | `\\\\\\\_444\\\\\\\_` | `p` | 6.86 ns | 3 |



This activity helped me understand how timing paths can be automatically analyzed using TCL scripts.



\---



&#x20;Project 2



<h3 id="project-2">

4-bit Up/Down Counter Physical Design

</h3>



&#x20;Project Introduction



The second assignment involved implementing and analyzing a 4-bit up/down counter using the OpenLane physical-design flow.



The design was taken through major stages including:



\- Synthesis

\- Floorplanning

\- Placement

\- Clock Tree Synthesis

\- Routing

\- Signoff analysis



&#x20;Maximum Operating Frequency



Different clock periods were tested to determine the maximum operating frequency.



| Clock Period | Timing Status | Observation |

|---:|---|---|

| 4 ns | PASS | Large positive slack |

| 3 ns | PASS | Timing closure achieved |

| 2 ns | FAIL | Negative slack |



The highest passing frequency was obtained at a 3 ns clock period.



Using:



`f = 1/T`



Therefore:



`f = 1 / (3 × 10⁻⁹)`



&#x20;Maximum Operating Frequency = 333.33 MHz



The design failed timing closure at a 2 ns clock period because negative slack was observed.



&#x20;Timing Parameters



| Parameter | Value |

|---|---:|

| Clock Uncertainty | 0.25 ns |

| Early Timing Derate | 0.95 |

| Late Timing Derate | 1.05 |



&#x20;Power Analysis



Power was analyzed at different stages of the physical-design flow.



| Stage | Total Power |

|---|---:|

| Synthesis | 1.58 × 10⁻⁴ W |

| Placement | 1.63 × 10⁻⁴ W |

| CTS | 3.62 × 10⁻⁴ W |

| Global Routing | 3.56 × 10⁻⁴ W |

| Routing Timing | 3.71 × 10⁻⁴ W |

| Signoff RCX\_MAX | 4.31 × 10⁻⁴ W |



The maximum reported signoff power was approximately:



4.31 × 10⁻⁴ W



&#x20;Area and Utilization



| Parameter | Value |

|---|---:|

| Synthesis Chip Area | 257.7472 µm² |

| Placement Area | 1268.7168 µm² |

| Routing Area | 1268.7168 µm² |

| Final Die Area | 0.0027065604 mm² |

| Core Area | 1268.7168 µm² |

| Utilization | 22.37% |

| Cell Density | 59115.62 |

| Cell Count/mm² | 11823.12 |



&#x20;Floorplan Analysis



The core dimensions were measured using OpenROAD TCL commands.



| Parameter | Value |

|---|---:|

| Core LLX | 5520 DBU |

| Core LLY | 10880 DBU |

| Core URX | 41400 DBU |

| Core URY | 46240 DBU |

| Core Width | 35880 DBU |

| Core Height | 35360 DBU |



The die dimensions were:



| Parameter | Value |

|---|---:|

| Die Width | 46940 DBU |

| Die Height | 57660 DBU |



&#x20;Physical-Only Cells



The following physical-only cells were identified:



\- `sky130\\\\\\\_fd\\\\\\\_sc\\\\\\\_hd\\\\\\\_\\\\\\\_decap\\\\\\\_3`

\- `sky130\\\\\\\_fd\\\\\\\_sc\\\\\\\_hd\\\\\\\_\\\\\\\_tapvpwrvgnd\\\\\\\_1`



Decap cells help improve power-supply stability, while tap cells provide substrate and well connections.



&#x20;Placement Analysis



Buffers, inverters, flip-flops, site rows and standard-cell dimensions were analyzed during placement.



The placement site was:



| Parameter | Value |

|---|---:|

| Site Name | `unithd` |

| Site Width | 460 DBU |

| Site Height | 2720 DBU |



Example library cells analyzed included:



| Library Cell | Width (DBU) | Height (DBU) |

|---|---:|---:|

| `sky130\\\\\\\_fd\\\\\\\_sc\\\\\\\_hd\\\\\\\_\\\\\\\_xor2\\\\\\\_1` | 3220 | 2720 |

| `sky130\\\\\\\_fd\\\\\\\_sc\\\\\\\_hd\\\\\\\_\\\\\\\_xnor2\\\\\\\_1` | 3220 | 2720 |

| `sky130\\\\\\\_fd\\\\\\\_sc\\\\\\\_hd\\\\\\\_\\\\\\\_or2b\\\\\\\_1` | 2760 | 2720 |

| `sky130\\\\\\\_fd\\\\\\\_sc\\\\\\\_hd\\\\\\\_\\\\\\\_and2b\\\\\\\_1` | 2760 | 2720 |

| `sky130\\\\\\\_fd\\\\\\\_sc\\\\\\\_hd\\\\\\\_\\\\\\\_dfrtp\\\\\\\_1` | 9200 | 2720 |



&#x20;CTS Analysis



Clock Tree Synthesis inserted clock buffers to distribute the clock signal.



The report identified three CTS buffers:



\- `clkbuf\\\\\\\_0\\\\\\\_clk`

\- `clkbuf\\\\\\\_1\\\\\\\_0\\\\\\\_\\\\\\\_f\\\\\\\_clk`

\- `clkbuf\\\\\\\_1\\\\\\\_1\\\\\\\_\\\\\\\_f\\\\\\\_clk`



The cell type was:



`sky130\\\\\\\_fd\\\\\\\_sc\\\\\\\_hd\\\\\\\_\\\\\\\_clkbuf\\\\\\\_16`



No additional inverter cells were inserted during CTS.



&#x20;Routing Analysis



The routing stage was analyzed to understand signal routing and the physical implementation after CTS.



The OpenLane flow was successfully taken through routing and signoff analysis.



\---



&#x20;Project 3



<h3 id="project-3">

32-bit RISC-V PicoRV32 Physical Design

</h3>



&#x20;Project Introduction



The third assignment focused on implementing and analyzing a 32-bit RISC-V PicoRV32 design using the OpenLane/OpenROAD physical-design flow.



This project extended the concepts learned from the smaller 4-bit counter design to a considerably larger processor-oriented RTL design.



&#x20;Design Details



| Parameter | Value |

|---|---|

| Design | PicoRV32 |

| Architecture | 32-bit RISC-V |

| Technology | SKY130 |

| Clock Period | 6 ns |

| Synthesis Clock Uncertainty | 0.9 ns |

| CTS Clock Uncertainty | 0.3 ns |

| Timing Derate | 3% |

| Input Delay | 3 ns |

| Output Delay | 3 ns |

| Floorplan Utilization | 60% |

| Floorplan Ratio | 0.7 |



&#x20;Clock Period and Uncertainty



The PicoRV32 design used a 6 ns clock period.



The synthesis clock uncertainty was configured as 15% of the clock period:



`15% × 6 ns = 0.9 ns`



For CTS, the target skew/uncertainty requirement was based on 5% of the clock period:



`5% × 6 ns = 0.3 ns`



&#x20;Timing Derate



A 3% timing derate was applied to the design.



The timing derate was configured and verified during the physical-design flow.



&#x20;Input and Output Delays



The input and output delays were configured to 50% of the clock period.



For a 6 ns clock:



\- Input Delay = 3 ns

\- Output Delay = 3 ns



&#x20;Floorplan Utilization



The floorplan utilization was configured to:



60%



This configuration was used to control the amount of core area occupied by standard cells.



&#x20;Floorplan Ratio



The floorplan ratio was configured to:



0.7



This parameter was verified through the OpenLane configuration.



&#x20;Manual Port Placement



Manual port placement was performed using a `pin\\\\\\\_order.cfg` file.



The configuration included signals such as:



\- Clock

\- Reset

\- Memory interface signals

\- IRQ signals

\- PCPI signals

\- Memory data signals

\- Other PicoRV32 input/output signals



The objective was to organize the ports systematically and control their physical placement.



&#x20;Library Cell Analysis



The OpenROAD report for the PicoRV32 design recorded:



| Parameter | Value |

|---|---:|

| Technology Layers | 14 |

| Technology Vias | 25 |

| Library Cells | 441 |

| Pins | 411 |

| Components | 12005 |

| Nets | 9508 |



This demonstrated the considerably larger physical complexity of the PicoRV32 design compared with the 4-bit counter.



&#x20;CTS Target Skew



For a 6 ns clock:



`5% × 6 ns = 0.3 ns`



The target value was therefore:



0.3 ns



The CTS stage was analyzed using the available OpenLane/OpenROAD flow and the achieved clock behavior was verified from the generated reports.



&#x20;Post-CTS Clock Network Delay



After CTS, the clock network was configured as a propagated clock.



The ideal clock network was disabled.



The verification showed:



| Parameter | Result |

|---|---|

| Clock Network Delay | INSERTED |

| Clock Type | PROPAGATED CLOCK |

| Ideal Clock Network | DISABLED |



This ensures that post-CTS timing analysis considers the implemented clock network rather than an ideal clock.



\---



&#x20;Technologies Used



The following technologies, tools and concepts were used during the course:



\- OpenLane

\- OpenROAD

\- SKY130 HD PDK

\- TCL

\- Linux

\- VI Editor

\- Verilog / RTL

\- Static Timing Analysis (STA)

\- RTL-to-GDSII flow

\- Synthesis

\- Floorplanning

\- Placement

\- Clock Tree Synthesis (CTS)

\- Routing

\- Signoff Analysis

\- IR-Drop Analysis

\- Power Analysis

\- Area Analysis

\- Utilization Analysis

\- Wire Length Analysis

\- PicoRV32

\- 32-bit RISC-V



\---



&#x20;Roles and Responsibilities



During the course, I was responsible for:



\- Learning the OpenLane physical-design environment.

\- Practicing Linux commands required for the VLSI flow.

\- Using VI editor for configuration and script editing.

\- Learning TCL scripting for automation and report analysis.

\- Running OpenLane physical-design stages.

\- Performing synthesis and floorplan analysis.

\- Performing placement analysis.

\- Performing Clock Tree Synthesis analysis.

\- Performing routing analysis.

\- Analyzing timing slack.

\- Determining maximum operating frequency.

\- Analyzing power consumption.

\- Analyzing area and utilization.

\- Performing IR-drop analysis.

\- Analyzing physical-only cells.

\- Identifying buffers, inverters and flip-flops.

\- Measuring standard-cell dimensions.

\- Analyzing clock routing.

\- Working with a 32-bit RISC-V PicoRV32 design.

\- Configuring timing constraints.

\- Configuring floorplan parameters.

\- Performing post-CTS clock-network verification.

\- Preparing technical documentation and reports.



\---



&#x20;Project Report



&#x20;Assignment 1



&#x20;Main Areas Covered



\- Linux command practice

\- VI editor

\- `chmod`

\- `grep`

\- `awk`

\- OpenLane directory structure

\- TCL scripting

\- Wire-length analysis

\- IR-drop analysis

\- Levels of Logic analysis



The first assignment established the basic command-line, scripting and physical-design analysis skills required for the later assignments.



\---



&#x20;Assignment 2



&#x20;4-bit Up/Down Counter



The 4-bit up/down counter was implemented using the OpenLane flow.



&#x20;Main Results



\- Maximum passing clock period: 3 ns

\- Maximum operating frequency: 333.33 MHz

\- 2 ns clock period: Timing Failure

\- Clock uncertainty: 0.25 ns

\- Early derate: 0.95

\- Late derate: 1.05

\- Placement utilization: 22.37%

\- Signoff RCX\_MAX power: 4.31 × 10⁻⁴ W



\---



&#x20;Assignment 2.2



The GUI-based physical-design exploration covered:



&#x20;Floorplan



\- Core width and height

\- Die width and height

\- Physical-only cells



&#x20;Placement



\- Buffers

\- Inverters

\- Flip-flops

\- Site rows

\- Standard-cell dimensions



&#x20;CTS



\- CTS buffers/inverters

\- Clock tree

\- Clock routing



&#x20;Routing



\- Signal routing

\- Routed design

\- Routing-stage analysis



\---



&#x20;Assignment 3



&#x20;32-bit RISC-V PicoRV32



The third assignment involved taking the PicoRV32 RTL through the OpenLane/OpenROAD physical-design flow.



The major topics included:



\- Clock period configuration

\- Clock uncertainty

\- Timing derate

\- Input/output delays

\- Floorplan utilization

\- Floorplan ratio

\- Manual port placement

\- CTS target skew

\- Clock network delay

\- Propagated clock analysis

\- Physical implementation of a larger RISC-V design



\---



&#x20;Learnings from LST and SST



&#x20;LST – Life Skills Training



The LST sessions helped me understand the importance of personal development along with technical knowledge.



During these sessions, I learned about:



\- Time management

\- Goal setting

\- Self-discipline

\- Decision-making

\- Problem-solving

\- Self-confidence

\- Handling challenges and failures

\- Maintaining a positive attitude

\- Developing a growth mindset

\- Taking responsibility for my actions



These sessions helped me understand how good life skills can improve both personal and professional development.



&#x20;SST – Soft Skills Training



The SST sessions helped me improve my communication and professional behavior.



I learned about:



\- Effective communication

\- Active listening

\- Teamwork

\- Leadership

\- Presentation skills

\- Professional communication

\- Interview skills

\- Workplace etiquette

\- Confidence while interacting with others

\- Coordination and collaboration



Overall, the LST and SST sessions helped me become more confident, disciplined and better prepared for a professional working environment.



\---



&#x20;Community Services



During the internship/course period, I participated in community-oriented activities and learned the importance of social responsibility and helping others.



&#x20;Activities Involved



<!-- ADD YOUR ACTUAL COMMUNITY-SERVICE ACTIVITIES HERE -->



\- <!-- Activity 1 -->

\- <!-- Activity 2 -->

\- <!-- Activity 3 -->



&#x20;Impact / Contribution



<!-- ADD YOUR ACTUAL COMMUNITY-SERVICE CONTRIBUTION HERE -->



The community-service activities helped me understand the importance of social responsibility, teamwork, communication and contributing positively to society.



&#x20;Photos



<!-- ADD YOUR ACTUAL COMMUNITY-SERVICE PHOTOS HERE -->



<div align="center">



<!--

<img src="YOUR\\\\\\\_IMAGE\\\\\\\_URL\\\\\\\_1" alt="Community Service Photo 1" width="30%">

<img src="YOUR\\\\\\\_IMAGE\\\\\\\_URL\\\\\\\_2" alt="Community Service Photo 2" width="30%">

<img src="YOUR\\\\\\\_IMAGE\\\\\\\_URL\\\\\\\_3" alt="Community Service Photo 3" width="30%">




</div>



\\---



\\ Certificate



The internship/course certificate serves as official recognition of my participation and successful completion of the required training and activities.






<p align="center">



<img

src="YOUR\_CERTIFICATE\_IMAGE\_URL"

alt="Internship Certificate"

width="80%"

>



</p>



\---



&#x20;Acknowledgments



I would like to sincerely thank Prof. Radhakumari Challa, Executive Director and Founder - SURE Trust, for providing me with the opportunity to participate in this course and gain valuable technical and professional knowledge.



I would also like to express my sincere gratitude to my mentor, Veeramani R, Staff Engineer at Synopsys Inc., for his guidance, support and valuable insights throughout the Physical Design (VLSI) course.



His guidance during the assignments helped me understand practical aspects of VLSI Physical Design, including the OpenLane/OpenROAD flow, timing analysis, floorplanning, placement, Clock Tree Synthesis, routing and signoff analysis.



I am grateful to SURE Trust and all the instructors and trainers for their continuous support and encouragement throughout my learning journey.



The practical assignments and LST/SST sessions helped me improve both my technical knowledge and professional skills.



I sincerely appreciate the time and effort invested in helping students develop the technical and professional skills required for their future careers.



\---



&#x20;References



1\. OpenLane

2\. OpenROAD

3\. SKY130 HD PDK

4\. PicoRV32 RISC-V RTL

5\. OpenLane/OpenROAD generated reports

6\. Course assignments and technical documentation

