# Chat App 
Simplified concept of chat application for php beginners

# Requirement

- Xampp &nbsp;<img src="https://github.com/Howdy-admoll/Howdy-admoll/blob/main/images/xammp.png" alt="xampp" width="25" height="25"/>
- Code Editor (I'm using VSCode) &nbsp;<img src="https://github.com/Howdy-admoll/Howdy-admoll/blob/main/images/vscode.png" alt="VsCode" width="48" height="48"/>

# Installation

- XAMPP is completely free and easy to install Apache distribution containing MySQL, PHP, and Perl. First, download XAMP from https://www.apachefriends.org/download.html. In the first page, select the components you want to install. <p align="center">
<img src="https://github.com/Howdy-admoll/Howdy-admoll/blob/main/images/runXampp.png" alt="setup" width="auto" height="auto"/></p>

- Select the installation directory so that all the components that you choose will be installed in this directory. <p align="center">
<img src="https://github.com/Howdy-admoll/Howdy-admoll/blob/main/images/instXampp.png" alt="install" width="auto" height="auto"/></p>

- XAMPP also allows you to easily [install PHP](https://github.com/Howdy-admoll/Hello) based applications. Bitnami module provides the easiest way to install WordPress, Drupal or Joomla among others on top of your XAMP after the installation you will see the control panel.

- Once you are done with Xampp installation, let’s move ahead to ```setting up the Database``` and see how to run a PHP file in xampp server.

## Setting Up The Database 

- After completion of the installation, you can use the XAMPP Control Panel to start/ stop all servers. Start Mysql and Apache servers. <p align="center">
<img src="https://github.com/Howdy-admoll/Howdy-admoll/blob/main/images/strtXampp.jpg" alt="start" width="auto" height="auto"/></p>

- Copy downloaded or forked HELLO file to htdocs (C:/Program Files/XAMPP/htdocs)

 In order to get the dashboard for localhost: search ```http://localhost``` in any browser. <p align="center">
<img src="https://github.com/Howdy-admoll/Howdy-admoll/blob/main/images/dashXampp.png" alt="start" width="auto" height="auto"/></p>

- Now navigate to ```phpMyadmin``` in the menu-bar or search ```http://localhost/phpmyadmin``` in your browser
1. Click ```New``` to create new Database (Database name = ```chat``` then navigate to the dropdown tab and select ```collation```)
2. click the button ```create```
3. Go to the ```import``` tab in your  Chat database and click IMPORT
4. upload the ```chat_info``` file contained in your sql database folder
5. click ```Go``` to complete the import.

- Now you're done with Database setup

- In order to get your application in localhost: search ```http://localhost/chat``` in the browser.

- Happy coding and chatting
