# CrowdShield-Smart-Wristband-Abstract

Large public gatherings such as concerts, festivals, sports events, and religious celebrations often face safety challenges because of high crowd density. In such crowded environments, incidents like medical emergencies, harassment, or sudden panic situations can occur unexpectedly. When these events happen, it becomes difficult for security personnel to quickly identify the person in distress and locate them within the crowd. Delays in response can increase the risk of injuries and create confusion among participants.

To address this issue, our project proposes a smart concert wristband that combines entertainment features with emergency safety support. The wristband functions as a concert entry band while also integrating a compact electronic system built around an ESP32‑C3 microcontroller. The device includes an SOS push button and a buzzer, allowing users to request help during an emergency quickly.

Under normal conditions, the wristband can be used for concert lighting effects and audience interaction, creating a synchronized visual experience across the crowd. However, if a user faces an emergency, pressing the SOS button immediately sends a Bluetooth Low Energy (BLE) alert signal to nearby receiver nodes installed across the event venue.

These ESP32 receiver modules continuously scan for emergency signals. When an alert is detected, the receivers measure the signal strength (RSSI) and send the data to a central monitoring system. Using this information, the system can estimate the approximate location of the user and display it on a dashboard map, enabling security teams to respond quickly, buzzer alerts to the surrounding area to help if the person has an emergency.

The system also allows group connectivity between wristbands, so that if one person in a group activates the SOS alert, nearby connected wristbands can display a visual indication in the mobile application. This helps friends or people nearby notice the emergency and provide immediate assistance even before security teams arrive.

Overall, the proposed solution provides a low‑cost, scalable, and practical safety system for large public events. By combining a concert RGB wristband with an integrated emergency alert mechanism, the system enhances both audience experience and crowd safety while reducing response time during critical situations.
