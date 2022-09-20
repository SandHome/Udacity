<h3 align="center">Power usage data analysis</h3>
<p align="left">
    This is project about power usage data analysis. the data is real data of a Tranformer Area with 115 Customer. The enegry data is measured by smart electronic meters (Meter). The data from meter is collected by a Terminal via PLC (Power Line Control Technology) one time per day include:
    <br>
    - Voltage U(V),
    <br>
    - Current I(A),
    <br>
    - Forward Active Energy A+(KWh)
    <br>
    - Forward ReActive Energy R+(KWh)
    <br>
    - Reverse Active Energy A-(KWh)
    <br>
    - Reverse ReActive Energy R-(KWh)
    <br>
    <br>
    With multi tariff meter it have more data of each tariff :
    <br>
    - Forward Active Energy tariff 1 A1+(KWh)
    <br>
    - Forward Active Energy tariff 2 A2+(KWh)
    <br>
    - Forward Active Energy tariff 3 A3+(KWh)
    <br>
    - Forward ReActive Energy tariff 1 R1+(Kvarh)
    <br>
    - Forward ReActive Energy tariff 2 R2+(Kvarh)
    <br>
    - Forward ReActive Energy tariff 3 R3+(Kvarh)
    <br>
    - Reverse Active Energy tariff 1 A1-(KWh)
    <br>
    - Reverse Active Energy tariff 2 A2-(KWh)
    <br>
    - Reverse Active Energy tariff 3 A3-(KWh)
    <br>
    - Reverse ReActive Energy tariff 1 R1-(Kvarh)
    <br>
    - Reverse ReActive Energy tariff 2 R2-(Kvarh)
    <br>
    - Reverse ReActive Energy tariff 3 R3-(Kvarh)
    <br>
    <br>
    With this project we will know how about the Power data will be use in Power Company. It will clear how to analyze and evaluate the accuracy of data, detect electrical fraud, detect abnormal data if any... !
</p>

## Installation
**Reading an excel file using Python**
- pip install xlrd

## File Descriptions
**Data Folder**
- Current Data
- Voltage Data
- Forward Energy
- Reverse Energy

**CRISP_DM**
- Tools Folder
- Data Analysis file

## Licensing, Authors
- This project is public that can be used by any one have the <a href="https://github.com/SandHome/Writing-a-Data-Scientist-Blog-Post">LINK</a> of this project
- Authors : Vũ. Phạm Thế (MR)

## References
- To more detail about <a href="https://en.wikipedia.org/wiki/Smart_meter">SMART METER</a>
- To more detail about <a href="https://en.wikipedia.org/wiki/Automatic_meter_reading">AMI SYSTEM</a>
- To more detail about <a href="https://www.gartner.com/it-glossary/advanced-metering-infrastructure-ami">Advanced Metering Infrastructure (AMI)</a>
- To understanding about <a href="https://en.wikipedia.org/wiki/Smart_meter#Advanced_metering_infrastructure">Advanced Metering Infrastructure (AMI)</a>
- To more detail about <a href="https://www.ferc.gov/CalendarFiles/20070423091846-EPRI%20-%20Advanced%20Metering.pdf">The Components of Advanced Metering Infrastructure (AMI)</a>
- To more detail about <a href="https://www.smartgrid.gov/files/NIST_SG_Interop_Report_Postcommentperiod_version_200808.pdf">What are the Benefits of AMI?</a>