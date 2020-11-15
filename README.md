# RPADeveloperNanoDegree-Sorting-Annual-Reports
An automation that accepts GitHub repository link, that has files with specific naming pattern, and download it. Then it sorts the files into folders depending on the files naming.\
- Program a Robot to start the automation by opening this Github Repo with a web browser.\
- Program a Robot to click on the download button and download the zip file in the Downloads directory.\
- Program a Robot to move the downloaded zip from the Downloads directory to the Project directory.\
- Program a Robot to unzip the downloaded file that you have recently moved to the project directory.\
- Program a Robot to sort the files into the desired folder depending upon the name of the file:
- If the file name follows the format of “CustomerName_Report_DDMMYYYY.xlsx/.pdf” sort this into a folder based on the year (YYYY). For example, for a file named “JaneDoe_Report_28102019.pdf”:\
 - If there is no folder named "2019" create one and move the file to the new folder.\
 - If there is already a folder named "2019", move the file to the existing folder.\
 - If any of the file(s) is/are not in the “CustomerName_Report_DDMMYYYY.xlsx/.pdf” format then program a Robot to create a new folder with today’s date (format MMDDYYYY) and move 	-them there.\
 - Repeat Step 5 for all the remaining files present.\
 - Program the Robot to successfully end the automation if all the files are sorted.\
