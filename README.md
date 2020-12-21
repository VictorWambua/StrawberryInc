# Aver-Tecs-Productions

SOFTWARES USED:

1)Third Party system used - XAMPP 2)Framework Used - Joomla! 3.9 3)iFrame used - Pesapal

APPROACH USED : I used the Model-View-Controller design model to develop the user interface. The model represents the data and it is does not depend on the controller or the view. The view displays the model data, and sends user actions such as button clicks to the controller.

BASIC FUNCTIONALITY:

Xampp software is used as the backend to store the database data of all transactions posted to it.

The developed Joomla donations component will be installed as an extension into the Joomla! Framework and it will appear under the Joomla Components after a successful installation process.

Pesapal iFrame is integrated into the developed Joomla Component to enable the transacting of donation funds through pesapal.

A web service is integrated in the Donation Component developed and it uses JSON web tokens to post all payments (Pending,Failed and Completed ONLY) to XAMPP software.

The site administrators can log in to the back-end and view details regarding each donation (Donor’s name, email or phone number and amount), through the Joomla Framework.

A user is able to donate through a Donation Form.

HOW TO SET UP (ON WINDOWS OPERATING SYSTEM):

1) Download Joomla! CMS Framework.(Latest version 3.9 - Download from the website www.joomla.org)

2) Download XAMPP software. (Download from official website www.apachefriends.org)

3) Install XAMPP software in your PC.

4) Start XAMPP software. On the Control panel of the software, click on the actions start for the modules Apache and MySQL.

4) Unzip Joomla Framework in a Joomla Folder, you can name it any name you prefer but in this case, let’s name it joomla.

5) Open the XAMPP installation folder in Local disk C on your PC,then find a folder named htdocs inside the XAMPP installation folder. Open it. The desktop path should look like this(C:\xampp\htdocs).

6) Copy the extracted joomla folder into the htdocs folder.

7) Open your web browser. Type in the search address bar,’Localhost’ (Without the quotes). A XAMPP Welcome information page will load. Click on the phpMyAdmin menu item. Another database configuration page will load.

8) Create a database user account with password and name it the name you prefer,eg,Aver Techs Productions with password @atp2020, Now create a database and name it the name you prefer. In this case, we named it joomladonations.

9) Open a new tab in yor browser and type in the address bar, ‘localhost/joomla’. An installation and configuration page for the Joomla CMS Framework will appear.

10) There will be 3 steps namely, Configuration, Database and Overview. The first step is configuration.

11) Input the Site Name,this is what you want your donation page to named. You can name it Donations Page.

12) Input Super User Account Details which include Email, eg,avertechsproductions20@gmail.com, username,eg, Aver Techs Productions and Password,eg, @atp2020. Select Language as English(United States). Click Next. You will be taken to step two of the installation and configuration process.

13) On the Database Type, select MySQL(PDO). Hostname will be localhost and Username will be Aver Techs Productions. At this stage, you can name the above field the names you prefer. Create a table prefix,eg, prefix jdc_. Then Click on the Next Button. You will be taken to the final process.

14) In the overview Process, you can install simple data, in this case None radio button is selected. Then Click install. Joomla! will be installed. Click on the “Remove installation folder” button to complete the installation process.

15) Click on the “site” button. Your Site will be loaded, in this case, a web page with the title “Donations Page” is Loaded.

16) Inorder to access the adminstration part, open a new tab in your browser and type in the address search bar, ‘localhost/joomla/administrator’. (without the quotes).

17) A login form will appear, fill in your login details and click on the login button. A control Panel will appear. You have successfully confugured Joomla! Framework for use with XAMPP software.
