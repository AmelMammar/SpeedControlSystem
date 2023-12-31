# SpeedControlSystem
This repository contains the following elements: 
1. The archive of the Event-B modeling of a Speed Control System (SCC): The Event-B project has been developed and proved under Rodin (Version:  3.8.0-af2f57e1e). To replay the proof obligations, you need to install the following external provers:
  - STM provers
  - PRoB (dis)Prove using ProB 
  - Mono-Lemna prover
2. The requirement document describing the case study.
3. The Event-B models in a pdf format

Installation instructions
To import the Event-B project under Rodin, you should select the option Import under the menu File and follow these steps:

<img width="261" alt="import" src="https://github.com/AmelMammar/SpeedControlSystem/assets/60692373/ef090d35-ebf5-40fe-9467-7bb95d82dec6">

<img width="280" alt="replay" src="https://github.com/AmelMammar/SpeedControlSystem/assets/60692373/f56d0414-bcab-4ccb-a5bb-f9bdb131475f">

<img width="438" alt="selectP" src="https://github.com/AmelMammar/SpeedControlSystem/assets/60692373/ef875cec-067c-4514-9b85-2aa7f188471c">

<img width="425" alt="file" src="https://github.com/AmelMammar/SpeedControlSystem/assets/60692373/73fdcdb0-fbb4-436f-b4b2-755a40f60ce8">


After importing the Zip file CBA.zip under the Rodin platform (Version: 3.8.0-af2f57e1e), some profs may appear as not discharged. So, you should replay all the proofs by a right click as depicted by the following figure:

<img width="280" alt="replay" src="https://github.com/AmelMammar/SpeedControlSystem/assets/60692373/6968a863-570f-4b90-a377-8fc70a1823d3">

To discharge the interactive proofs, we have imported the AtelierB provers, ProB Disprover and the SMT provers as depicted by the following figure:

![ProBDis](https://github.com/AmelMammar/SpeedControlSystem/assets/60692373/d97f69ce-3535-4e69-95d0-7dc052816da4)

To install the external provers, users should select the "Install New Software" menu and then select the desired plugin:
![386881157_252795020992632_2078631935947026497_n](https://github.com/AmelMammar/SpeedControlSystem/assets/60692373/fb31dc89-c2fe-49be-8401-e978d8f257d7)
