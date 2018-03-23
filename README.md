Raw experimental data for measurements of different LTE network quality indicators for the evaluation of Channel-aware Transmission (CAT) and predictive CAT (pCAT) with different parameterizations and metrics.

For CAT, only the results of the transmissions are provided and the single KPI-based transmissions are performed with t_min={10s, 30s}. For pCAT, the real-world traces containing live measurements of the current network quality indicators along the driven world are contained as well. The M5 Decision Tree (M5T) metric is further evaluated for Phi_max={15 MBit/s, 18 MBit/s} and with variing prediction horizon tau={10s, 30s, 60s}

Within the filenames of the measurements, t1 is referring to the suburban evaluation track and t2 is related to the highway scenario.

[![DOI](https://zenodo.org/badge/126449508.svg)](https://zenodo.org/badge/latestdoi/126449508)

### Connectivity map

The origin for the map is 51.4371,7.3929 and the cell size for the data aggregation is 25m * 25m.

### Data format for traces [Second-wise measurements]
* Trip duration [s]
* Driven distance [m]
* Latitude
* Longitude
* Altitude
* Velocity [m/s]
* Angular Direction
* LTE Connection [true/false]
* SNR [dB]
* RSRP [dB]
* RSRQ [dB]
* CQI
* ASU
* Signal Strength [dB]
* Timing Advance
* Cell Identity (CI)
* Mobility Country Code (MNC)
* Mobile Network Code (MNC)
* Physical Cell ID (PCI)
* Tracking Area Code (TAC)

### Data format for transmissions
* Transmission time since evaluation start [s]
* Payload size [MB]
* Transmission duration [s]
* Throughput [MBit/s]
* Average data age [s]
* SNR [dB]
* RSRP [dB]
* RSRQ [dB]
* CQI
* ASU
* Transmission time since evaluation start (HTTP Level) [s]
* Transmissions attempts since last ack
* Acks since last Acks
* Velocity [km/h]


### Filenames
 * Time DDMMYY-HHMMSS
 * (optinal) Track ID: t1/t2
 * Transmission Scheme
 * Tmin

### License

See the [LICENSE](LICENSE.md) file for license rights and limitations (MIT).
