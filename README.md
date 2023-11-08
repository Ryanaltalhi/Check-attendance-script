# Check-attendance-script


## Project Description
This script is developed using Google Apps Script to process data in a Google Sheets and move data based on specific conditions. The primary purpose of the script is to count the occurrences of email addresses in the sheet and transfer data to a new sheet if certain conditions are met.

## How to Use
To use this script, follow these steps:

1. Open the Google Sheets containing the data you want to process.

2. Add the script to the Google Sheets by going to "Extensions" and then selecting "Apps Script." Paste the code into the new window.

3. You can configure various variables, conditions, and processing details according to your needs. You can modify the `minAttendanceRequired` variable and other parameters as needed.

4. Run the `compareAndMoveData` function by clicking the play button in the Apps Script editor. This will execute the script and perform the data processing.

5. The script will check for the specified conditions and move data to a new sheet called "NewData" if the conditions are met.

## Code Explanation
The code consists of two main functions:

- `compareAndMoveData`: This function processes the data in multiple sheets, counts email occurrences, and moves data based on specified conditions.

- `isEmailAlreadyMoved`: This function checks if an email has already been moved to the new sheet to avoid duplication.

Feel free to modify the code, variables, and conditions to suit your specific use case.

