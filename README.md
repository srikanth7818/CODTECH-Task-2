Name: GOLLA SRIKANTH
Company: CODTECT IT SOLUTIONS
ID: CT12DS2007
Domain: VLSI
Duration: Aug to Oct 2024
Mentor: Neela Santhosh Kumar

Objective

The goal of this project is to build a temperature monitoring system. The microcontroller will read temperature data from the sensor via SPI and display the readings on an OLED screen. The system will continuously monitor the temperature and update the display in real time.

Key Activies

1. Full-Duplex Communication: SPI allows simultaneous data transmission and reception between the master and slave devices. This is achieved using separate lines for transmitting (MOSI) and receiving (MISO) data.

2. Synchronous Data Transfer: SPI uses a clock signal generated by the master to synchronize data transfer, ensuring that data is read or written at the correct times.

3. Multiple Slaves: SPI can support multiple slave devices on the same bus. Each slave is selected using a dedicated Chip Select (CS) or Slave Select (SS) line, allowing the master to communicate with only one slave at a time.

 SPI Bus Signals:
- MOSI (Master Out Slave In)**: The data line used to send data from the master to the slave.
- MISO (Serial Clock)**: The clock signal generated by the master to synchronize data transfer.
- SS/CS (Slave Select/Chip Select)**: A control line used by the master to select which slave device to communicate with. This line is active low, meaning the selected slave is active when this line is low.

SPI Modes:
SPI operates in different modes depending on the clock polarity (CPOL) and clock phase (CPHA):
- Mode 0: CPOL = 0, CPHA = 0
- Mode 1: CPOL = 0, CPHA = 1
- Mode 2: CPOL = 1, CPHA = 0
- Mode 3: CPOL = 1, CPHA = 1 (Master In Slave Out)**: The data line used to send data from the slave back to the master.
- SCLK

Technologies Used

EDA playground: For designing and verifying SPI protocol.

Block diagram

![image](https://github.com/user-attachments/assets/b441f26b-be2f-4a61-888e-88e2238912b2)


![image](https://github.com/user-attachments/assets/f23bf906-b797-4f55-9994-0055885a6817)


![image](https://github.com/user-attachments/assets/7b65c9a2-9594-4d1a-9a34-cf2aca20f8d9)





