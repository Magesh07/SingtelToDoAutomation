# SingtelToDoAutomation

## Installation (pre-requisites)
 1. Minimum Java Version - JDK 11 (make sure Java class path is set)
 2. Minimum Maven apache-maven-3.3.3 (make sure .m2 class path is set)
 3. Eclipse(Version: 2022)
 4. Eclipse Plugins :
       - TestNG for Eclipse
       - Cucumber Eclipse Plugin
 5. Browser driver (Make sure you have your chrome browser driver is placed in '\src\test\resources\Drivers' path as per your local chromre browser version)

## Framework set up
 Open Eclipse->File->Import->Git->Select 'Project from  Git'->Click on Next Button->Clone URI->Paste the Clone URL mentioned below->
click Next Button->Select 'Import as general project'->Click on next button->click on Finish Button

![This is an image](https://github.com/Magesh07/SingtelToDoAutomation/blob/master/ReadMeImages/FinishProject.png)

Clone repository from here(https://github.com/Magesh07/SingtelToDoAutomation.git) from master branch or download zip and set it up in your local workspace.
Update Maven Project By navigating to Right-click on the Project->Maven->UpdateProject->Ok

###### Steps

![This is an image](https://github.com/Magesh07/SingtelToDoAutomation/blob/master/ReadMeImages/3.Select_Repo_Source.png)

![This is an image](https://github.com/Magesh07/SingtelToDoAutomation/blob/master/ReadMeImages/2.SourceGit_Branch_Section.png)

![This is an image](https://github.com/Magesh07/SingtelToDoAutomation/blob/master/ReadMeImages/LocalDestToProject.png)

###### Once project imported into package explorer do  the below steps:
1. Select the Project->Right-click->Select configure->Convert to maven project(As given in the below screenshot)

![This is an image](https://github.com/Magesh07/SingtelToDoAutomation/blob/master/ReadMeImages/MavenProjectCovert.png)

###### Run the Tests :

Windows->Preferences->Java->Installed JREs->Select the JDK as per the below screenshot(Only JDK should be mapped)

![This is an image](https://github.com/Magesh07/SingtelToDoAutomation/blob/master/ReadMeImages/JDKMapping.png)

- Right-click on testng.xml file->RunAs->TestNGSuite
   or 
- Right-click on pom.xml file->RunAs->MavenTest

## Reporters:
Once you ran your tests you can get the test automation reports in below path:
<ProjectFolder>\src\Reports\ExtendReports
 
![This is an image]( https://github.com/Magesh07/SingtelToDoAutomation/blob/master/ReadMeImages/ExtentReport.png)
