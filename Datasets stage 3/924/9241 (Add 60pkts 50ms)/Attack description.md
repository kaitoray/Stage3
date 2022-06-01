# Malicious behaviour:

Network level: MU2 replayed and injected malicious SV packets (60 pkts with 50ms HB) to fake emergency situation on FDR (4 scenarios: (a)FDR1=22kV1=F_FDR1=2017; (b)FDR2=F_FDR2=2017; (c)FDR3=F_FDR3=2017; (d)FDR4=22kV3=F_FDR4=2017; interval = 1000 pkts).

Physical process level: Under normal operation, the fake emergency signals will deceive IEDs to trips CBs, and thus, disrupt power transmission.

**Attacks happen approximately at SmpCnt = 1000-1060, 2000-2060, 3000-3060, 4000-4060**