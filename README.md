# Project Overview
## Problem Statement:

The analytics department of an elderly care facility wants to implement an effective anomaly detection system to identify instances of falls among their residents. They have deployed IoT sensors in the residents' living spaces to capture movement and activity data. The objective is to develop a robust anomaly detection solution that can accurately detect and alert caregivers about fall events, ensuring timely response and intervention.

## Data Description:

The dataset available is collected from IoT sensors installed in the rooms of elderly residents. The data includes sensor positions at each sample, labeled x, y or z. 010-000-024-033, 010-000-030-096, 020-000-032-221 and 020-000-033-111 are one-hot encoded representations of each sensor activity. Four sensors were used during the experiments, which have been fixed to the persons chest, ankles and belt.

*The labels represent the falling/normal-living event, where 0 is normal and 1 is the anomalous event of falling.*
