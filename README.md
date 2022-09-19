<img width="800" alt="截屏2022-09-19 下午9 50 34" src="https://user-images.githubusercontent.com/112700133/191033061-ea4a1671-26c7-4d52-b3ed-3495a2ae0292.png">

![](https://img.shields.io/badge/version-0.1-green.svg) 

****
Artifacts accompanying the paper *Eadro: An End-to-End Troubleshooting Framework for Microservices on Multi-source Data* submitted for publication at ICSE 2023. This tool try to model the intra- and inter-dependencies between microservices for troubleshooting, enabling end-to-end anomaly detection and root cause localization.

![dependency_00](https://user-images.githubusercontent.com/112700133/191036446-d4cf8d07-bd4e-4452-a3e2-f7d4e9da0624.png)

## Architecture
![Eadro_00](https://user-images.githubusercontent.com/112700133/191034412-a6999252-b37a-4302-86ca-b1c020d04319.png)

## Data
Currently, we only upload codes and a small amount of our used data (about 10% in `data_demo`) because the data contianing metadata may reveal our identity. After double-anonymous reviewing, we will make all collected data publicly available.

The `json` file records the starting and ending time for an injected fault, while the child director contains three sources of data, i.e, logs, KPIs, and traces.

## UI
The final visualized page should be like:
![interface_00](https://user-images.githubusercontent.com/112700133/191035850-efc5b72b-47cd-47ff-ac23-e065a8af7857.png)

## Concact us
🍺 Feel free to leave messages in "Issues"! 
