# Movies & Books Management System - Android

**Movies & Books Management System Android** is an simple **Salesforce Mobile SDK** based [Connected App](https://help.salesforce.com/s/articleView?id=sf.connected_app_overview.htm&type=5) that uses Salesforce API to access records that are available in its [Salesforce version](https://github.com/artysta/movies-and-books-management-system-salesforce).

There are two steps you have to do in order to make this application working. At first you have to deploy its Salesforce version - [Movies & Books Management System Salesforce](https://github.com/artysta/movies-and-books-management-system-salesforce). You can find the deployment instructions in the README.md file of the linked repository.

After deployment you should:
 - go to the Setup
 - search for the App Manager
 - locate **Movies_and_Books_Management_System_Android** application
 - click on the down arrow icon at the end and select **View** from the dropdown menu (check the screenshot below)

 <img src="./screenshots/connected-app.png" alt="connected-app.png"/>

 - copy API Consumer Key
 - clone this repository

    ```console
    git clone https://github.com/artysta/movies-and-books-management-system-android
    ```

 - open **movies-and-books-management-system-android\app\res\values\bootconfig.xml** file in a text editor
 - replace **YOUR_CONSUMER_KEY_GOES_HERE** value with the key you have just copied

The easiest way to run this application is to use Android Studio.
 - open Android Studio
 - click File -> New -> Import Project...
 - search for cloned repository
 - select **movies-and-books-management-system-android**
 - click OK button
 - wait for Gradle to build the project 😝
 - select Run -> Run 'app' (you can use AVD or your physical Android device)
 - you need Java 11 to run this application