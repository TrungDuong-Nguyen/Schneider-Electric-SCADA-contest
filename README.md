<img align="left" width=350 height=150 src="https://github.com/TrungDuong-Nguyen/SchneiderElectric_SCADAContest/blob/main/Schneider-Electric-Logo.png"> <img align="right" width=150 height=150 src="https://github.com/TrungDuong-Nguyen/SchneiderElectric_SCADAContest/blob/main/UnityPro-Logo.jpg">

<br>
<br>
<br>
<br>
<br>
<br>

## About

The Supervisory Control And Data Acquisition (SCADA) system provides the operators with real-time monitoring and control of technical facilities in the plants. This system is present in diverse industry areas such as electrical power generation, water treatment and distribution, chemical processing, oil filtering, as well as in many other manufacturing lines in factories.

Our project, **Design and simulate a SCADA system for wine production line integrated with power supply**, is realized within the technical contest "_The best application with UnityPro & Vijeo Citect SCADA_" launched by [**Schneider Electric Vietnam**](https://www.se.com/vn/en/) in June 2011.

Specifically, we design and simulate a SCADA system composed by two modules (subsystems): a wine production line, and a power supply. To understand how the system works, please read the [working principle](/Working%20Principle%20of%20the%20System.pdf).

<br>


## Outlines
In the wine production line, the raw grapes are processed alternately through multiples stages before being bottled. Besides, a power supply system is built for the wine production line. This power system comprises two transformers and a series of circuit breakers to transmit electricity from the high-voltage electrical grid. In addition, to maintain the power supply in case of an incident on the grid, two generators are connected to the system.

To simulate the system, we use two personal computers. The first one plays the role of the MTU (Master Terminal Unit), which sends out commands to the RTU (Remote Terminal Unit), acquires data, and displays in real-time the data on a graphical interface called HMI (Human Machine Interface). The second computer, which simulates a Premium PLC, is considered the RTU. Using the software Vijeo Citect, we developed the HMI[^1] and configured the communication within the SCADA system. Then, by utilizing the software Unity Pro, we program the PLC to perform the predetermined operations. Finally, we connect these two computers and simulate with success the functioning of the whole system.

[^1]: Some graphic objects we used when developping the system interfacte are provided by [Symbol Factory](https://www.softwaretoolbox.com/store/item_pages/itempage_419.asp), a library of professionally built vector objects supporting the design of HMI applications.
