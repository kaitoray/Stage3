# Malicious behaviour:

Network level: MU1 modifies and replayed malicious SV packets (10) to fake emergency situation on TRSF (2 scenarios: 66kV1=TRSF1W1=1000,TRSF1W2=1732,TRSF1_CB=0,F_TRSF1=3000; 66kV3=TRSF2W1=1000,TRSF2W2=1732,TRSF2_CB=0,F_TRSF2=3000; interval = 2000 pkts).

Physical process level: Under normal operation, the fake emergency signals will deceive IEDs to trips CBs, and thus, disrupt power transmission.

**Attacks happen approximately at SmpCnt = 2000-2010, 4000-4010**