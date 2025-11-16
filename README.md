# DESIGN-OF-INVERTING-AMPLIFIER-NON INVERTING-AMPLIFIER-DIFFERENTIAL AMPLIFIER-USING-OP-AMP-741
# AIM:
To design and construct a inverting, non- inverting and differential amplifiers.

# APPARATUS REQUIRED:
<img width="944" height="253" alt="image" src="https://github.com/user-attachments/assets/75606ec6-5b9a-4a89-a137-c0ab7d2100ff" />


# THEORY:
Op-amp in open-loop configuration has a very few application because of its enormous open- loop gain. Controlled gain can be can be achieved by taking a part of output signal to the input with the help of feedback. This is called as Closed- Loop Configuration. The three basic types of closed-loop amplifier configuration are:
1. Inverting amplifier.
2. Non-inverting amplifier.
3. Differential amplifier.
The entire configuration can be operated with either AC or DC input.

# INVERTING AMPLIFIER:
This is the most widely used op-amp. Here, the output voltage Vo is feedback to the inverting input terminal through the Rf – R1 network. The negative sign in gain indicates the phase shift of 180ο.
The circuit closed-loop voltage gain is Avcl= -RF / R1

# NON - INVERTING AMPLIFIER:
If signal is applied to the non-inverting input terminal of op-amp without inverting the input signal such a circuit is called non-inverting amplifier. Here the output is feedback to the inverting input terminal. The phase shift of input signal does not occur in non-inverting terminal.
The circuit closed-loop voltage gain is ACL = 1 + ( RF / R1)

# DIFFERENTIAL AMPLIFIER
A circuit that amplifies that amplifies the difference between two input signals is called as differential amplifier. It is useful in instrumentation amplifier. If the two input signals are the same, the output should be zero. Differential amplifier with a single op-amp has the exact gain of an inverting amplifier and it is given as
AV=Vd/V2-V1=-Rf/Ri

# PROCEDURE:
1. Select R1 as a constant value and choose a value of Rf.
2. Connect the circuit as per as the circuit diagram.
3. Apply the constant amplitude input voltage to the circuit.
4. Measure the output voltage amplitude for different value of V1 from DSO.
5. Calculate the practical Voltage for different value of V1& compare it with theoretical output.
6. Practical gain & theoretical voltage should be approximately equal.
7. Plot the graph of the input wave versus output wave for any one practical case.
   
# PIN DIAGRAM
<img width="401" height="173" alt="image" src="https://github.com/user-attachments/assets/84328324-1ceb-4c3c-98af-eb5f5e1b7829" />

# CIRCUIT DIAGRAM: INVERTING AMPLIFIER:
<img width="597" height="277" alt="image" src="https://github.com/user-attachments/assets/a0babb36-f3b8-4467-b8e0-8af9caed8ee1" />

# MODEL GRAPH:
<img width="450" height="228" alt="image" src="https://github.com/user-attachments/assets/235f4402-0bee-42b7-80de-38055bb37b2c" />

# CIRCUIT DIAGRAM:
# NON-INVERTING AMPLIFIER:
<img width="451" height="254" alt="image" src="https://github.com/user-attachments/assets/a13892d7-98ac-47f5-a46d-0ec4474ed449" />

# MODEL GRAPH:
# NON-INVERTING AMPLIFIER
<img width="421" height="217" alt="image" src="https://github.com/user-attachments/assets/acb72459-bb16-44df-9cb8-b8bbfb5213fe" />

# CIRCUIT DIAGRAM: DIFFERENTIAL AMPLIFIER
<img width="453" height="335" alt="image" src="https://github.com/user-attachments/assets/9de2e6f0-5af0-444c-8c7f-25ee4b922fa4" />

# MODEL GRAPH:
<img width="658" height="213" alt="image" src="https://github.com/user-attachments/assets/a41aaf0b-11ac-4694-9366-34c0028075c3" />

# DESIGN:

# TABULATION:
```
Inverting Amplifier
<img width="757" height="385" alt="Screenshot 2025-11-16 104556" src="https://github.com/user-attachments/assets/2371cba3-1507-439b-b1a6-81d679840a6c" />
Non-Inverting Amplifier
<img width="760" height="392" alt="Screenshot 2025-11-16 104647" src="https://github.com/user-attachments/assets/502ee21a-8682-4bfe-800b-7df3a3596ff5" />
Differential Amplifier
<img width="759" height="403" alt="Screenshot 2025-11-16 104807" src="https://github.com/user-attachments/assets/7c421030-92d6-4a8e-bb1f-6b4c035763de" />
```
# THEORETICAL CALCULATION:
```
<img width="571" height="817" alt="Screenshot 2025-11-16 105012" src="https://github.com/user-attachments/assets/61dd8bc8-ea77-4568-bf5f-2cdac8e1d714" />
```
# GRAPH:
<img width="664" height="790" alt="Screenshot 2025-11-16 105049" src="https://github.com/user-attachments/assets/6400c53f-c2c7-4091-b852-cbaefb1ddffd" />
<img width="617" height="550" alt="Screenshot 2025-11-16 105153" src="https://github.com/user-attachments/assets/e665fc3e-e0ae-47ad-90e3-5632562f0d6c" />
# RESULT:
Thus the inverting,Non-inverting and differential amplifiers are designed and their performance was successfully tested using op-amp IC 741.
