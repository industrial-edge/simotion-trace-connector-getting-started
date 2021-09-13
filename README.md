# Writing good how-to or tutorial

Before you start writing, read the following materials how to write good documentation (including how-tos).

* [Google Developer style guide](https://developers.google.com/style)
* [Technical writing Courses](https://developers.google.com/tech-writing)
* [Microsoft Writing Style Guide](https://docs.microsoft.com/cs-cz/style-guide/welcome/)

Then decide: Are you writing a tutorial or a how-to guide?

[Divio](https://documentation.divio.com/) explains the difference  (Note that this applies for software documentation for application developers)

* Tutorials are lessons that take the reader by the hand through a series of steps to complete a project of some kind. They are what your project needs in order to show a beginner that they can achieve something with it. https://documentation.divio.com/tutorials/
* How-to guides take the reader through the steps required to solve a real-world problem

Each have a different writing style. Tutorials must be bullet proof (no unexpected behavior) https://documentation.divio.com/how-to-guides/

Note: Try to write the tutorials and how-tos as a standalone html page, ready to be generated using Static site generator [MkDocs](https://www.mkdocs.org/). When referencing code examples or files, use the full URL of the git repository. We want to reuse these how-tos and tutorials in Documentation website.

Don't explain concepts. [It gets in a way of action](https://documentation.divio.com/how-to-guides/#don-t-explain-concepts).  

Don't use HTML tags unless working with videos. And try to avoid using videos unless absolutely necessary. Don't upload videos to Git repository.

Bellow you can find the structure of IE tow-to/tutorial

* [Writing good how-to or tutorial](#writing-good-how-to-or-tutorial)
  * [Description](#description)
    * [Overview](#overview)
    * [General Task](#general-task)
  * [Requirements](#requirements)
    * [Prerequisites](#prerequisites)
    * [Used components](#used-components)
  * [Installation](#installation)
  * [Usage](#usage)
  * [Documentation](#documentation)
  * [Contribution](#contribution)
  * [Licence and Legal Information](#licence-and-legal-information)

## Description

### Overview

Why has been this how-to/tutorial created? What is the purpose?

### General Task

What is the general goal/task of this how-to/tutorial?

![task](docs/graphics/example_graphic.png)

## Requirements

For the Version 1.0.0 of the application SIMOTION Trace Connector the following requirements are necessary:

* The WebServer of the SIMOTION needs to be activated. This also enables automatically the used OPC XML DA protocol. 
* Open port 80 for Webserver and OPC XML DA
* SIMOTION Firmware Version V4.1 or newer 
* Industrial Edge Device with RT V1 or higher
  * Device license: 6ES7823-0EE00-4AY0
  * Device: 6ES7647-8BD31-0CW1
  
**Notice:** the app is currently not running on WinCC Comfort Panels with integrated Edge functionality

## Installation

How to install/run this application example? (i.e. how to deploy it to Industrial Edge device?) How to build this application? How to set up configurations in IE?

To keep the readme.md file as short as possible please add more detailed information in the docs folder.

* [Build application](docs/Installation.md#build-application)

## Usage

When the app is installed, how can I use it? Usually some basic UI description to prove that the app is working correctly.

## Documentation

Add links to documentation. Either on external URL or in the doc folder. Please use always link to a file not to a directory (it doesn't work with static site generator engines).

Add these links:

You can find further documentation and help in the following links

* [Industrial Edge Hub](https://iehub.eu1.edge.siemens.cloud/#/documentation)
* [Industrial Edge Forum](https://www.siemens.com/industrial-edge-forum)
* [Industrial Edge landing page](https://new.siemens.com/global/en/products/automation/topic-areas/industrial-edge/simatic-edge.html)
* [Industrial Edge GitHub page](https://github.com/industrial-edge)

## Contribution

Thank you for your interest in contributing. Anybody is free to report bugs, unclear documentation, and other problems regarding this repository in the Issues section. Everybody is free to propose any changes to this repository using Pull Requests.

## Licence and Legal Information

Please read the [Legal information](LICENSE.md).
