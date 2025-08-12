# About This Repository

Sample PLC code on how to use FB_ScopeServerControl to start and stop a recording from the PLC (Requries TF3300).
Data is then saved as a .svdx file. 

With the .svdx file, it can be opened up and viewed inside of scope view.

In this example, there is also an example function block on how to call the scope export tool from the PLC, and covert the recorded data in the .svdx file into a .csv file. 

A very capable and robust alternative to this is to use the [TwinCAT Analytics Logger](https://infosys.beckhoff.com/content/1033/tf3500_tc3_analytics_logger/7666756875.html?id=3699947303829975394).

Scope recordings (.svdx), or Analytic logger files(.tas), can be converted to CSV with the use of the [TwinCAT 3 Scope Export Tool](https://infosys.beckhoff.com/english.php?content=../content/1033/te13xx_tc3_scopeview/1022949131.html&id=1090492099338523905).

This sample is created by [Beckhoff Automation LLC.](https://www.beckhoff.com/en-us/), and is provided as-is under the Zero-Clause BSD license.

# How to get support

Should you have any questions regarding the provided sample code, please contact your local Beckhoff support team. Contact information can be found on the official Beckhoff website at https://www.beckhoff.com/en-us/support/.

# Further Information
https://infosys.beckhoff.com/content/1033/tcplclib_tc2_utilities/35059339.html?id=146323714276683940
https://infosys.beckhoff.com/content/1033/te13xx_tc3_scopeview/1022949131.html?id=1090492099338523905

## Requirements

The following components must be installed to run sample code:

- [TE1000 TwinCAT 3 Engineering](https://www.beckhoff.com/en-en/products/automation/twincat/te1xxx-twincat-3-engineering/te1000.html) version 3.1.4024.0 or higher
TF3300 on the target system
