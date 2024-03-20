# Wind Farm Digital Twin with Azure and Unity

This repository holds the code for a **Wind Farm Digital Twin** project built with Unity, Azure Digital Twins, Azure IoT Hub, and SignalR. 

![Mixed Reality Test inside Unity engine](MR-ADT.gif)

The project features a **mixed reality application** designed to run on Microsoft HoloLens.  

**What it does:**

* Users can explore a virtual wind farm containing multiple turbines.
* Each turbine reflects the **real-time status** of its corresponding real-world counterpart.
* Users can inspect and focus on individual turbines to reveal information such as **temperature, humidity, and other relevant data**.
* If a critical event is detected, like excessive ice buildup, users can trigger an action by clicking a button. This action sends a **command** to the real-world turbine through the Azure services.

**Implementation Details:**

* Leverages assets sourced from Microsoft tutorials for a streamlined development process.

**Please note:** This repository focuses on the technical aspects of the wind farm digital twin, it is for learning purposes only and should no be considered as a production scenario.

The app requires a signalR connection and test code to push sample Turbine data to ADT, refer to "mixed reality digital twins in unity" tutorial in Microsoft learn for details.

**Future considerations:**

* Adding easy steps for testing using sample data.
* Expansion of user interaction capabilities within the mixed reality environment.

**This project demonstrates the power of combining Unity with Azure Digital Twin services to create a real-time, interactive digital twin solution for industrial applications.**

Digital Twins, powered by the Unity engine, offer dynamic 3D simulations that improve understanding and enhance predictive analytical models. By enabling two-way data flow between the digital twin and real-world sensors or processes, organizations gain accurate insights. These simulations empower decision-makers to visualize scenarios, optimize operations, and respond swiftly to changing conditions.

Users can explore a virtual wind farm containing multiple turbines. Each turbine reflects the **real-time status** of its corresponding real-world counterpart.Users can inspect and focus on individual turbines to reveal information such as **temperature, humidity, and other relevant data**.If a critical event is detected, like excessive ice buildup, users can trigger an action by clicking a button. This action sends a **command** to the real-world turbine through the Azure services.


