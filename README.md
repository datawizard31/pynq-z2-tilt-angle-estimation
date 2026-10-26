# pynq-z2-tilt-angle-estimation
Accelerometer interfacing and roll-pitch angle estimation using PYNQ-Z2 and Python.

PYNQ-Z2 Based Tilt Angle Estimation

Overview

This project explores accelerometer interfacing and roll and pitch angle estimation using the PYNQ-Z2 development board and Python.

Hardware

- PYNQ-Z2 development board
- MPU-series accelerometer/gyroscope module (exact model to be verified)

Technologies

- Python
- Jupyter Notebook
- I²C communication
- Xilinx Vivado
- Xilinx Zynq-7000 SoC

Features

- Reads raw acceleration data through I²C.
- Converts sensor readings into signed numerical values.
- Calculates roll and pitch angles using trigonometric functions.
- Measures angle-estimation latency and analyses sensor-reading performance.

Project Files

- "design_1.bit": FPGA bitstream.
- "design_1.hwh": Hardware handoff metadata.
- "tilt_angle_estimation.ipynb": Python implementation (add the actual notebook).

Results

The tested implementation recorded an average angle-estimation latency of approximately 1.52 ms. Measurement conditions and timing scope should be documented for reproducibility.

How to Run

1. Set up the PYNQ-Z2 board.
2. Load the matching FPGA overlay and hardware metadata, if required by the implementation.
3. Connect the supported sensor to the correct I²C interface.
4. Open the Jupyter Notebook on the PYNQ environment.
5. Run the cells and observe the calculated angles.

Author

Add your name and LinkedIn profile here.
