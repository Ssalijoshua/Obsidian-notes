### Analog to Digital Converters

#### i) Parallel ADC

![[Pasted image 20241109154704.png]]

- **V_REF**: This is the reference voltage for the ADC and sets the maximum voltage that can be measured.
- **Voltage Divider**: The resistors connected to V_REF create reference voltages (V2, V1​, V0) with uniform spacing between them.
- **Comparators**: Each comparator has one input connected to the reference voltages and the other to the analog input voltage, VAV_AVA​.
    - If VA​ is greater than the reference voltage connected to the comparator's negative input, the comparator outputs a high signal (5V in this case).
    - Otherwise, the comparator outputs a low signal (0V).
- **Digital Logic Encoder**: The outputs of the comparators (c2​,c1​,c0​) are fed into the encoder, which converts them into a binary output code.
#### Advantage of the parallel ADC
- It is very fast
##### Disadvantage of the parallel ADC
- While the parallel ADC is very fast, it suffers from the problem of requiring (2^N) − 1 comparators and 2^N resistors to convert an analog signal into an N -bit digital representation.
- It requires a lot of space and power in order to function.

#### ii) Counting ADC
