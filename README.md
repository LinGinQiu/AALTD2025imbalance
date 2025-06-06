# Webpage for "e-SMOTE: a train set rebalancing algorithm for  time series classification"

Repository for AALTD 2025 submission Paper ID: 41.

## Datasets

The dataset files used are available in `.ts` format in the `UCR_Imbalanced_9_1` folder.
The following table provides details for each dataset. * indicates that the dataset is originally a two-class problem.

| Dataset | Train Maj. | Train Min. | Test Maj. | Test Min. |
|---------|-----------|-----------|----------|----------|
| ACSF1 | 90 | 10 | 90 | 10 |
| AconityMINIPrinterLarge_eq* | 1585 | 176 | 781 | 86 |
| AconityMINIPrinterSmall_eq* | 423 | 47 | 209 | 23 |
| AllGestureWiimoteX_eq | 270 | 30 | 630 | 70 |
| AllGestureWiimoteY_eq | 270 | 30 | 630 | 70 |
| AllGestureWiimoteZ_eq | 270 | 30 | 630 | 70 |
| AsphaltObstaclesUni_eq | 279 | 31 | 280 | 31 |
| AsphaltPavementTypeUni_eq | 647 | 71 | 648 | 72 |
| AsphaltRegularityUni_eq* | 381 | 42 | 381 | 42 |
| ChlorineConcentration | 353 | 39 | 2954 | 328 |
| Computers* | 125 | 13 | 125 | 13 |
| Covid3Month_disc | 104 | 11 | 44 | 4 |
| CricketX | 342 | 38 | 243 | 27 |
| CricketY | 252 | 28 | 333 | 37 |
| CricketZ | 288 | 32 | 297 | 33 |
| Crop | 2700 | 300 | 6300 | 700 |
| DistalPhalanxOutlineAgeGroup | 270 | 30 | 124 | 13 |
| DistalPhalanxOutlineCorrect* | 378 | 42 | 161 | 17 |
| DistalPhalanxTW | 261 | 29 | 121 | 13 |
| EOGHorizontalSignal | 270 | 30 | 270 | 30 |
| EOGVerticalSignal | 270 | 30 | 270 | 30 |
| Earthquakes* | 264 | 29 | 104 | 11 |
| ElectricDeviceDetection* | 543 | 60 | 3238 | 359 |
| ElectricDevices | 6695 | 743 | 5755 | 639 |
| EthanolLevel | 378 | 42 | 374 | 41 |
| FaceAll | 360 | 40 | 648 | 72 |
| FiftyWords | 398 | 44 | 398 | 44 |
| Fish | 149 | 16 | 151 | 16 |
| FloodModeling1_disc* | 344 | 38 | 151 | 16 |
| FloodModeling2_disc* | 369 | 41 | 135 | 15 |
| FloodModeling3_disc* | 329 | 36 | 126 | 14 |
| FordA* | 1846 | 205 | 681 | 75 |
| FordB* | 1860 | 206 | 409 | 45 |
| GestureMidAirD1_eq | 144 | 16 | 90 | 10 |
| GestureMidAirD2_eq | 144 | 16 | 90 | 10 |
| GestureMidAirD3_eq | 144 | 16 | 90 | 10 |
| GesturePebbleZ1_eq | 110 | 12 | 143 | 15 |
| GesturePebbleZ2_eq | 120 | 13 | 133 | 14 |
| HandOutlines* | 638 | 70 | 237 | 26 |
| Haptics | 137 | 15 | 248 | 27 |
| InsectWingbeatSound | 180 | 20 | 1620 | 180 |
| KeplerLightCurves | 153 | 17 | 72 | 8 |
| LargeKitchenAppliances | 250 | 27 | 250 | 27 |
| MedicalImages | 315 | 35 | 683 | 75 |
| MelbournePedestrian_nmv | 882 | 98 | 1710 | 190 |
| MiddlePhalanxOutlineAgeGroup | 345 | 38 | 117 | 13 |
| MiddlePhalanxOutlineCorrect* | 388 | 43 | 166 | 18 |
| MixedShapesRegularTrain | 400 | 44 | 1967 | 218 |
| NonInvasiveFetalECGThorax1 | 324 | 36 | 432 | 48 |
| NonInvasiveFetalECGThorax2 | 324 | 36 | 432 | 48 |
| OSULeaf | 166 | 18 | 210 | 23 |
| PLAID_eq | 171 | 19 | 171 | 19 |
| PhalangesOutlinesCorrect* | 1172 | 130 | 526 | 58 |
| PhoneHeartbeatSound | 251 | 27 | 100 | 11 |
| PowerCons* | 90 | 10 | 90 | 10 |
| ProximalPhalanxOutlineAgeGroup | 328 | 36 | 153 | 17 |
| ProximalPhalanxOutlineCorrect* | 406 | 45 | 199 | 22 |
| RefrigerationDevices | 250 | 27 | 250 | 27 |
| ScreenType | 250 | 27 | 250 | 27 |
| SemgHandGenderCh2* | 150 | 16 | 390 | 43 |
| SemgHandMovementCh2 | 375 | 41 | 375 | 41 |
| SemgHandSubjectCh2 | 360 | 40 | 360 | 40 |
| SharePriceIncrease* | 663 | 73 | 663 | 73 |
| SmallKitchenAppliances | 250 | 27 | 250 | 27 |
| StarLightCurves | 848 | 94 | 7059 | 784 |
| Strawberry* | 394 | 43 | 238 | 26 |
| SwedishLeaf | 261 | 29 | 414 | 46 |
| SyntheticControl | 250 | 27 | 250 | 27 |
| Tools | 266 | 29 | 117 | 13 |
| TwoPatterns | 729 | 81 | 2965 | 329 |
| UWaveGestureLibraryX | 774 | 86 | 3145 | 349 |
| UWaveGestureLibraryY | 774 | 86 | 3145 | 349 |
| UWaveGestureLibraryZ | 774 | 86 | 3145 | 349 |
| Wafer* | 873 | 97 | 5499 | 611 |
| WormsTwoClass* | 105 | 11 | 44 | 4 |
| Yoga* | 163 | 18 | 1607 | 178 |

## Parameters

The following table provides classifier parameters used.

| Classifier | Short Name | Parameters |
|------------|------------|------------|
| 1-NN DTW | DTW | Warping window: Full |
| Proximity Forest | PF | Number of trees: 100, Number of splits: 5 |
| FreshPRINCE | FP | Classifier: Rotation Forest with 200 trees, Parameter set: comprehensive |
| H-InceptionTime | H-IT | Ensemble size: 5, Batch size: 64, Inception modules: 6, Kernel size: 40, Max pooling size: 3, Number of epochs: 1500, Number of layers: 3, Inception filters: 32 |
| QUANT | Quant | Classifier: Extra trees with 200 trees, Interval depth: 6, Quantile divisor: 4 |
| WEASEL V2.0 | W2 | Classifier: Logistic regression, Alphabet size: 2, Max feature count: 30000 |
| Random Dilated Shapelet Transform | RDST | Number of shapelets: 10000, Normalization chance: 0.8, Alpha similarity: 0.5 |
| HIVE-COTE V2 | HC2 | Alpha: 4 |
| MultRocket-Hydra | MRHydra | Classifier: Ridge with cross-validation, MR kernels: 10000, g: Hydra groups, Hydra kernels per group: 8 |
| Rotation Forest | RotF | Number of trees: 200 |