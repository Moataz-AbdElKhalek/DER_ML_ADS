This is a sample DNP3 dataset for DER networks in the smart grid that can be used for anomaly detection using machine learning.

This dataset was part of the analysis used for the paper:

"ML-based Anomaly Detection System for DER DNP3 Communication in Smart Grid," by Moataz Abdelkhalek and Manimaran Govindarasu, published in 2022 IEEE International Conference on Cyber Security and Resilience (CSR), 2022, pp. 209-214, doi: 10.1109/CSR54599.2022.9850313.

Any use of the dataset must include a citation to the dataset and the paper.


This dataset contains 79 features listed as follows:

--------------------------------------------------------------
| Feature Name               | Description                                                                                                                                  |
|----------------------------|----------------------------------------------------------------------------------------------------------------------------------------------|
| Dst Port                   | Destination Port<br>(Src/Dst IP and Src Port were removed from the dataset for privacy purposes)                                             |
| Protocol                   | The network protocol number<br>(based on IANA Protocol Numbers <br>https://www.iana.org/assignments/protocol-numbers/protocol-numbers.xhtml) |
| Flow duration              | Duration of the flow in Microsecond                                                                                                          |
| total Fwd Packet           | Total packets in the forward direction                                                                                                       |
| total Bwd packets          | Total packets in the backward direction                                                                                                      |
| total Length of Fwd Packet | Total size of packet in forward direction                                                                                                    |
| total Length of Bwd Packet | Total size of packet in backward direction                                                                                                   |
| Fwd Packet Length Min      | Minimum size of packet in forward direction                                                                                                  |
| Fwd Packet Length Max      | Maximum size of packet in forward direction                                                                                                  |
| Fwd Packet Length Mean     | Mean size of packet in forward direction                                                                                                     |
| Fwd Packet Length Std      | Standard deviation size of packet in forward direction                                                                                       |
| Bwd Packet Length Min      | Minimum size of packet in backward direction                                                                                                 |
| Bwd Packet Length Max      | Maximum size of packet in backward direction                                                                                                 |
| Bwd Packet Length Mean     | Mean size of packet in backward direction                                                                                                    |
| Bwd Packet Length Std      | Standard deviation size of packet in backward direction                                                                                      |
| Flow Byte/s                | Number of flow packets per second                                                                                                            |
| Flow Packets/s             | Number of flow bytes per second                                                                                                              |
| Flow IAT Mean              | Mean time between two packets sent in the flow                                                                                               |
| Flow IAT Std               | Standard deviation time between two packets sent in the flow                                                                                 |
| Flow IAT Max               | Maximum time between two packets sent in the flow                                                                                            |
| Flow IAT Min               | Minimum time between two packets sent in the flow                                                                                            |
| Fwd IAT Min                | Minimum time between two packets sent in the forward direction                                                                               |
| Fwd IAT Max                | Maximum time between two packets sent in the forward direction                                                                               |
| Fwd IAT Mean               | Mean time between two packets sent in the forward direction                                                                                  |
| Fwd IAT Std                | Standard deviation time between two packets sent in the forward direction                                                                    |
| Fwd IAT Total              | Total time between two packets sent in the forward direction                                                                                 |
| Bwd IAT Min                | Minimum time between two packets sent in the backward direction                                                                              |
| Bwd IAT Max                | Maximum time between two packets sent in the backward direction                                                                              |
| Bwd IAT Mean               | Mean time between two packets sent in the backward direction                                                                                 |
| Bwd IAT Std                | Standard deviation time between two packets sent in the backward direction                                                                   |
| Bwd IAT Total              | Total time between two packets sent in the backward direction                                                                                |
| Fwd PSH flag               | Number of times the PSH flag was set in packets travelling in the forward direction (0 for UDP)                                              |
| Bwd PSH Flag               | Number of times the PSH flag was set in packets travelling in the backward direction (0 for UDP)                                             |
| Fwd URG Flag               | Number of times the URG flag was set in packets travelling in the forward direction (0 for UDP)                                              |
| Bwd URG Flag               | Number of times the URG flag was set in packets travelling in the backward direction (0 for UDP)                                             |
| Fwd Header Length          | Total bytes used for headers in the forward direction                                                                                        |
| Bwd Header Length          | Total bytes used for headers in the backward direction                                                                                       |
| FWD Packets/s              | Number of forward packets per second                                                                                                         |
| Bwd Packets/s              | Number of backward packets per second                                                                                                        |
| Min Packet Length          | Minimum length of a packet                                                                                                                   |
| Max Packet Length          | Maximum length of a packet                                                                                                                   |
| Packet Length Mean         | Mean length of a packet                                                                                                                      |
| Packet Length Std          | Standard deviation length of a packet                                                                                                        |
| Packet Length Variance     | Variance length of a packet                                                                                                                  |
| FIN Flag Count             | Number of packets with FIN                                                                                                                   |
| SYN Flag Count             | Number of packets with SYN                                                                                                                   |
| RST Flag Count             | Number of packets with RST                                                                                                                   |
| PSH Flag Count             | Number of packets with PUSH                                                                                                                  |
| ACK Flag Count             | Number of packets with ACK                                                                                                                   |
| URG Flag Count             | Number of packets with URG                                                                                                                   |
| CWR Flag Count             | Number of packets with CWE                                                                                                                   |
| ECE Flag Count             | Number of packets with ECE                                                                                                                   |
| down/Up Ratio              | Download and upload ratio                                                                                                                    |
| Average Packet Size        | Average size of packet                                                                                                                       |
| Avg Fwd Segment Size       | Average size observed in the forward direction                                                                                               |
| AVG Bwd Segment Size       | Average number of bytes bulk rate in the backward direction                                                                                  |
| Fwd Header Length          | Length of the forward packet header                                                                                                          |
| Fwd Avg Bytes/Bulk         | Average number of bytes bulk rate in the forward direction                                                                                   |
| Fwd AVG Packet/Bulk        | Average number of packets bulk rate in the forward direction                                                                                 |
| Fwd AVG Bulk Rate          | Average number of bulk rate in the forward direction                                                                                         |
| Bwd Avg Bytes/Bulk         | Average number of bytes bulk rate in the backward direction                                                                                  |
| Bwd AVG Packet/Bulk        | Average number of packets bulk rate in the backward direction                                                                                |
| Bwd AVG Bulk Rate          | Average number of bulk rate in the backward direction                                                                                        |
| Subflow Fwd Packets        | The average number of packets in a sub flow in the forward direction                                                                         |
| Subflow Fwd Bytes          | The average number of bytes in a sub flow in the forward direction                                                                           |
| Subflow Bwd Packets        | The average number of packets in a sub flow in the backward direction                                                                        |
| Subflow Bwd Bytes          | The average number of bytes in a sub flow in the backward direction                                                                          |
| Init_Win_bytes_forward     | The total number of bytes sent in initial window in the forward direction                                                                    |
| Init_Win_bytes_backward    | The total number of bytes sent in initial window in the backward direction                                                                   |
| Act_data_pkt_forward       | Count of packets with at least 1 byte of TCP data payload in the forward direction                                                           |
| min_seg_size_forward       | Minimum segment size observed in the forward direction                                                                                       |
| Active Min                 | Minimum time a flow was active before becoming idle                                                                                          |
| Active Mean                | Mean time a flow was active before becoming idle                                                                                             |
| Active Max                 | Maximum time a flow was active before becoming idle                                                                                          |
| Active Std                 | Standard deviation time a flow was active before becoming idle                                                                               |
| Idle Min                   | Minimum time a flow was idle before becoming active                                                                                          |
| Idle Mean                  | Mean time a flow was idle before becoming active                                                                                             |
| Idle Max                   | Maximum time a flow was idle before becoming active                                                                                          |
| Idle Std                   | Standard deviation time a flow was idle before becoming active                                                                               |
