# Experimental Framework for Real-Time Indian Sign Language Recognition Using Advanced Machine Learning Algorithms for Community Development  

## Overview  
This project aims to develop a **real-time sign language interpreter** using:  
- **Flex and accelerometer sensors** integrated with an **ESP32 board**.  
- **Machine learning algorithms** to classify gestures and translate them into Readable outputs.
- Setting up a local server and rendering a webpage to enable real time communication.   
- A solution enabling seamless communication for hearing and speech-impaired individuals.  

## Features  
- **Real-time gesture recognition** using flex and accelerometer sensors.  
- **Compact and portable** design.  
- Operates **offline**, ensuring accessibility anywhere.  
- **Cost-effective** solution for sign language interpretation.  
- **Customizable** for different sign languages.  
- **Accurate recognition** in diverse environmental conditions.  

## System Components  

### Hardware  
- **ESP32 microcontroller.**  
- **Flex sensors.**  
- **Accelerometer sensor.** (e.g., MPU6050)  
- **Power supply.**  
- **Hand glove.** for mounting sensors
- **Resistors.**

![Hardware Setup](https://github.com/Rishmitha789/Sign-Language-Interpreter-for-The-Hearing-Speaking-Impaired/blob/main/Hardware%20Setup.jpeg?raw=true)


### Software  
- **Google Collab** for data analysis and machine learning using python.
- Libraries:  
  - `numpy`  
  - `pandas`  
  - `matplotlib`  
  - `scikit-learn`
  - `json`
  - `time`
- Gesture classification using machine learning algorithms such as:  
  - Decision Tree  
  - Random Forest
  - Logistic Regression
  - SVM
  - KNN
  - FNN
  - Transformer model
  - LSTM
  - XGBoost
- **Arduino IDE** for ESP32 programming
- **Tera term** for Data Logging
- **Visual Studio** for server setup and webpage rendering.

## References
- 1.	Z. R. Saeed, Z. B. Zainol, B. B. Zaidan, and A. H. Alamoodi, "A Systematic Review on Systems-Based Sensory Gloves for Sign Language Pattern Recognition: An Update From 2017 to 2022," IEEE Access, vol. 10, pp. 123358–123377, 2022, doi: 10.1109/ACCESS.2022.3219430.

- 2.	N. Bahia and R. Rani, "Multi-level Taxonomy Review for Sign Language Recognition: Emphasis on Indian Sign Language," ACM Transactions on Asian and Low-Resource Language Information Processing, vol. 22, 2022, doi: 10.1145/3530259.

- 3.	K. Wang and G. Zhao, "Gesture Recognition Based on Flexible Data Glove Using Deep Learning Algorithms," 2023 4th International Seminar on Artificial Intelligence, Networking and Information Technology (AINIT), Nanjing, China, 2023, pp. 113–117, doi: 10.1109/AINIT59027.2023.10212923.

- 4.	K. T. Lee, P. S. Chee, E. H. Lim, and C. C. Lim, "Artificial Intelligence (AI)-driven Smart Glove for Object Recognition Application," Materials Today: Proceedings, vol. 64, pp. 1563–1568, 2022, doi: 10.1016/j.matpr.2021.12.473.

- 5.	P. D. Rosero-Montalvo et al., "Sign Language Recognition Based on Intelligent Glove Using Machine Learning Techniques," 2018 IEEE Third Ecuador Technical Chapters Meeting (ETCM), Cuenca, Ecuador, 2018, pp. 1–5, doi: 10.1109/ETCM.2018.8580268.

- 6.	D. Alosail, H. Aldolah, L. Alabdulwahab, A. Bashar, and M. Khan, "Smart Glove for Bi-lingual Sign Language Recognition Using Machine Learning," 2023 International Conference on Intelligent Data Communication Technologies and Internet of Things (IDCIoT), Bengaluru, India, 2023, pp. 409–415, doi: 10.1109/IDCIoT56793.2023.10053470.

- 7.	Ajay S, A. Potluri, S. M. George, G. R, and A. S, "Indian Sign Language Recognition Using Random Forest Classifier," 2021 IEEE International Conference on Electronics, Computing and Communication Technologies (CONECCT), Bangalore, India, 2021, pp. 1–6, doi: 10.1109/CONECCT52877.2021.9622672.

- 8.	J. Maitre, C. Rendu, K. Bouchard, B. Bouchard, and S. Gaboury, "Basic Daily Activity Recognition with a Data Glove," Procedia Computer Science, vol. 151, pp. 108–115, 2019, doi: 10.1016/j.procs.2019.04.018.

- 9.	Y. Zheng, "A Noble Classification Framework for Data Glove Classification of a Large Number of Hand Movements," Journal of Electrical and Computer Engineering, vol. 2021, pp. 1–11, doi: 10.1155/2021/9472053.

- 10.	J. Abougarair and W. A. Arebi, "Electrical & Electronics Engineering, University of Tripoli, Libya," MedCrave Online Journal of Robotics & Artificial Intelligence Technology, vol. 8, no. 2, pp. 1–5, 2022.

- 11.	Muralikrishna. K. S., N. Prakasan, Haritha T. K., A. J. George, and R. T. Paul, "Smart Glove for Malayalam Sign Language Recognition and Audio Output," International Journal of Advanced Research and Innovative Ideas in Education, vol. 10, no. 1, pp. 1–8, 2022.

- 12.	S. Y. Heera, M. K. Murthy, V. S. Sravanti, and S. Salvi, "Talking Hands — An Indian Sign Language to Speech Translating Gloves," 2017 International Conference on Innovative Mechanisms for Industry Applications (ICIMIA), Bengaluru, India, 2017, pp. 746–751, doi: 10.1109/ICIMIA.2017.7975564.

- 13.	Baktash, S. Mohammed, and H. Farooq, "Multi-Sign Language Glove-Based Hand Talking System," IOP Conference Series: Materials Science and Engineering, vol. 1105, pp. 012078, 2021, doi: 10.1088/1757-899X/1105/1/012078.

- 14.	M. Ganganna, "Smart Glove for the Disabled: A Survey," ResearchGate, 2021.

- 15.	M. A. Ahmed, B. B. Zaidan, A. A. Zaidan, M. M. Salih, Z. T. Al-Qaysi, and A. H. Alamoodi, "Based on Wearable Sensory Device in 3D-Printed Humanoid: A New Real-Time Sign Language Recognition System," Measurement, vol. 168, pp. 108431, 2021, doi: 10.1016/j.measurement.2020.108431.

- 16.	L. Fan et al., "Smart-Data-Glove-Based Gesture Recognition for Amphibious Communication," Micromachines, vol. 14, no. 11, pp. 2050, 2023, doi: 10.3390/mi14112050.

- 17.	P. Achenbach et al., "Give Me a Sign: Using Data Gloves for Static Hand-Shape Recognition," Sensors, vol. 23, no. 24, pp. 9847, 2023, doi: 10.3390/s23249847.

- 18.	R. Gupta, A. Bhatnagar, and G. Singh, "A Weighted Deep Ensemble for Indian Sign Language Recognition," IETE Journal of Research, vol. 70, pp. 1–15, 2023, doi: 10.1080/03772063.2023.2175057.

- 19.	M. Buttar et al., "Deep Learning in Sign Language Recognition: A Hybrid Approach for the Recognition of Static and Dynamic Signs," Mathematics, vol. 11, pp. 3729, 2023, doi: 10.3390/math11173729.

- 20.	P. Bhatia and A. Wadhawan, "Deep Learning-Based Sign Language Recognition System for Static Signs," Neural Computing and Applications, vol. 33, pp. 1–15, 2021, doi: 10.1007/s00521-019-04691-y.

- 21.	R. Tripuraribhatla et al., "A Depth-Based Indian Sign Language Recognition Using Microsoft Kinect," Sādhanā, vol. 45, pp. 1–15, 2020, doi: 10.1007/s12046-019-1250-6.

- 22.	M. Amin et al., "Alphabetical Gesture Recognition of American Sign Language Using E-Voice Smart Glove," 2020 International Multi-Topic Conference (INMIC), Lahore, Pakistan, 2020, pp. 1–6, doi: 10.1109/INMIC50486.2020.9318185.

- 23.	S. Sharma et al., "Trbaggboost: An Ensemble-Based Transfer Learning Method Applied to Indian Sign Language Recognition," Journal of Ambient Intelligence and Humanized Computing, vol. 13, pp. 1–15, 2022, doi: 10.1007/s12652-020-01979-z.

- 24.	A. Filipowska et al., "Machine Learning-Based Gesture Recognition Glove: Design and Implementation," Sensors, vol. 24, no. 18, pp. 6157, 2024, doi: 10.3390/s24186157.

- 25.	R. Su et al., "Random Forest-Based Recognition of Isolated Sign Language Subwords Using Data from Accelerometers and Surface Electromyographic Sensors," Sensors, vol. 16, no. 1, pp. 100, 2016, doi: 10.3390/s16010100.

- 26.	R. Liang and M. Ouhyoung, "A Real-Time Continuous Gesture Recognition System for Sign Language," Proceedings of the 1998 International Conference on Automatic Face and Gesture Recognition, pp. 558–567, 1998, doi: 10.1109/AFGR.1998.671007.

- 27.	F. Pezzuoli et al., "Recognition and Classification of Dynamic Hand Gestures by a Wearable Data-Glove," SN Computer Science, vol. 2, pp. 1–15, 2021, doi: 10.1007/s42979-020-00396-5.

- 28.	L. J. Kau et al., "A Real-Time Portable Sign Language Translation System," 2015 IEEE Midwest Symposium on Circuits and Systems (MWSCAS), pp. 1–4, 2015, doi: 10.1109/MWSCAS.2015.7282137.

- 29.	W. Lu et al., "Artificial Intelligence–Enabled Gesture‐Language‐Recognition Feedback System Using Strain‐Sensor‐Arrays‐Based Smart Glove," Advanced Intelligent Systems, vol. 5, pp. 1–15, 2023, doi: 10.1002/aisy.202200453.

- 30.	C. Lu et al., "Data Glove with Bending Sensor and Inertial Sensor Based on Weighted DTW Fusion for Sign Language Recognition," Electronics, vol. 12, no. 3, pp. 613, 2023, doi: 10.3390/electronics12030613.


## Acknowledgments  
Special thanks to:  
- The open-source community for providing tools and libraries that made this project possible.  
- Volunteers who contributed to the data collection.  
