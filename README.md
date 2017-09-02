# User Instruction
The best way to use, examine and interact with the Octans Employee Recognition app is to navigate to the project website: [Employee Recognition](https://octans-employee-recognition.herokuapp.com/).

However, if for some reason the URL is not working or if you would like to run the application locally, please follow the instructions below to set up and run the application:

* Confirm you have node.js installed or Install the most recent version found here: [https://nodejs.org/en/download/current/](https://nodejs.org/en/download/current/) .
* Confirm you have an AMP server installed or install one such as MAMP, found here: [https://www.mamp.info/en/]([https://www.mamp.info/en/) .
* Download the files from Github to a directory of your choice.
* Navigate to the directory you unzipped the source code to.
* Install dependencies using the 'npm install' command from a command line prompt.
* Update the /config/database.json file with database credentials of your local environment.
* Run /sql/recreate_tables.sql to create tables needed by the app. You must create a local database prior to executing this SQL.
* Install TexLive to support PDF creation via LaTeX. An installer is available here:
[https://www.tug.org/texlive/acquire-netinstall.html](https://www.tug.org/texlive/acquire-netinstall.html)
* Start the application using the 'npm start' command from a command line prompt.
* Verify you received a message on the command line confirming the server is listening.
* Open a web browser and navigate to localhost:3000 to access the application.
