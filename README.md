<br/>
<p align="center">
  <a href="https://github.com/Rajmvr24/Masters-Thesis">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">INVESTIGATION OF 5G RADIO WAVE PROPAGATION IN MACRO CELL ENVIRONMENTS
  </h3>
    <p align="center">
    Master Thesis
    <br/>
    <br/>
  </p>
</p>

## About The Project

The Aim of the project is to propose and investigate a propagation model that is suitable for 5G New Radio implementation in Macro cell environments. By analyzing the different signal quality parameters like RSRP,RSRQ,SINR, the suitable propagation model can be selected. 
The following tasks are performed in order to achieve the Aim of the research project.

•	Initially, analyze the different existing propagation models sitable for 5G New Radio and operating frequency.

•	Analyze the 5G New Radio parameters(PCI, PSS, SSS, PBCH, DMRS) and signal quality parameters.(RSRP, RSRQ, SINR, RSSI).

•	Collect  the measurements of different parameters  near the base station .

•	Import these measured values into radio planning software and predict the values.

•	Perform the comparison of measured values and predicted values for different propagation models to find best suited model in macro cell environments.

•	Calibrate the proposed model by adjusting the correction coefficient.

## Illustration of work flow chart

<p align="center">
 <a href="https://github.com/Rajmvr24/Masters-Thesis">
    <img src="images/flow%20chart.png" alt="chart" width="800" height="800">
  </a>
</p>

## Measurement Plot and Directions

<p align="center">
 <a href="https://github.com/Rajmvr24/Masters-Thesis">
    <img src="images/measurements.png" alt="measurements" width="800" height="800">
  </a>
</p>

## Measurement Graphs

<p align="center">
 <a href="https://github.com/Rajmvr24/Masters-Thesis">
    <img src="images/measurement%20graphs.png" alt="measuremmentgraph" width="800" height="800">
  </a>
</p>

## 3D Map of Kaunas

<p align="center">
 <a href="https://github.com/Rajmvr24/Masters-Thesis">
    <img src="images/map.png" alt="map" width="800" height="800">
  </a>
</p>

## 5G Transmitter Details

<p align="center">
 <a href="https://github.com/Rajmvr24/Masters-Thesis">
    <img src="images/transmitter%20details.png" alt="transmitter" width="800" height="800">
  </a>
</p>

## Aster Propagation Model Predictons

<p align="center">
 <a href="https://github.com/Rajmvr24/Masters-Thesis">
    <img src="images/aster%20propagation.png" alt="aster" width="800" height="800">
  </a>
</p>

## 3GPP 38.900 Propagation Model Predictions

<p align="center">
 <a href="https://github.com/Rajmvr24/Masters-Thesis">
    <img src="images/3gpp.png" alt="3gpp" width="800" height="800">
  </a>
</p>

## Standard Propagation Model Predictions

<p align="center">
 <a href="https://github.com/Rajmvr24/Masters-Thesis">
    <img src="images/standard%20propagation.png" alt="standard" width="800" height="800">
  </a>
</p>

## Error(P-M)

<p align="center">
 <a href="https://github.com/Rajmvr24/Masters-Thesis">
    <img src="images/error.png" alt="error" width="800" height="800">
  </a>
</p>

## Coefficient Correction

<p align="center">
 <a href="https://github.com/Rajmvr24/Masters-Thesis">
    <img src="images/coefficient%20correction.png" alt="coecor" width="800" height="800">
  </a>
</p>

## Conclusion

This research work presents the overview of investigation of 5G in a Macrocell environment. The main conclusions of all the tasks for the project experiment is presented in this chapter.
1. The 5G NR basic concept and the parameters were analyzed. The different propagation models which are suitable for 5G frequencies and other parameter were chosen and investigated deeply to understand the concept.
2. The latest 5G phone Poco M3 Pro, which is compatible with 5G services in Lithuania is used to take the real-time measurements for the 5G NR near the 5G base station that is located at Savanorių avenue 363, Kaunas. And all the 5G quality parameters (RSRP, RSRQ, SINR) are tabulated.
3. For the prediction purpose, the Kaunas city map is created in 3D format with a resolution of 1 m. The satellite map data is collected from the open street view website and the working area data are extracted from that website, by using photoshop, the extracted map data is converted into the compatible format to the Forsk Atoll. All the necessary 3D map data of Kaunas is imported into the RAN planning Atoll software. 
4. The walk test measurement data taken by the 5G phone is fed into the Atoll software to compare the measured data with predicted data. The different propagation model data is compared with the real-time measurement, the error value E is the difference between predicted and measured values. The propagation model which has a low error value is best suited for 5G NR deployment in a Macro environment.
5. By comparing the error values of different propagation models from figure (32,33,34) and table (9), Aster propagation mean error for total measured points is -7.49, which is significantly less than   the other two models. The  macro cell environment mode is used for prediction. Standard deviation (std dev) and Root mean square(RMS) values of Aster model is 10.41, 12.82 respectively is very low than 3GPP 38.900model and standard model. The Aster propagation model is identified as best suited model for 5G in Macrocell environment with low mean error -7.49, Standard deviation 10.41 and Root mean square 12.82.
6. The calibration of  parameter coefficient is done to get better efficient in the proposed model.The propogation model coefficient are optimized for macro cell environment. Depending on the environments like micro or macro these coefficients of parameter changes accordingly. The standard deviation(-0.01) denotes how dispersed the values are, higher the value  means high dispersed. The RMS value denotes how far the values are different from one another, lower the value  the measured and predicted values are close.The Correlation coefficient value is 0.75 after calibration. It denotes the how predicted values differ from measured values and range from-1 to +1.
