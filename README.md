# SAM2-OV
Official implementation of the paper  

**"SAM2-OV: A Novel Detection-Only Tuning Paradigm for Open-Vocabulary Multi-Object Tracking" (AAAI 2026)**  

![Pipeline](data/framework.jpg)

### Main Results

####  TAO Validation Set

| Method          | LVIS | TAO  | Novel TETA | Novel LocA | Novel AssocA | Novel ClsA | Base TETA | Base LocA | Base AssocA | Base ClsA |
| --------------- | ---- | ---- | ---------: | ---------: | -----------: | ---------: | --------: | --------: | ----------: | --------: |
| DeepSORT (ViLD) | ✓    | ✓    |       21.1 |       46.4 |         14.7 |        2.3 |      26.9 |      47.1 |        15.8 |      17.7 |
| QDTrack*        | ✓    | ✓    |       22.5 |       42.7 |         24.4 |        0.4 |      27.1 |      45.6 |        24.7 |      11.0 |
| TETer*          | ✓    | ✓    |       25.7 |       45.9 |         31.1 |        0.2 |      30.3 |      47.4 |        31.6 |      12.1 |
| OVTrack         | ✓    | –    |       27.8 |       48.8 |         33.6 |        1.5 |      35.5 |      49.3 |        36.9 |  **20.2** |
| MASA            | ✓    | –    |       30.0 |       54.2 |         34.6 |        1.0 |      36.9 |  **55.1** |        36.4 |      19.3 |
| OVTR            | ✓    | –    |       31.4 |       54.4 |         34.5 |        5.4 |      36.6 |      52.2 |        37.6 |      20.1 |
| SLAck           | ✓    | –    |       31.1 |       54.3 |         37.8 |        1.3 |      37.2 |      55.0 |        37.6 |      19.1 |
| SAM2-OV (Ours)  | ✓    | –    |   **37.9** |   **57.6** |     **48.5** |    **7.4** |  **39.8** |      52.4 |    **51.6** |      15.4 |

#### TAO Test Set

| Method          | LVIS | TAO  | Novel TETA | Novel LocA | Novel AssocA | Novel ClsA | Base TETA | Base LocA | Base AssocA | Base ClsA |
| --------------- | ---- | ---- | ---------: | ---------: | -----------: | ---------: | --------: | --------: | ----------: | --------: |
| DeepSORT (ViLD) | ✓    | ✓    |       17.2 |       38.4 |         11.6 |        1.7 |      24.5 |      43.8 |        14.6 |      15.2 |
| QDTrack*        | ✓    | ✓    |       20.2 |       39.7 |         20.9 |        0.2 |      25.8 |      43.2 |        23.5 |      10.6 |
| TETer*          | ✓    | ✓    |       21.7 |       39.1 |         25.9 |        0.0 |      29.2 |      44.0 |        30.4 |      10.7 |
| OVTrack         | ✓    | –    |       24.1 |       41.8 |         28.7 |        1.8 |      32.6 |      45.6 |        35.4 |  **16.9** |
| OVTR            | ✓    | –    |       27.1 |       47.1 |         32.1 |    **2.1** |      34.5 |      51.1 |        37.5 |      14.9 |
| SLAck           | ✓    | –    |       27.1 |       49.1 |         30.0 |        2.0 |      34.7 |      52.5 |        35.6 |      16.1 |
| SAM2-OV (Ours)  | ✓    | –    |   **32.8** |   **52.6** |     **44.1** |        1.7 |  **41.0** |  **55.6** |    **55.6** |      11.8 |

### Code

🚧 Code is coming soon.

### License

[![Code License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0) **Usage and License Notices**: The code are intended and licensed for research use only. 

