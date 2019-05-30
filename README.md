## SECTION 1 : PROJECT TITLE
## NUS ISS Chat Bot Agent 


<img src="images/branding-iss.png"
     style="float: left; margin-right: 0px;" /> 

<!---
<img src="images/branding-iss.png"
     style="float: left; margin-right: 0px;" width="400" /> 
-->
## SECTION 2 : EXECUTIVE SUMMARY / PAPER ABSTRACT
In Singapore shuttle services to ferry students from their home to school and back is quite common. Probably every Singaporean would have travelled in a shuttle service during their student days.

Our team of 4 Singapore residents have also gone through the process of selecting shuttle services for our school going children and the biggest challenge we found was to find a service which takes the shortest distance to reach the school from our house at a reasonable cost and able to service multiple schools at the same time. 

We believe that many other Singapore parents would also be finding similar difficulties in selecting shuttle services for their children for a nominal cost. This provides a greater opportunity to address the gap in the market and thus we decided to embark on this project. In this project, we are assuming that we are a service provider having few depots operating shuttle buses at our disposal. We would be providing shuttle services optimized through the implementation of Reasoning Systems Optimization techniques using KIE workbench, Drools and OptaPlanner.  

We felt that the scale and scope of the project was such that many more options for optimization could have been explored e.g. the amount of time taken for students to reach school taking traffic conditions in to consideration on top of travel distance optimized. However, given the time limitations we were happy with the solution we were able to achieve as part of this project.  

#### Welcome to NUS Institute of Systems Science (ISS) Chat Bot Agent
<H6>You may ask me like : 
"List of Graduate Programs offered" or 
"Want to know about Master of Technology in Enterprise Business Analytics"</H6>

<iframe
    allow="microphone;"
    width="350"
    height="430"
    src="https://console.dialogflow.com/api-client/demo/embedded/d67c9f9f-521d-42ab-b497-0587ccf865ab">
</iframe>


Project Git Repository : https://github.com/aivoyagers/IRS-CS-2019-04-27-IS1PT-GRP02-aiVoyagers-NUS-ISS-ChatBot.git 

---
## SECTION 3 : CREDITS / PROJECT CONTRIBUTION

| Official Full Name  | Student ID (MTech Applicable)  | Work Items (Who Did What) | Email (Optional) |
| :------------ |:---------------:| :-----| :-----|
| SUDALAIANDI RAJA SUDALAIMUTHU | A0195338U |Chat Bot Design Approach, DailogFlow Configuration and Build, Knowledge Base Scraping in to FAQ Template, Knowledge Base FAQ for Graudate Programmes, Testing of DialogFlow, Project video, GitHub Repo Setup, Userguide and Readme | E0384969@u.nus.edu |
| JAYARAMAN REVATHI | A0195357R | Webpage Design and Client Side Programming, Knowledge Base FAQ for Stackable Programmes and Center of Excellence, Integration | E0384988@u.nus.edu |
| JAYASRI RAGHUNATHAN | A0005978U | Project Report, Architecture Diagram, Web Scraping for Knowledge Base build | E0384183@u.nus.edu |
| SUNIL VARGHESE | A0195247W | Knowledge base for Executive education FAQ, Project Report | E0384878@u.nus.edu |


---
## SECTION 4 : VIDEO OF SYSTEM MODELLING & USE CASE DEMO
[![IRS Intelligent Rapid Shuttle](SystemCodes/static/IRS-Output.jpg)](https://youtu.be/W3MZEjSZb8A "IRS Shuttle Service")
Click the image above to view Video. Alternatively, you can view following the link https://github.com/aivoyagers/IRS-RS-2019-03-09-IS1PT-GRP-aiVoyagers-irs-Intelligent-Rapid-Shuttle/blob/master/Video/IRSVideo.MOV

---
## SECTION 5 : USER GUIDE
NUS ISS Chat Bot Agent is a web based Chat Bot Agent using Google DialogFlow for providing human like servicing agent providing response to questions raised by prospective students of NUS ISS. 

Follow below steps to setup NUS ISS Chat Bot Agent system.

+	git clone https://github.com/aivoyagers/IRS-CS-2019-04-27-IS1PT-GRP02-aiVoyagers-NUS-ISS-ChatBot.git
+	Use your web browser to navigate to DialogFlow website https://dialogflow.com/
+ Login to DialogFlow with your Google userid and password
+ Click 'Go to Console' to enter in to DialogFlow
+ Create a new DialogFlow Agent and Save
+ Upon successful completion of Agent Creation, Click Settings icon next to the Agent name.
+ Select 'Export and Import' Menu option in Settings page and Click 'Import From ZIP' option to import DialogFlow agent from the file "SystemCodes\NUS-ISSchatBOT-aiVoyagers.zip" downloaded from GitHub cloned project folder.
+ Open Web HTML file SystemCodes\NUS-ISS-ChatBot.html using your browser to initiate dialog with Chat Bot Agent system. The default HTML file uses iFrame with pre-built Agent running in DialogFlow. 
+ You can follow this step, If you like to configure to use your own imported DialogFlow agent. You may skip this step, if you want to use default Chat Bot Agent system. Please copy/paste iFrame code from 'Integrations' option selecting 'Web Demo' on to HTML file. 
+ Enter questions like :
  + Overview of Graduate Diploma in Systems Analysis programme (GDipSA)
  + Technical learning outcomes of Master of Technology in Enterprise Business Analytics programme (MTech EBAC)
  + Modules of Master of Technology in Digital Leadership (MTech DL)
  


---
## SECTION 6 : PROJECT REPORT / PAPER
### Table of Contents

* Executive Summary
* Business Problem Background
* Project Objective
* Project Solution
* Project Scope
* System Features
* Limitations
* Conclusion
* Improvements



---
## SECTION 7 : MISCELLANEOUS

### 7.1 Domain Class Diagram  
<img src="SystemCodes/static/IRS-Class-Diagram.png"
     style="float: left; margin-right: 0px;" /> 

### 7.2 IRS Systems Artchitecture  
<img src="SystemCodes/static/IRS-Systems-Architecture.png"
     style="float: left; margin-right: 0px;" /> 

---
