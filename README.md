# Jobvio.in - Online Job Portal

## How to install Xampp?
It is completely free and easy to install Apache distribution containing MySQL, PHP, and Perl. First, download XAMP from https://www.apachefriends.org/download.html. In the first page, select the components you want to install.

![xmp1](https://user-images.githubusercontent.com/83587918/163679429-fbd3084d-7a9a-498b-99d0-b750e9687130.png)

Select the installation directory so that all the components that you choose will be installed in this directory.

![xmp2](https://user-images.githubusercontent.com/83587918/163679479-42947763-34f3-44cb-9dd3-f1ca768f92eb.png)

XAMP also allows you to easily install PHP based applications. Bitnami module provides the easiest way to install WordPress, Drupal or Joomla among others on top of your XAMP after the installation you will see the control panel.

Once you are done with Xampp installation, let’s move ahead and see how to run a PHP file in xampp server.

## How to run PHP program in Xampp step-by-step?
- Download this repository as zip file. Extract it and rename folder as "jobportal"

- After completion of the installation, you can use the XAMPP Control Panel to start/ stop all servers.

- Start Mysql and Apache servers.

![xmp3](https://user-images.githubusercontent.com/83587918/163680203-5a2f78e3-4324-4737-b405-00e0fed00c3d.jpg)

- Copy that folder (jobportal) to "htdocs" (C:/Program Files/XAMPP/htdocs)

- You can also create any folders inside "htdocs" folder and save codes over there.

## Access phpMyAdmin to setup MySQL database
- Select  phpMyAdmin  tab

![xmp5](https://user-images.githubusercontent.com/83587918/163680943-fab2352b-eae9-4485-82b3-87dad7e922f5.png)

Alternatively, you may access  phpMyAdmin  via the XAMPP manager / controller, click  Go to Application  button to access XAMPP dashboard. The main page should look similar to the following

![xmp6](https://user-images.githubusercontent.com/83587918/163681094-54afa2b2-7024-4901-9871-ed572228db0e.png)

## Create a database
Let's create a  jobportal  database. To create a database, there are several options.

You may use the  Create database  feature.
- On the  phpMyAdmin  screen, select the  Databases  tab. Alternatively, you may click the  New  link on the left panel.
- Under the  Create database,  enter a Database name
- Click the  Create  button

![xmp7](https://user-images.githubusercontent.com/83587918/163681284-95167efb-5c74-4253-bf68-908e649963da.png)

## Import SQL file
- On the  phpMyAdmin  screen, select the  jobportal  database
- Select the  Import  tab

![xmp8](https://user-images.githubusercontent.com/83587918/163681358-b0625f30-4e37-4f06-a0d5-0d3acdbac6c5.png)

- Choose the jobportal.sql file to import

![xmp9](https://user-images.githubusercontent.com/83587918/163681424-0342da56-f427-434a-ac4b-be31a9288833.png)

- Click the  Go  button to run the command.

## To access localhost: search http://localhost in any browser.

![xmp4](https://user-images.githubusercontent.com/83587918/163680655-0f1aff0c-8bae-4657-872f-bb841818333a.png)

- To run this project, open localhost/jobportal/index.php or type it in the browser then it gets executed.

![Screenshot (298)](https://user-images.githubusercontent.com/83587918/163680816-c82acd86-da11-4c33-aa1b-f8ba91bb06fc.png)


