# BlackBerryProtectTDR-PowerBIViewer
Power BI Reports using BlackBerry Protect Threat Data Report data feeds. This Power BI Template includes reports for Event, Threat, Memory Protection, Devices, Policies, and External (USB) devices. This report can be shared with others in your organization and schedule to automatically download the TDR data once per day.

** Power BI Template now supports all regions via a list parameter -- Thanks for the idea Sameh Sabry ** 

## Background
This Power BI Template is based on the following blog series:  
http://securitysynapse.blogspot.com/2020/09/fun-with-microsoft-power-bi-part-i-intro.html
http://securitysynapse.blogspot.com/2020/10/fun-with-microsoft-power-bi-part-ii.html
http://securitysynapse.blogspot.com/2020/10/fun-with-microsoft-power-bi-part-iii.html
http://securitysynapse.blogspot.com/2020/10/fun-with-microsoft-power-bi-part-iv.html


## Prerequisites
1. Microsoft Power BI Desktop
2. Microsoft Power BI Service (Online) to share report and schedule updates


## How to use
1. Download the Power BI template (.pbit)
2. Open the template
3. Select your region and enter your TDR Token (obtained from the BlackBerry Protect console: Settings > Application > Threat Data Report)
4. Wait for data to load
5. Ensure reports are populated and working properly

(Optional sharing and auto updating)  
6. Click Publish button (to your own workspace if you wish to keep it private)  
7. You will be asked to save a local copy (.pbix) with the data  
8. Once in the Power BI Service (Online), under MyWorkspaces > Datasets > Schedule Refresh  

## Screenshots
![Threats Report](https://github.com/TonyLeeVT/BlackBerryProtectTDR-PowerBIViewer/blob/main/screenshots/ThreatsReport.png)
![Policy Explorer](https://github.com/TonyLeeVT/BlackBerryProtectTDR-PowerBIViewer/blob/main/screenshots/PolicyExplorer.png)
