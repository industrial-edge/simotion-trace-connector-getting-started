# Creating tracejobs in SIMOTION Trace connector

How to configure and execute tracejobs via web-based SIMOTION Trace connector application.

* [Tracejobs configuration and execution](#trace-connector-tutorial)
  * [Description](#description)
    * [Overview](#overview)
    * [General Task](#general-task)
  * [Requirements](#requirements)
  * [Usage](#usage)
  * [How to create your first trace](#how-to-create-your-first-trace)
  * [Get application and more information](#get-application-and-more-information)
  * [Contribution](#contribution)
  * [Licence and Legal Information](#licence-and-legal-information)

## Description

### Overview

SIMOTION Trace connector is a web-based application running on SIEMENS Industrial Edge 


### General Task

This tutorial was created to help user to configure and execute tracejobs via the SIMOTION
webserver interface and download the recorded traced data to the Edge device.


![task](docs/graphics/SIMOTION_Trace_Connector_App_Diagram_595x277_en.jpg)

## Requirements

For the SIMOTION Trace connector application the following requirements are necessary:

* The WebServer of the SIMOTION needs to be activated. This also enables automatically the used OPC XML DA protocol. 
* Open port 80 for Webserver and OPC XML DA
* SIMOTION Firmware Version V4.1 or newer 
* Industrial Edge Device with RT V1 or higher
  * Device license: 6ES7823-0EE00-4AY0
  * Device: 6ES7647-8BD31-0CW1
  
**Notice:** the app is currently not running on WinCC Comfort Panels with integrated Edge functionality

## Usage

When the app is installed, it offers the following functionality:

* Definition of tracejobs (variables, trace duration, trigger condition)
* Automatic execution and scheduling of the tracejobs
* Remanet storage of the trace results
* Visualization of the trace data
* Publishing of the trace results via MQTT data bus
* External triggering and status monitoring of the tracejobs via MQTT

## How to create your first trace
Following instructions describe the main steps how to successfully create your first trace:
1. Connect  new SIMOTION, using correct IP address and a SIMOTION name
![connect SIMOTION](docs/graphics/connect-new-simotion.png)
  
2. Preselect variables that will later be used to configure the tracejobs
![preselect variables](docs/graphics/preselect-variables.png)
  
3. Configure and schedule tracejob
![configure tracejob](docs/graphics/create-tracejob.png)
  
4. Check information about executed tracejobs
![logbook](docs/graphics/logged-tracejobs.png)

## Documentation

Application functionality and user scenarios are detailed in user documentation.

[User documentation]()


You can also find further documentation and help in the following links:

* [Industrial Edge Hub](https://iehub.eu1.edge.siemens.cloud/#/documentation)
* [Industrial Edge Forum](https://www.siemens.com/industrial-edge-forum)
* [Industrial Edge landing page](https://new.siemens.com/global/en/products/automation/topic-areas/industrial-edge/simatic-edge.html)
* [Industrial Edge GitHub page](https://github.com/industrial-edge)

## Get application and more information

To get the application and receive additional information about the application, please follow the link to Siemens Industry Online Support  provided below.

[comment]: <> ([Industrial Edge: SIMOTION Trace Connector]&#40;https://support.industry.siemens.com/cs/document/109784249/industrial-edge-simotion-trace-connector?dti=0&lc=en-US&#41;)

## Contribution

Thank you for your interest in contributing. Anybody is free to report bugs, unclear documentation, and other problems regarding this repository in the Issues section. Everybody is free to propose any changes to this repository using Pull Requests.

## Licence and Legal Information

Please read the [Legal information](LICENSE.md).
