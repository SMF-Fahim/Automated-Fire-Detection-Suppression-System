# Automated-Fire-Detection-Suppression-System
This report describes an educational prototype that detects a possible fire condition using two LM741 operational-amplifier stages. A photodiode provides the first, flame-light sensing condition. A TMP36 temperature sensor and an adjustable potentiometer provide the second, temperature-verification condition. When the intended conditions are satisfied, the output stage switches a DC motor intended to operate a water pump and activates a buzzer for an audible warning. LEDs provide visual status indication.
Main operating sequence
•	Flame-light sensing: the photodiode and its resistor network produce a voltage that changes with incident light.
•	First comparison: LM741 stage 1 compares the photodiode voltage with a reference and changes its output when the selected light threshold is crossed.
•	Temperature verification: the first stage enables the second sensing stage. The TMP36 output is compared with a threshold adjusted using the potentiometer.
•	Output response: the second LM741 stage activates the output-control circuit. An NPN transistor switches the DC motor/pump, and a buzzer provides an audible alert.
•	Status indication: LEDs show the relevant detection/output states.

