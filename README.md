# Freelander2_CAN_Sniffer---Release-Only
 Executable of the CAN Bus Sniffer Helper Program
 NOTE: The source code is not being released to ensure responsible usage. It includes functionality for extracting the vehicle's current mileage, which could potentially be misused for illicit purposes, such as conducting a man-in-the-middle attack to falsify the mileage displayed on the dashboard.

CAN Bus Analysis Helper Program

When used in conjunction with OBD2_Interface_v2 project by The Bionicbone this helper program can help parse the log files to remove some noise from the SavvyCAN analysis.

Functions:

- COM Recorder
- Compare Data (i.e. two files, one with reverse not selected and another with is selected)
- Point in Time


Converters:

- Log Convert Bus 0 & 1 to 1 & 2
- Log Separate Buses
- Log Remove ID (with specified Data set if required)
- Log Convert Land Rover Freelander 2 Special IDs
     - Extending multiplexed IDs so multiplexed IDs visible in each state and keeping any unchanged data in the log (i.e. CCF) 
     - Extending multiplexed IDs so multiplexed IDs visible in each state while cleansing any unchanged data (i.e. CCF) to reduce noise in SavvyCAN

![image](https://github.com/user-attachments/assets/1c78f58f-5d45-4d62-823e-51c9cacd8c16)

![image](https://github.com/user-attachments/assets/96aa986d-36b6-4492-ac2f-a1335cf78033)

![image](https://github.com/user-attachments/assets/46299210-2590-41c6-bcba-7c0d74ebcbbd)

![image](https://github.com/user-attachments/assets/067f7f2e-b3cc-4b93-87fb-58dda305da72)
