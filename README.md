# webapp-slowness
Azure App Service application slow <br>
This is the Lab for investigating application slowness issues deployed in Azure App Service. 

## Scenario:
In this lab, you will need to 
- Deploy the application code to an App Service. 
- Enable Application Insights.
- Capture profiler traces to investigate the issue and to find out the root cause. 

## Goal:
-	Is to deploy the app to Azure. Reproduce the issue by opening multiple tabs and navigate to FeatureProducts.aspx page. The more tabs you have open, you will see the pages start to spin and delay in content rendering. 
-	To capture profiler trace, navigate to the app service in the portal. Under **Diagnose and Solve problem**--> **Diagnostic tools** --> click on **Collect .Net Profiler trace** and reproduce the issue.<br>
Image:
![](https://github.com/4lowtherabbit/Labwebappslow/blob/master/imag.png)

## Deployment Instructions:
1.	Download the solution as a zip file to local.   
2.	Drag & drop the zip file to the wwwroot folder of an empty site to deploy it.
