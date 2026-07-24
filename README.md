Chironwire-2026

** Update Version 2026 ** Redesigned this section to address the following issues:

- Parts did not fit flush when assembled into the frame.
- The motor mount would flex under high acceleration.
- Added a support bearing to reduce the risk of motor shaft misalignment caused by excessive belt tension.

<img width="671" height="717" alt="Untitled" src="https://github.com/user-attachments/assets/bf534762-8815-4471-b1ce-ca6deecb88a1" />

** Disassembly and assembly steps **
- remove all existing electronics
- remove the bed

- install linear guide with **MGN12H_2040_Guide.stl**
Front view: This is the spacing between the linear rail and the guard as designed
<img width="671" height="717" alt="4da12b11-4b8c-405c-b23f-5e3c2b48af57" src="https://github.com/user-attachments/assets/d18d6ac5-916e-444c-836d-bb3a3583dbd4" />|
- connect the 3 pieces composing the Y carriage frame using the leftover 8mm spacers

**MGN12 Drilling Y A-xis guide**

- Use MGN12H_(M3_20x20mm)_Y_AXIS.stl the mounting hole spacing is designed for M3 screws with a 20 × 20 mm pattern. Please measure your linear rail before installation, as the hole spacing may vary between manufacturers. However, this is not a major issue , you can simply drill the holes out to 4 mm to provide enough clearance.
<img width="671" height="717" alt="280f26b1-d70f-42f9-9b4a-be8f6eb953e4" src="https://github.com/user-attachments/assets/9bd687b3-54dc-4b93-9adb-a1ceeebf28f5" />

I used a spring plunger

<img width="671" height="717" alt="cdc93a92-7736-4de8-8f81-1e79ead178e7" src="https://github.com/user-attachments/assets/6e419a4b-5622-47ca-95fd-98a7617a27bd" />
<img width="671" height="717" alt="280f26b1-d70f-42f9-9b4a-be8f6eb953e4" src="https://github.com/user-attachments/assets/e0ff092b-af0f-4fa0-b25b-82f918bd1bcf" />

- Install the assembly onto the Y-axis linear rail.
If the bed feels stiff or does not move smoothly after installation, slightly loosen the linear rail mounting screws. Move the bed back and forth to allow the rail to self-align. For example, with the bed at the front, tighten one M3 screw. Then move the bed to the rear and tighten the next M3 screw. Repeat this process until the bed moves smoothly, then fully tighten all of the screws.** This will not cause any issues, as the Y-axis is not part of a CoreXY printer.**

<img width="671" height="717" alt="b8ede8ee-4f5d-4bcb-b8b6-78630baa8b45" src="https://github.com/user-attachments/assets/89de0b6b-3b15-489c-aff2-9296db16e1e8" />

XZ Motor 

- Install the 625 bearings. You can reuse the two 625 bearings from the V-wheels that were removed.
- Assemble it according to the original Switchwire assembly guide. The only additional hardware required is:
M3×25 screw
M3×8 screw
M3×5×4 heat-set insert nut

<img width="1075" height="1434" alt="6fcd44f3-0f03-40ae-b3f3-7f80906ff85a" src="https://github.com/user-attachments/assets/e46d28a1-1bf3-47fa-a89e-fb7c479c374f" />

<img width="671" height="1048" alt="9d3b7f99-f0ae-4429-afc5-b46df814d016" src="https://github.com/user-attachments/assets/ac5800e9-f39b-4010-b31d-0144b04df9ec" />
<img width="671" height="1048" alt="7e8b8b0d-8bbf-4f2e-a519-91bd42f692cd" src="https://github.com/user-attachments/assets/3dd81e86-9cb3-4ab6-b928-5a534b9031fe" />

- From this point onward, the build is almost identical to the original Switchwire. You can continue by following the official Switchwire assembly guide.**
For the wiring, if you're using the same control board as I am, you can follow the wiring example shown below.









Thanks for credit and edit from

- https://github.com/Jamiever6/ChironWire/tree/main
- https://github.com/VoronDesign/Voron-Switchwire/tree/master


