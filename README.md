# Open-Source Software (OSS) for developing appropriate smart manufacturing technologies in SMEs

## Summary of this study
Recently, digital transformation is getting more attention to integrate the entire product development process. To do this, Information and Communication Technologies (ICTs) are essential for multiple connections among each component. These connections can improve productivity and reduce environmental impacts such as energy and materials.

On the other hand, using open-source software is very popular nowadays. Various software is available from online communities and large IT companies. They are helping to develop smart technologies with less technical and economic pressure.

However, manufacturing Small and Medium-sized Enterprises (SMEs) still have difficulties adopting these emerging technologies. Significantly, technical and economic barriers limit their transition from traditional manufacturing to smart factories. But, to survive in the competitive market, they have to find a way to jump up using smart manufacturing technology. 

In this page, I narrowed down enabling OSS for developing an appropriate IoT edge computing system in each of 8 common and must-have functional components. In addition, I added a programming language as an extra.
<br/>

| Functional component | Cosideration | Recommendation |
| ----------- | ----------- | ----------- |
| Device management | Popularity and stable | **Linux families** Raspberry Pi OS [[Link](https://www.raspberrypi.com/software/)] |
| Communication | Standard (for interoperability) | **Wi-Fi** |
| Protocol | Standard (for interoperability) | **MQTT** [[Link](https://mqtt.org/)] <br/> **OPC UA** [[Link](https://opcfoundation.org/about/opc-technologies/opc-ua/)]] |
| Data management | On-premises (vs. cloud) | **MySQL** [[Link](https://www.mysql.com/)], **MariaDB** [[Link](https://mariadb.org/)] |
| Analytics | Event-driven (vs. big data) | [Image processing] <br/> **OpenCV** [[Link](https://opencv.org/)] <br/> [Complex Event Processing (CEP)] <br/> **Node-RED** [[Link](https://nodered.org/)] |
| Visualization | Interactive and lightweight | **Node-RED** [[Link](https://nodered.org/)] |
| Scalability | Dozens of devices (vs. tens of hundred) | Any idea? |
| Security | Private network (vs. public) | Any idea? |
| Programming language | Popularity and simple-to-learn | **Python** Most popular one! [[Link](https://www.python.org/)] |


## Related publication
1. Kim, H., 2022. Open-source software for developing appropriate smart manufacturing technology in small and medium-sized enterprises (SMEs). Journal of Appropriate Technology, 8(3), pp.109-116. [[Link](https://doi.org/10.37675/jat.2022.00206)]
---
## Reference
References of this study are listed in below.  

### Journal paper
- Kim, H., Lee, H. and Ahn, S.H., 2022. Systematic deep transfer learning method based on a small image dataset for spaghetti-shape defect monitoring of fused deposition modeling. Journal of Manufacturing Systems, 65, pp.439-451. [[Link](https://doi.org/10.1016/j.jmsy.2022.10.009)]  

- Waters, M., Waszczuk, P., Ayre, R., Dreze, A., McGlinchey, D., Alkali, B. and Morison, G., 2022. Open Source IIoT Solution for Gas Waste Monitoring in Smart Factory. Sensors, 22(8), p.2972. [[Link](https://doi.org/10.3390/s22082972)]  

- A Novel Rule-based MPS model for SME Manufacturing Factory in Korea (2019) [[Link](https://doi.org/10.1016/j.procs.2019.08.103)]  

- Establishment of an IoT-based smart factory and data analysis model for the quality management of SMEs die-casting companies in Korea (2019) [[Link](https://doi.org/10.1177/1550147719879378)]  

- Using open-source microcontrollers to enable digital twin communication for smart manufacturing (2019) [[Link](https://doi.org/10.1016/j.promfg.2020.01.212)]  

- Digital Manufacturing on a Shoestring Low Cost Digital Solutions for SMEs (2020) [[Link](https://doi.org/10.1007/978-3-030-27477-1_4)]  

- Identification of critical success factors, risks and opportunities of Industry 4.0 in SMEs (2020) [[Link](https://doi.org/10.1080/00207543.2019.1636323)]  

- Shop-Floor Service Connector - a message-oriented Middleware Focused on the Usability and Infrastructure Requirements of SMEs Developing Smart Services (2020) [[Link](https://doi.org/10.1109/ICKII50300.2020.9318831)]  

- Towards a data science platform for improving SME collaboration through Industry 4.0 technologies (2020) [[Link](https://doi.org/10.1016/j.techfore.2021.121242)]  

- A Study on Design of Real-time Big Data Collection and Analysis System based on OPC-UA for Smart Manufacturing of Machine Working (2021) [[Link](https://doi.org/10.7236/IJIBC.2021.13.4.121)]  

- Low-Cost Precision Monitoring System of Machine Tools for SMEs (2021) [[Link](https://doi.org/10.1016/j.procir.2021.01.098)]  

- Machine Tool Transition from Industry 3.0 to 4.0 A Comparison between Old Machine Retrofitting and the Purchase of New Machines from a Triple Bottom Line Perspective (2021) [[Link](https://doi.org/10.3390/su131810441)]  

- Retrofitting a Process Plant in an Industry 4.0 Perspective for Improving Safety and Maintenance Performances (2021) [[Link](https://doi.org/10.3390/su13020646)]  

- Appropriate Smart Factory for SMEs Concept, Application and Perspective (2021) [[Link](https://doi.org/10.1007/s12541-020-00445-2)]  

- Trends for Low-Cost and Open-Source IoT Solutions Development for Industry 4.0 (2021) [[Link](https://doi.org/10.1016/j.promfg.2021.10.042)]  

- Appropriate Smart Factory Demonstration of Applicability to Industrial Safety (2021) [[Link](https://doi.org/10.37675/jat.2021.7.2.196)]  

- Kim, H., Jung, W.K., Choi, I.G. and Ahn, S.H., 2019. A low-cost vision-based monitoring of computer numerical control (CNC) machine tools for small and medium-sized enterprises (SMEs). Sensors, 19(20), p.4506. [[Link](https://doi.org/10.3390/s19204506)]  

- Contreras Pérez, J.D., Cano Buitrón, R.E. and García Melo, J.I., 2018, November. Methodology for the retrofitting of manufacturing resources for migration of SME towards industry 4.0. In International Conference on Applied Informatics (pp. 337-351). Springer, Cham. [[Link](https://doi.org/10.1007/978-3-030-01535-0_25)]  

- Nsiah, K.A., Schappacher, M., Rathfelder, C., Sikora, A. and Groza, V., 2018, May. An open-source toolkit for retrofit industry 4.0 sensing and monitoring applications. In 2018 IEEE International Instrumentation and Measurement Technology Conference (I2MTC) (pp. 1-6). IEEE. [[Link](https://doi.org/10.1109/I2MTC.2018.8409633)]  

- Sezer, E., Romero, D., Guedea, F., Macchi, M. and Emmanouilidis, C., 2018, June. An industry 4.0-enabled low cost predictive maintenance approach for smes. In 2018 IEEE International Conference on Engineering, Technology and Innovation (ICE/ITMC) (pp. 1-8). IEEE. [[Link](https://doi.org/10.1109/ICE.2018.8436307)]  

- Illa, P.K. and Padhi, N., 2018. Practical guide to smart factory transition using IoT, big data and edge analytics. Ieee Access, 6, pp.55162-55170. [[Link](https://doi.org/10.1109/ACCESS.2018.2872799)]  

<br/>

### Public report
- OECD, 2021. The Digital Transformation of SMEs. [[Link](https://doi.org/10.1787/bdb9256a-en)]

<br/>

### White paper
(to be added...)
