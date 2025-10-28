# EGV-9B-9-Band-QRP-CW-Transceiver-Build-Modification

1. Summary

A hands-on project to build the EGV-9B, a complex 9-band QRP CW transceiver kit from EA3GCY. After a meticulous assembly process, the transceiver was enhanced with several custom modifications to improve operator feedback and usability, including a TX LED, a Sotabeams digital audio filter, and a zero-beat indicator.

The project involved detailed soldering, component testing, calibration, and a systematic "burn-in" process to ensure stability.

2. The Build

The EGV-9B is an advanced kit with a high component count. The build was complex but went smoothly overall due to the clear and detailed instructions provided by EA3GCY.

Difficulties Encountered: The most challenging parts included winding numerous toroids for the transformers, band-pass filters (BPF), and low-pass filters (LPF), as well as the delicate installation of the screen. A pin strip was damaged during the build and had to be replaced.

Initial Power-On: The radio powered on successfully from the get-go and showed correct TX operation into a dummy load.

3. Modifications & Enhancements

After the base assembly, several modifications were added to improve the "user experience" and functionality of the transceiver:

Modification 1: TX LED Indicator

Added a simple LED circuit to provide clear visual confirmation that the transceiver is in transmit mode.

Modification 2: Sotabeams Digital Audio Filter

Integrated a Sotabeams audio filter module to enhance the receiver's CW selectivity. This provides two filter widths: a narrow 300Hz for crowded band conditions and a wider 1000Hz for general searching.

Modification 3: Zero Beat LED

Leveraging a feature from the Sotabeams filter, a zero-beat indicator LED was added, which simplifies tuning and ensures the received station is at the correct pitch.

4. Testing, Calibration & Results

A systematic process was followed to calibrate and validate the transceiver's performance before its first on-air use.

Initial Calibration: Calibrated the BFO (Beat Frequency Oscillator) and the main XTAL oscillator to ensure correct frequency alignment.

Performance Baseline: Initial sensitivity was measured at approximately -105dBm, which is a very good result for this class of receiver.

Burn-In & Stability Test: To ensure the stability of the crystal oscillator (which is not oven-controlled), the radio was left running for several days connected to a dummy load, with power-off cycles for battery charging and "cold-soak" testing outside at ~5°C.

Final Status: The radio is now fully operational. RBN (Reverse Beacon Network) reports look good, and I have several successful QSOs in the log. A recalibration is planned in one month to adjust for any component drift after the burn-in period.

5. Next Steps

An outdoor portable test is scheduled to validate its performance in a field environment.

5. Acknowledgements

I had invaluable advice and support from my friends Theodoros (SV1SYM) and Tony (EI5EM). Thanks, guys!

6. Photos
![Image](https://github.com/user-attachments/assets/64d2cd1d-6308-4679-99df-9fd5a1e28074)

![Image](https://github.com/user-attachments/assets/47208bc0-0500-441e-b393-c59a0785c205)

![Image](https://github.com/user-attachments/assets/baf608ae-8856-4c3e-bb01-e891d9c8bdfd)

![Image](https://github.com/user-attachments/assets/3e82bb7d-bad6-47fa-8ecf-5d1249c936a9)

![Image](https://github.com/user-attachments/assets/50724d69-c5b3-46fb-9f51-178bdafd7e82)

![Image](https://github.com/user-attachments/assets/7999d70b-d5b0-4f88-a052-ad5389ae24f0)

![Image](https://github.com/user-attachments/assets/afc0e1e7-c2b7-483d-af1f-f7ee1c563118)

Overall it was a lot of fun, I operate regularly using this rig both from home and portable.

73 de Nik SV1SYY
