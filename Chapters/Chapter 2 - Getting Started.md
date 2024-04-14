# Chapter 2 - Getting Started
## 1. What the Pen Drive (USB) or CD includes:
The installation Pen Drive (USB) or CD includes the following:
1. An installation program for the Offline CASS. The installer includes uninstallation support.
2. The User Manual in Adobe PDF format.
3. Adobe Acrobat Reader 2015.
4. Installation files for DotNET framework 4.0 
5. Installation files for the SQL Server Express 2008
6. Installation files for the Crystal Reports Runtime Ver. 13_0_20

## 2. System Requirements
The following configuration is based on environments used during development. As such, they should be treated as mere recommendations as opposed to instructions. Where a specific brand of software is recommended, the recommendation should not be assumed to be the assumption of any liability, by the author that may arise from the use of the software.

The following is the recommended system configuration
1. A Personal Computer running Microsoft Windows 8 or higher, with 2GB RAM and 40GB HDD.
2. A printer capable of printing onto A4 paper.
3. Pen Drive (USB) or CDROM Drive to facilitate installations.
4. A reliable internet connection to download the software from WAEC website (https://waecinternational.org/cass/downloads).

In the following section, it is assumed that your CD-ROM or Pen Drive (USB) is on drive D. If this is not the case, then substitute your Pen Drive (USB) or CD-ROM drive letter in the appropriate places.

## 3. Installing the Pre-requisites
1. Close ALL any applications that you may be running on your PC
2.	Insert the Pen Drive into the USB port or CD into your CD-ROM drive
3. Copy the folder D:\Prerequisites to your hard disk.
![](/assets/images/c02/c2.1.png)

## 4. Installing Dot Net framework 4.0
> Note that for the application and other prerequisite applications to work, we must first install Dot Net framework 4.0 or higher. The procedure of installing is as follows:

1. Double click the DotNetFX… folder and double click on the application the file in the folder
![](/assets/images/c02/c2.2.png)

2. Follow the on-screen instruction while the application installs
![](/assets/images/c02/c2.3.png)

3. When the installation is completed, click the Exit button
![](/assets/images/c02/c2.4.jpg)

## 5. Installing SQL Server
1. After launching the program, you may get the following dialog depending on your User Access Control settings. Click the Run button to continue.
![](/assets/images/c02/c2.5.png)

2. The next screen requests you accept the license agreement. Please make sure you do that, or you could run into trouble later on if you violate the EULA. Click the Accept button to continue.
![](/assets/images/c02/c2.6.png)

3. To proceed with the setup, please click the tab labelled 'Installation'. Then Click 'New SQL Server stand-alone installation or add features to an existing installation.
![](/assets/images/c02/c2.7.png)
![](/assets/images/c02/c2.8.jpg)
 
> Note: Please ensure that all rules listed in the dialog box are checked green as shown above or their status are marked PASSED. Where there is an error, ensure that the error is resolved before proceeding. In fact, the installation will not continue until the errors are resolved.

![](/assets/images/c02/c2.9.jpg)
![](/assets/images/c02/c2.10.jpg)
 
 > NOTE: Ensure that the STATUS on the Setup Support Rules are marked PASSED as shown above.

4. You only get a choice on this dialog if you’re installing the full version. Choose Next to continue. 

5. Check the ‘I accept the license terms’ box, and then click the Next button to continue the installation.
![](/assets/images/c02/c2.11.png)
 
6. Note, the installation of Now you start the SQL Server 2014 2008 started install. Click the Install button to continue. This’ll take a few minutes then you’re prompted to continue.
![](/assets/images/c02/c2.12.png)

7. You should get all check marks but if your firewall ports are closed then below, is what you’ll get as output. Click the Next button to continue.
![](/assets/images/c02/c2.13.jpg)

8. The Features selection dialog is important. Click the Select All button if you wish to install all features or you may customize your installation by selecting features that you wish to install from the boxes as shown below. Click the Next button to continue.
![](/assets/images/c02/c2.14.png)

9.  Now you Accept the installation of ‘SQLExpress’ as the named instance by clicking the Next button.  
![](/assets/images/c02/c2.15.png)

10. Accept the 1,446 MB space requirement by clicking the Next button.
![](/assets/images/c02/c2.16.png)

11. The account name must be an authorized user account defined by the system or left blank. Leave it blank! Click the Next button to continue.
![](/assets/images/c02/c2.17.png)

12. The easiest way to enter a valid credential is to click the Add Current User button. Click the Add Current User button then click Next to continue.
![](/assets/images/c02/c2.18.png)

13. Choose which pieces of information you’d like to send. Not checking anything is also an option. Click Next button to continue.
![](/assets/images/c02/c2.19.jpg)

14. Now the installation will check if everything works before attempting it with the rules you’ve entered. Click the Next button to continue.
![](/assets/images/c02/c2.20.png)

15. After verifying the installation, is possible, you’ll see what you’re installing before you click the third Install button to continue.
![](/assets/images/c02/c2.21.png)
 
16. It is now time to wait while SQL Server 2014 Express edition installs    
17. When all features are marked success, If you arrive at the next screen, SQL Server 2014 Express has successfully been is installed. Click Next to continue.
![](/assets/images/c02/c2.22.jpg)

18. When the installation is completed, Now you’ll see the final installation dialog and the link to the installation log file. Click on close or finish.

## 6. Installing the Crystal Reports Runtime: 

The Crystal Reports runtime is required for the application to produce reports like; CASS Listing, Students Entry Listing and so on. The installation Pen Drive (USB) or CD contains both the 32-bit or 64-bit runtime versions as required. You could also download either the 32-bit or 64-bit runtimes as required where there is reliable internet connectivity from https://waecinternational.org/cass/downloads then, install. 

The procedure required to install the application is as follows: 
1. Double-click the CRRuntime_32bit_13_0_20.msi or CRRuntime_64bit_13_0_20 12.msi as appropriate.
![](/assets/images/c02/c2.25.jpg)

2. Review the License Agreement and select click I Accept the License Agreement and click Next to proceed.
![](/assets/images/c02/c2.26.jpg)

3. Click Next to install the application.
![](/assets/images/c02/c2.27.jpg)

4. The installation may take several minutes to complete. Please wait
![](/assets/images/c02/c2.28.jpg)

5. Click Finish to complete the installation process.
![](/assets/images/c02/c2.29.jpg)

## 7. Installing the CASS Offline Application
Now that the prerequisite s applications have been successfully installed, you are now ready to install the CASS Offline Application proper. The procedure is 	similar to the steps above.
1. Close ALL any applications that you may be running.
2. Insert the Pen Drive (USB) into the USB port or the CD into your CD-ROM drive on your computer.
3. You may copy the folder D:\WAECCASSSetup to your hard disk or directly install the application from the USB or CD.
4. Navigate to the folder WAECCASSSetup on the CD or Pen Drive (USB). Open the folder you will have copied the files to and run double click on Setup.exe to start the installation of the CASS Offline application on your computer.
5. Follow the onscreen instructions. Please note, again that the precaution to install the program after copying from the read-only media, ensure that the is assure Pen Drive or the CD is not corrupt. If they are corrupted, installation of the application will not be possible. thus affecting the integrity of your setup.

    1. Once the setup wizard launches, you are shown the ‘welcome’ screen
![](/assets/images/c02/c2.30.png)

    2. The wizard asks you to confirm the installation of the software application. Click Next to continue.
![](/assets/images/c02/c2.31.png)

    3. The installation may take a few minutes to complete. Please wait!
![](/assets/images/c02/c2.32.png)

    4. Click Finish to complete the installation.
![](/assets/images/c02/c2.33.png)