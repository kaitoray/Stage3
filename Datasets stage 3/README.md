# Datasets for stage 3

The datasets were collected from a software based simulation environment simulating a small scale IEC 61850 compliant substation with both the primary plant and the process bus.

The datasets consist of 148 attack scenarios, each scenario include two benign behaviours (fault-free behaviours and emergency behaviours) and one type of malicious behaviours. 

All attack scenarios are derived from two types of false data injection attacks (FDIAs): 1) modification of data in the original message, and 2) addition of fake messages. Different attack configurations were applied to generate a variety of datasets, such as injecting or modifying different numbers of packets, injecting packets in different frequencies, and slightly increasing original measurements with certain ratios.

To avoid flooding messages in the process bus, during the simulation, we scale up the heartbeat of SV packets from the 250ns to 50ms. Thus, Each dataset contain oringal timestamps (collected from the simulation), and scaled timestamps which were scaled down by 200 times to synchronise with the real-time behaviours in industrial practice.

**The details of each dataset and attack scenario are explained and listed in "Attack Scenario details.xlsx"**
**The location and file name of each scenario or each dataset is demonstrated in "Attack Scenario details.xlsx"**

For example, attack scenario 9432 has one orignal dataset called **IED_TRSF1_SV.csv**, one merged dataset called **Data.xlsx**, and two final datasets called **5_2.xlsx** and **6_2.xlsx**, in the location of /943/9432 (Add all 25ms).
