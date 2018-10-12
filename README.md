# GrayCode_BITSPilani
CodeFunDo++Project_Submission_Repository
Generic Application which can be used in any kind of disaster/calamity. Create datasets of people locally so that they can communicate with each other. During calamity, streamline the data to maximize the efficiency of relief operation. 

<p align="center">
  <img src="https://github.com/redgene/GrayCode_BITSPilani/blob/master/InkedUntitled%20Diagram_LI.jpg" width="350" title="Architecture Diagram">
</p>

Image above shows the architecture diagram on how the application works. The affected people form small groups and upload their locations/ages/severity on the application. Then the rescue teams/volumteering groups take the optimized route to reach them.

## Before the disaster
As soon as the warning is issued by the local government, Bing Maps of their locality will be downloaded, this is done to ensure that even if there is no connectivity, they can help themselves to get out of the situation.
## Features of our app
* The user can fill their situation and severity of the condition they are in. User can inform about other people or about his/her locality or find their friends/family. Datasets of people trapped locally will be created to intraconnect them, this encourages them to form self help groups. 
* The data will then be processed on Azure Cloud. The analysed information will then be used to connect the volunteering groups among themselves and with people affected to maximize their efforts. The shortest path for the relief operation will be calculated using Bing Maps Routing API for effective contribution. Map will be updated in realtime with road-blocks, affected areas and nearest shelters, drinking water, helplines, medicines, transportation, etc.
* In case of remote regions the app will automatically try to repetedly send the compiled information as a distress to the cloud and guide them to take necessary steps meanwhile.


