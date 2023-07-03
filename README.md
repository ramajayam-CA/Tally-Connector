# Tally-Excel- PowerBI- Power Query ODBC Connector

This Tool will help to import Tally Data (Master Data and Transactional Data) to excel /Power BI/ Power Query.

# Steps in Connecting the TDL In Tally and Import in Excel
**Step 1**
Download the File Named Connection.tcp and paste in any folder in your PC

**Step 2** **Connecting TDL**
Copy the Folder path and Load Any company in Tally and Navigate to F1 Help >> TDL's & Addons
or Press Ctl + Alt + T in Gateway of Tally Menu

![image](https://github.com/ramajayam-CA/Tally-Connector/assets/12751693/6ccaaf4b-13a6-4dad-9924-75402d64976e)

Then Press F4 and Paste the path and select the Connection.tcp File

![image](https://github.com/ramajayam-CA/Tally-Connector/assets/12751693/39f65fa3-8369-4611-82a9-2b799a367f18)

**Step 3** **Enabling ODBC in Tally**

Navigate to F1 Help >> Settings >> Connectivity and Press Enter

![image](https://github.com/ramajayam-CA/Tally-Connector/assets/12751693/3002cd7d-c011-416a-96de-0141e26ccb0d)


Then Set the Following Options

Tally prime act as : **Both**

Enable ODBC  : **Yes**

Port : 9000 or any other port of your choice

![image](https://github.com/ramajayam-CA/Tally-Connector/assets/12751693/512921e5-1acd-467b-867f-7e1818cf2dfe)


# How to Connect to  Excel through Microsoft Query


**Step 4** 
  **Running Tally in Administrator Mode**

  - After connecting the TDL file, Make sure You have Completed Step 1 to 3 as above  Enabling ODBC **RUN TALLY IN ADMINISTRATOR MODE IN WINDOWS**
  - Then Open Excel and Navigate to Data >> Get Data >> Other Sources >> Microsoft Query >> Then Click on **TALLYODBC_9000** press **OK** in the Choose Data Source
    If you have any error in this step then please go through Steps 1 to 3 properly

![image](https://github.com/ramajayam-CA/Tally-Connector/assets/12751693/c44ffadb-1380-4ab1-af32-041671d0fb75)


![image](https://github.com/ramajayam-CA/Tally-Connector/assets/12751693/1a3de0f6-4156-4cc1-8722-ec969b1807b1)

    
**Step 5** 

**Selecting the Table in the tally database**

**The following tables** one by one 

**1. A_Sirc_Leder_Detailed_7_1 - Master Data**
**2. A_Sirc_Vourcher7_1        - Transaction Data**


After Selecting press the > button to load all the fields or the selected field 
Then Click **Next** 3 times And finally Click Finish so that the data loaded in Excel 


# Tdl Documentation - Community Version 7.1 (For ICAI Members)


Tally Definition Language (TDL) is the development language of Tally Products. TDL is developed to provide the user with the flexibility and power to extend the default capabilities of Tally, and integrate them with the external applications. TDL provides a development platform for the user. The entire user interface of Tally.ERP 9 is built using TDL. TDL as a language, provides capabilities for Rapid Development, Rendering, Data Management, and Integration.

**TDL Can Help Chartered Accountants in the following Ways**

1. Ability to generate Custom reports from Tally 

2. Real-Time integration with Excel / PowerBi / Tableau with the ODBC Access

3. Reduce the time to prepare Fianancial Statements from Tally.

4. Identify 269SS and 269T Transaction in Tally

5. Complete GST Audit in less than 30 Minutes from Tally.

6. Ledger Scrutiny With Advanced filters in Tally

7. Do ageing analysis from a partly Bill reference enabled enviornment.

8. Get All Transaction and Ledger Data in Excel (Even a Very Large Data) in few clicks

9. Get Critical Data Analysis for Tax audit Report

10. Analyse the Utilusation of Funds in a business enviornment.

11. There are many further Benifits being explored by the Author


# Fields Present in the Ledger Table

![image](https://github.com/ramajayam-CA/Tally-Connector/assets/12751693/993555b3-d60d-430e-8dee-ed1ab10a7263)


# Fields Present in the Transaction Table.

![image](https://github.com/ramajayam-CA/Tally-Connector/assets/12751693/536a3c9b-f271-4907-820c-50cee2853415)



# How to Connect to PowerBI


![image](https://github.com/ramajayam-CA/Tally-Connector/assets/12751693/a919eddb-8cc4-4fd7-9811-579bfc8ffa00)

