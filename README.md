# Technical Tests for Smartmatic Application
 
 Please follow these instructions in order to run the script

## Requirements to run it through CMD or PowerShell

- Have installed node.js, you can find it [here](https://nodejs.org/es/) if you do not have it installed.
- ChromeDriver according to your Chrome Browser version, please update first your Chrome Browser to the latest version and then get the ChromeDriver that matches with your Chrome browser version from this [link](https://chromedriver.chromium.org/).

## Installation and running for a Windows machine with Google Chrome

- Clone this repository
- Move to the local repository folder where the test script is and paste there the ChromeDriver.exe file previously downloaded.
- Then add the ChromeDriver path to the Environment Variable > System Variables >PATH > Click Add and paste the path there.
- Open your cmd or powershell, move to the repository directory and install the Selenium Command-Line Runner with this command: ```npm install -g selenium-side-runner```
- Then install the browser driver with this command: ```npm install -g chromedriver```
- Then run the script with this command: ```selenium-side-runner /path/to/your-project.side```

## Installation and running for any computer with Chrome, Firefox or Edge browser

- To install the extension (IDE) for Chrome and Edge, click [here](https://chrome.google.com/webstore/detail/selenium-ide/mooikfkahbdckldjjndioackbalphokd).
- To install the extension (IDE) for Firefox, click [here](https://addons.mozilla.org/en-GB/firefox/addon/selenium-ide/).
- After the installation is complete, open the extension and will show you the IDE, click "Open an existing project" and the click the "►" icon to run the script
