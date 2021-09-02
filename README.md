# Criterion Validation of an Open-Source Wearable Physiological Sensors Device

This code implements the Criterion Validation code of an Open-Source Wearable Physiological Sensors Device used in the paper:

**Langevin, A.; Bégin, W.; Lavallière, M.; Beaulieu, L.; Menelas, B.; Gaboury, S.; Bouchard, K.; Gagnon, G. and Paquette, L. (2021). Criterion Validation of an Open-source Wearable Physiological Sensors Device.**

## Abstract
Wearable sensors are very popular in monitoring sport performances and increasingly used in scientiﬁc research. However, several scientiﬁc and ethical issues regarding pricing, raw data accessibility, validity and commercial access to user’s data are linked with these devices. To address these limitations, an open-source device, called Emotibit, was designed through crowdfunding. The aim of this study is to evaluate the criterion validity of this new open-source device’s physiological components in resting position. To this end, heart rate (HR) and heart rate variability (HRV) via photoplethysmography (PPG) and electrodermal activity (EDA) were assessed and compared with a medical grade reference device, the FlexComp Inﬁniti. The Bland-Altman plot and ratio (BAr) results indicate a good validity for HR estimation with a BAr of 0.02. However, results suggest an insufﬁcient validity for HRV, as well as EDA amplitude and number of activation events estimation. These results are comparable to other studies using PPG for HRV estimation, but the EDA components need adjustment in regard to the sensitivity of the device. We analyze the validity issues associated with open source technology, and conclude that further improvements are required to qualify its accuracy with statistical signiﬁcance. This study also contributes to the wearable sensors studies by identifying and describing the many challenges associated with the democratization of access to biosensing technology.

# Dataset
The collection data are in the folder **Data**. For each participant, a folder **Emotibit** contains data recorded by the open source device [Emotibit](https://www.emotibit.com/) and the folder **Flexcomp** contains reference data recorded by the [FlexComp Inﬁniti of Thought Technology Ltd](https://thoughttechnology.com/flexcomp-system-with-biograph-infiniti-software-t7555m/).

# Instruction
All the validation steps are in the Jupyter file **PPG and EDA evaluation.ipynb**.

# EDA Analyze
The SCRs extraction requires Ledalab on Matlab available at: http://www.ledalab.de/.
