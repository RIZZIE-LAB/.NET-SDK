# Misty II .NET SDK

This repository includes tools and sample projects for working with Misty's .NET SDK.

To use the code in this repository, you need the following:

* Misty II robot
* PC (or virtual machine) running Windows 10
* Microsoft [Visual Studio](https://visualstudio.microsoft.com/vs/), with **Windows Universal Platform** workload and **Windows 10 SDK libraries** (build 17763) installed

For more information about setting up your environment to work with Misty's .NET SDK, see the [.NET SDK overview](https://docs.mistyrobotics.com/misty-ii/dotnet-sdk/overview/) in the Misty Robotics developer documentation.

## Contents

This repository includes the following directories:

### C#

Libraries, sample code, and runnable .NET skills for learning about Misty's .NET SDK. Includes:

  * **Libraries/SkillTools** - Library with helper functionality for HTTP requests, simple data stores, and asset management.
  * **Sample Projects** - Sample code and solutions with runnable .NET skills for experimenting with Misty and learning about the .NET SDK. Includes:
    * **AssetFunSkill** - Demonstrates how to automatically install assets if they do not already exist on Misty.
    * **CognitiveServicesExample** - Demonstrates how to use Microsoft's Cognitive Services in a C# skill.
    * **IntroSkills** - Code for the [`IntroSkillsTask` walkthrough](https://docs.mistyrobotics.com/misty-ii/dotnet-sdk/sample-project/) in Misty's developer documentation. (This is a great place to start if you're new to Misty's .NET SDK.)
    * **MoveArmsAndHeadSkill** - This skill brings Misty to life with randomized head and arm movements.
    * **Navigation** - Code for a **drive and dock** skill that has Misty navigate a path and return to her charger. Includes a `SharedTypes` folder with classes and functionality that can be shared across skills.
    * **TextToSpeechSkill** - Demonstrates how to use text-to-speech and custom user events.
    * **TouchSensorSkill** - Misty reacts when you touch her bump or capacitive touch sensors. Includes several examples of registering events and processing event data.
    * **UnitTestExampleSkill** - Basic unit tests with Misty's .NET SDK.
    * **WanderSkill** - Misty roams an area and attempts automatic obstacle avoidance by detecting obstacles with her bump and time-of-flight sensors. Includes several examples of registering events and validating event data.

### Tools

A simple .html page for sending a POST request to the endpoint for Misty's `ReloadSkills` command. The `ReloadSkills` command forces Misty to load all of her installed skills into the skills system.

---

**WARRANTY DISCLAIMER.**

* General. TO THE MAXIMUM EXTENT PERMITTED BY APPLICABLE LAW, MISTY ROBOTICS PROVIDES THIS SAMPLE SOFTWARE “AS-IS” AND DISCLAIMS ALL WARRANTIES AND CONDITIONS, WHETHER EXPRESS, IMPLIED, OR STATUTORY, INCLUDING THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, TITLE, QUIET ENJOYMENT, ACCURACY, AND NON-INFRINGEMENT OF THIRD-PARTY RIGHTS. MISTY ROBOTICS DOES NOT GUARANTEE ANY SPECIFIC RESULTS FROM THE USE OF THIS SAMPLE SOFTWARE. MISTY ROBOTICS MAKES NO WARRANTY THAT THIS SAMPLE SOFTWARE WILL BE UNINTERRUPTED, FREE OF VIRUSES OR OTHER HARMFUL CODE, TIMELY, SECURE, OR ERROR-FREE.
* Use at Your Own Risk. YOU USE THIS SAMPLE SOFTWARE AND THE PRODUCT AT YOUR OWN DISCRETION AND RISK. YOU WILL BE SOLELY RESPONSIBLE FOR (AND MISTY ROBOTICS DISCLAIMS) ANY AND ALL LOSS, LIABILITY, OR DAMAGES, INCLUDING TO ANY HOME, PERSONAL ITEMS, PRODUCT, OTHER PERIPHERALS CONNECTED TO THE PRODUCT, COMPUTER, AND MOBILE DEVICE, RESULTING FROM YOUR USE OF THIS SAMPLE SOFTWARE OR PRODUCT.

Please refer to the Misty Robotics End User License Agreement for further information and full details: https://www.mistyrobotics.com/legal/end-user-license-agreement/

---

*Copyright 2020 Misty Robotics*<br>
*Licensed under the Apache License, Version 2.0*<br>
*http://www.apache.org/licenses/LICENSE-2.0*