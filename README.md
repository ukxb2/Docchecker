# Docchecker
The software will enable the user to check if there are any errors in the review document before uploading it to the database
Table of Contents
Table of Contents
1.0	PURPOSE	3
2.0	SCOPE	3
3.0	ASSOCIATED DOCUMENTS	3
4.0	DESCRIPTION OF SYSTEM/SYSTEM INTENDED USE	3
5.0	TOOL VERSION	3
6.0	INSTRUCTIONS FOR INSTALLATION	4
7.0	INSTRUCTIONS FOR USE	4
8.0	SUPPORT PLAN	4
9.0	TRAINING MATERIAL	4
10.0	FILE LISTING	4
APPENDIX A– DEVELOPER INSTRUCTIONS	5


 
1.0	PURPOSE
The purpose of this document is to provide detailed instructions and information regarding the proper use of the Doc Checker Tool. 
2.0	SCOPE
The information in this document covers the steps to be taken for proper operation and preparation for the Doc Checker Tool. Doc Checker Tool is used for any document review where the document contains references to other TCE documents. 
Instructions necessary to perform the Doc Checker Tool, as well as the steps needed for the setting up of the environment is discussed here
3.0	ASSOCIATED DOCUMENTS

60086597- Doc Checker Electronic Records/Electronic Signatures Compliance
60086597- Doc Checker Level of Concern Assessment.
4.0	DESCRIPTION OF SYSTEM/SYSTEM INTENDED USE

The software will be used during any document review where the document contains references to other TCE documents. The software will easily identify the references within a document to see if they are released in TCE.
5.0	TOOL VERSION

This version of Doc Checker Tool is 2.0. Each update would involve the updating of the following files
•	FileConversion.exe
•	tesTCE.exe
•	sjm_SWKit_Data_extract.exe
•	Start.bat
•	Sylmar.bat
•	Sunny.bat
•	CanIProceed.exe
•	FileCreator.exe
•	Sunny_Enter.exe
Copying of the above mentioned files is sufficient after each update.


6.0	 INSTRUCTIONS FOR INSTALLATION

The tool works best for Microsoft Office 2010 and above. Make sure to have Visual C++ 2005 installed in your system.
7.0	 INSTRUCTIONS FOR USE

•	Copy the folder Document_checker folder into your C folder (make sure it is in C drive because all the paths are set from the C drive).
•	Run the Start.bat file
•	A pop up will appear asking you to select the documents. After selecting the document, wait till the program makes a pop up saying “Successfully updated the file. Press any button to continue”. Select the required button.
•	The excel sheet will be generated with the required information.
NOTE 1: If the Sunnyvale has not shown the status of registering after 2 minutes of launch, kindly select that window and press enter. This might have been because the window has gone to sleep.
NOTE 2: Run cleanup.exe and Cleanup123.exe before using the tool if the previous execution has errored out.
NOTE 3: Make sure you do not write on the excel sheet while the program is using it, this would cause an error and one might have to start again.

8.0	SUPPORT PLAN
Software Development Quality will be responsible for the maintenance and update of this tool.
9.0	TRAINING MATERIAL
Engineers will be trained by performing the instructions for installation and instructions for use detailed in this document. No formal training is required.
10.0	FILE LISTING
•	Svprod_Data_nonsso
•	Sytce_data_nonssoTCE2008_2T
•	FileConversion.exe
•	Sjm_SWKit_Data_Extract.exe
•	testTCE.exe
•	Start.bat
•	Sunny.bat
•	Cleanup.exe
APPENDIX A– DEVELOPER INSTRUCTIONS
Environment Setup
In order to develop the Doc Checker Tool, the proper environment must be setup for code compilation and editing. The source code for the tool is developed using Microsoft Visual C# 2015 Express and Visual C++ 2005. A valid installation of Microsoft Office 2010 or greater is recommended. 
Editing the code
Open testTCE.sln in Visual C# Express and modify the necessary lines of code. This project deals with the parsing of the given file and picking out the possible document numbers. 
Goto docchecker->project->sjm_SWKit_DATA_Extract.sln in Visual C++ 2005 and make the necessary changes.
Open the FileConversion.sln in FIleConversion folder in Visual C# Express and make necessary changes. 
Open cleanup folder in Visual C# Express and add additional files that need to be deleted.
Make sure that you have all the latest versions of the above files listed in section 10.0. Login issues might arise if you do not have the latest version.


