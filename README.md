# GENERATION-AND-DETECTION-OF-FM---USING---SCILAB---T1---M4---ODD
# FREQUENCY MODULATION AND DEMODULATION

## AIM

To write a program for Frequency Modulation and Demodulation using SCILAB and to observe and measure the frequency deviation and the modulation index of FM.

---

## EQUIPMENTS REQUIRED

* Computer with i3 Processor
* SCI LAB

---

## THEORY

Frequency modulation is a type of modulation in which the frequency of the high frequency (carrier) is varied in accordance with the instantaneous value of the modulating signal.

### FREQUENCY DEVIATION Δf and MODULATION INDEX mf:

The frequency deviation **Δf** represents the maximum shift between the modulated signal frequency, over and under the frequency of the carrier.

We define modulation index **mf** the ratio between **Δf** and the modulating frequency.

$$
m_f = \frac{\Delta f}{f_m}
$$

---

## FREQUENCY MODULATION GENERATION

The circuits used to generate a frequency modulation must vary the frequency of a high frequency signal (carrier) as function of the amplitude of a low frequency signal (modulating signal). In practice there are two main methods used to generate FM.

---

## ALGORITHM

### 1. Define Parameters:

* **Fs:** Sampling frequency.
* **T:** Duration of the signal.
* **Fc:** Carrier frequency.
* **Fm:** Frequency of the modulating signal.
* **Beta:** Modulation index, which controls the extent of frequency deviation.

### 2. Generate Signals:

* **modulating_signal:** Sinusoidal signal used for modulation.
* **carrier_signal:** The high-frequency carrier signal.
* **modulated_signal:** FM modulated signal calculated by varying the carrier frequency according to the modulating signal.

### 3. FM Modulation:

* **Modulated_signal** is obtained by modulating the carrier signal with the modulating signal.

### 4. FM Demodulation:

* **Differentiation:** Computes the derivative of the modulated signal to extract frequency variations.
* **Envelope Detection:** Takes the absolute value to retrieve the envelope of the signal.
* **Low-pass Filtering:** Applies a Butterworth low-pass filter to smooth the envelope and recover the original modulating signal.

### 5. Visualization:

* Plots the modulating signal, carrier signal, FM modulated signal, and demodulated signal for analysis.

---

## PROCEDURE

* Refer Algorithms and write code for the experiment.
* Open SCILAB in System.
* Type your code in New Editor.
* Save the file.
* Execute the code.
* If any Error, correct it in code and execute again.
* Verify the generated waveform using Tabulation and Model Waveform.

---

## TABULATION
<img width="874" height="1309" alt="image" src="https://github.com/user-attachments/assets/988ca725-3362-41ef-9edc-53bf3ebbfa53" />

## CALCULATION
<img width="747" height="1493" alt="image" src="https://github.com/user-attachments/assets/a8c51241-0f98-46d0-a2f1-62655f9e5288" />
## RESULT 
The Frequency Modulation is generated successfully.
