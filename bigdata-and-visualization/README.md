# Introduction

This is a supplement guide to ‘Microsoft Cloud Workshop - [Bigdata and Visualization](https://github.com/Microsoft/MCW-Big-data-and-visualization/blob/master/Hands-on%20lab/HOL%20step-by-step%20-%20Big%20data%20and%20visualization.md)’, to be used when you are delivering a hands-on-lab session using Cloud Labs AI platform from Spektra Systems. If you have any questions, please reach out to cloudlabs-support@spektrasystems.com

In this workshop, you will complete a web app using Machine Learning to predict travel delays given flight delay data and weather conditions, plan the bulk data import operation, followed by preparation tasks, such as cleaning and manipulating the data for testing, and training your Machine Learning model.

# Verify the pre-provisioned Environment

## Verify Azure Access

Open a browser instance in private or incognito mode and login to [Microsoft Azure Portal](https://portal.azure.com) using the credentials provided. In Azure portal you can navigate to the Resource groups to see the pre-deployed Resource group.
* You should use the existing Resource group during the lab.

> Note: You might have an existing Azure Credential. For the pre-provisioned environment, new Microsoft Azure environment is provisioned and new AAD user is created for you. To prevent conflict with your existing accounts, it is advised to use In Private mode of IE / IE Edge or Incognito mode of Chrome browser.

## Verify Data Science Virtual Machine

You are provided a [Data Science Virtual Machine - Windows 2016](https://azuremarketplace.microsoft.com/en-us/marketplace/apps/microsoft-ads.windows-data-science-vm) with additional softwares configured. FQDN of the virtual machine and administrator credentials are provided in the lab details page. You can remote into the virutal machine using the provided credentials and validate the following:

> Note: DSVM is provisioned in the resource group, in which you have access. Once you login to Microsoft Azure Portal, you can navigate to this VM to find more details.

## Verify the pre-requisite Azure resources
1. **Data Sceince Virtual Machine**
2. **Machine Learning Studio Workspace** is provisioned in the resource group, in which you have access. 
3. **Virtual Network**
4. **Public IP**
5. **Network Interface**
6. **Storage accounts**
7. **Data Factory**


## Notes to Attendees
While doing **Before the Hands-on-lab** section, follow the below steps.
1. You need not to execute **Task 1** in **Before the Hands-on-lab** section, since it is pre-created. You can use the pre-created resources during the lab.
2. You should perform **Task 2**. In this task, you will **register for a trial API account at WeatherUnderground.com**
3. You should perform **Task 3, 4, 5** for Retrieve Azure Storage account information and create container, etc.
4. Don’t deploy **Data Factory** specified in **Task 6**, since it is pre-created.
5. You should perform **Task 7**: Initialize Azure Machine Learning Workbench on the Lab DSVM.
   Need not to download Machine learning Workbench as it is pre-downloaded. You can find the setup of workbench on downloads folder at  desktop.
6. You should perform **Task 8**: Provision Azure Machine Learning Experimentation service
7. You should perform **Task 9**: Create an Azure Databricks cluster

# Known Issues

# Help and Support

If you require any help during the workshop, please reach out to the instructor / proctors. Instructors / proctors might escalate the issue to remote support team, at that time, please pass on your AAD User ID (aad_user_xyz), so that it is easier to look up your environment.


