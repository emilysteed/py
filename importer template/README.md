# Country Team x NIS Program Template Compare
#### Written By: Emily Steed
## Purpose: 
    This Jupyter Notebook was created to allow Act East NIS users to compare versions of Importer Template Files. 

## Set-Up:
    Before utilizing this program, the following must be complete:
    1) Download VS Code (or preferred code editor) - https://code.visualstudio.com/
    2) Download Python - https://www.python.org/downloads/
    3) Download Git - https://git-scm.com/downloads
    4) Create GitHub Account - https://github.com/

## Introduction:

    "Nis_download" and "country_download" are the files to be compared, "summary_output" is a .txt extension where you would like the summary comparison report to be saved, and "additions_deletions" is a .xlsx extension where you would like the additions and deletions to be saved. Note that the names "nis_download" and "country_download" represent a common use case, but any two importer files may be compared using this program.

    There are two outputs: (1) Summary TXT file and (2) Additions/Deletions XLSX file. 

    The summary TXT file will highlight all changes between events (identified by the combination of their Event UID and Organisation Unit). It will also highlight all event additions and deletions. However, because the TXT file will only highlight the first ten columns/variables of added/deleted events, I have created a second XLSX output which will contain all variables for those events. 

## Running the Program:

    Navigate to the home page of this repository. Click the green <> Code button, and copy the link. This will allow you to clone my repository and run the code on your computer.

    Then, open up your terminal in VS Code. Type "git clone"; add the URL that you have just copied at the end of the statement. Press enter, and the cloned repository will appear. 

    Before running the program, ensure that the Macros "nis_download", "country_download", "summary_output", "additions_deletions" are updated. 

