# EXP.NO.1-EXPERIMENTAL-VERIFICATION-OF-VARIOUS-TYPES-OF-SAMPLING-TECHNIQUES
 

1.Experimental Verification Of Signal Sampling Using Various Types Such as 
    i) Natural Sampling
    ii) Flat Top Sampling

## AIM
 To perform experimental verification of various types of sampling such as natural sampling and flat top sampling.
## APPARATUS REQUIRED
Trainer Kit, DSO(10MHz) , Patch Cords and Power Supply (0-30V)   
## PROCEDURE
1. Generate a continuous-time analog input waveform (e.g., a sinusoidal signal at 1 kHz) using a function generator.
2. Utilize a dedicated sampling circuit that provides the capability to switch between natural and flat-top sampling operations.
3. Employ a second function generator or a timing control unit to produce the sampling pulse train (typically a rectangular wave with a frequency significantly higher than the input signal, for example, 8 kHz or more).
4. Connect the output of the sampling circuit to the input channel of the digital storage oscilloscope to visualize the resulting sampled signal.
5. Optionally, for signal reconstruction analysis, connect the sampled output to the input of a low-pass filter and observe the recovered waveform.
6. Initialize the sampling circuit to operate in the natural sampling mode.
7. Apply the 1 kHz sine wave (or a similar analog signal) as the input to the sampling circuit.
8. Introduce the sampling pulse train (a rectangular waveform with a narrow duty cycle, such as 10%) as the sampling control signal.
9. Observe and record the output waveform displayed on the oscilloscope.
10. You should observe segments of the input signal being transmitted during the active intervals of each sampling pulse.
11. Analyze the form of the sampled signal and compare its characteristics with the original continuous input waveform.
12. If a low-pass filter is connected, examine its output to determine the effectiveness of the original signal's recovery.
13. Repeat the above steps for both sample-and-hold and flat-top sampling modes of operation.
14. Generate appropriate graphical representations of the observed waveforms for each sampling method and interpret the results.

## CIRCUIT DIAGRAM
![Screenshot 2025-05-11 210921](https://github.com/user-attachments/assets/39a273a0-f56a-482d-b0eb-37315bd884e3)
![Screenshot 2025-05-11 210936](https://github.com/user-attachments/assets/84b9603c-58a5-462a-a7af-9c4fa2ab65f0)



## MODEL GRAPH
![Screenshot 2025-05-11 210958](https://github.com/user-attachments/assets/ddaa4e3c-3cd2-4aa4-9dd9-3a5d47a56328)
![Screenshot 2025-05-11 211013](https://github.com/user-attachments/assets/cbce7f9f-2a0c-4dd8-a332-83d48de25cc5)



## TABLE
![Screenshot 2025-05-11 211258](https://github.com/user-attachments/assets/d2e191b3-03ce-4e9a-a23e-000122efa74c)


## OUTPUT GRAPHS
![Screenshot 2025-05-11 211733](https://github.com/user-attachments/assets/a6ddb205-b119-4232-a896-78bf7aec0e2f)
![Screenshot 2025-05-11 211749](https://github.com/user-attachments/assets/78b9a90a-b634-4b33-85f3-d8afb2cdaa16)
![Screenshot 2025-05-11 211804](https://github.com/user-attachments/assets/7340f9c4-4dfb-4c28-a7e3-2cbea7edf035)



## RESULT 
Thus the sapmpling and reconstruction of the given input signal is done using different types of sampling techniques.
