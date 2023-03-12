## Academic Attribution:

This tool is part of achieved results in the PhD of **David A. Nascimento**.

If you use it for research, please include the following reference in any resulting publication.

```
@ARTICLE{PLCA_TAS:2023,
  author={Nascimento, David A. and Bondorf, Steffen and Campelo, Divanilson R.},
  journal={IEEE Transactions on Communications}, 
  title={Modeling and Analysis of Time-Aware Shaper on Half-Duplex Ethernet PLCA Multidrop}, 
  year={2023},
  volume={},
  number={},
  pages={1-1},
  doi={10.1109/TCOMM.2023.3246080}
}
```

# How to use this repository?

1. Clone the DNC repository following the instructions on https://github.com/NetCal/DNC 

2. Clone this repository in your computer and import **DNC-EthernetTSN** project in Eclipse in "File" -> "Import" -> "General" -> "Existing Projects into Workspace"

# How to run this code?

Run main file **Ethernet_IEEE_TransOnComm_2022_paper.java** of package **org.networkcalculus.dnc.ethernet.demos**.

Results will be salved in **results** directory. 
They include:
- Excel sheets with all calculated parameters of each TAS window.
- Chart for each TAS window and their combination regarding the multidrop access with PLCA in each scheduling case.
- Chart for each Arrival and Service Curves used in each scheduling case.
- ServerGraph for each scheduling case which enables it to be run into DNC if one wants.
- Excel sheets with all results for all scheduling cases.
