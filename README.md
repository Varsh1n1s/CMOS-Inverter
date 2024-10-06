# CMOS-Inverter

A CMOS inverter is a basic logic gate in digital electronics, formed by a combination of a p-type MOSFET (PMOS) and an n-type MOSFET (NMOS) connected in a complementary manner. 

- **Structure**: The PMOS is connected to the positive power supply (Vdd), while the NMOS is connected to ground (Vss). The input is applied to the gates of both transistors, and the output is taken from their common connection.

- **Operation**: 
   - When the input is low (0), the PMOS conducts and the NMOS is off, resulting in a high output (Vdd).
   - When the input is high (1), the NMOS conducts and the PMOS is off, pulling the output low (Vss).
   
- **Characteristics**: 
   - The CMOS inverter consumes negligible power in its static state (when the input is stable) since only one transistor conducts at a time, avoiding direct current flow between Vdd and ground.
   - It has high noise margins and is widely used for its power efficiency and speed in digital circuits.

