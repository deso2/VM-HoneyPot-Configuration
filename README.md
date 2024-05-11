# VM Configuration on Azure

<img width="700" src="https://github.com/deso2/VM-HoneyPot-Configuration/assets/168561314/82e04c77-8284-4ee8-a054-81943d7484b9">

<img width="700" src="https://github.com/deso2/VM-HoneyPot-Configuration/assets/168561314/32b2ca15-7a52-4e1a-9104-b6605cac25d2">

Begin by signing up for Microsoft Azure. Once logged in, create a Virtual Machine (VM). Click on the VM logo and select "Create" to initiate the creation of an Azure Virtual Machine. Choose a new resource group name of your choice. Next, set up a username and password for your VM. 

<img width="700" src="https://github.com/deso2/VM-HoneyPot-Configuration/assets/168561314/5e036355-56f8-4692-ab31-2c6a5ba26ceb">

Proceed to the next step, leaving the disk settings as default. Under networking, configure the network security group by clicking "Advanced." Then "Create new," in inbound rule, delete the inbound rule, adjusting settings to make the VM discoverable by others. Review the configuration and proceed with creating the VM. Proceed to create a new Log Analytics workspace using the same resource group. Review the settings and confirm the creation.

<img width="700" src="https://github.com/deso2/VM-HoneyPot-Configuration/assets/168561314/827e3b74-374b-40e8-bee8-72274e5e3643">

<img width="700" src="https://github.com/deso2/VM-HoneyPot-Configuration/assets/168561314/fd1bac98-954d-4020-8b01-67f0cc583382">

Navigate to Microsoft Defender for Cloud and access environmental settings and the left side toolbar. Enable Defender plans for servers and save the settings. In the data collection tab, select all events and save the configuration.

<img width="700" src="https://github.com/deso2/VM-HoneyPot-Configuration/assets/168561314/4f29a8d3-2ff1-42f3-a2a2-2d382b72cfbc">

Access the Log Analytics workspace within the resource group and proceed to connect the VM to the Log Analytics workspace. Set up Sentinel by creating a new instance and clicking on the created workspace to add necessary configurations.

This walkthrough provides detailed steps for setting up Microsoft Azure, creating a virtual machine, configuring security settings, setting up logging and monitoring with Log Analytics, and integrating with Microsoft Defender for Cloud and Azure Sentinel.
