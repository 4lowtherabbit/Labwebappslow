# webapp-slowness
Azure App Service application slow <br>
This is the Lab for investigating application slowness issues deployed in Azure App Service. 

## Scenario:
In this lab, you will need to 
- Deploy the application code to an App Service. 
- Enable Application Insights.
- Capture profiler traces to investigate the issue and to find out the root cause. 

## Goal:
-	Is to deploy the app to Azure. Reproduce the issue by opening multiple tabs and navigate to FeatureProducts.aspx page. The more tabs you have open, you will see the pages start to spin and delay in cont rendering. 
-	To capture profiler trace, navigate to the app service in the portal. Under **Diagnose and Solve problem**--> **Diagnostic tools** --> click on **Collect .Net Profiler trace** and reproduce the issue.
Image:
![](https://github.com/4lowtherabbit/Labwebappslow/blob/master/imag.png)

## Deployment Instructions:
1.	Click on the “Deploy to Azure” button. 
   This will open a new browser window and navigate to the Azure Deployment Page. <br>
2.	Choose your subscription and fill in other content <br>
3.	Click on "Deploy". <br>

## Deployment Link:
<a href="https://deploy.azure.com?repository=https://github.com/4lowtherabbit/Labwebappslow" target="_blank">
    <img src="https://azurecomcdn.azureedge.net/mediahandler/acomblog/media/Default/blog/deploybutton.png"/>
</a> 
