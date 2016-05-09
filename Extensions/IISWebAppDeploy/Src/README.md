# **IIS Web App Deployment Using WinRM**

Using Windows Remote Management (WinRM), connect to the host machine(s) where IIS is installed, and manage the Web application as described below:

 - Create a new website or update an existing website.
 - Create a new application pool or update an existing application pool.
 - Deploy a Web Application to the IIS Server using Web Deploy.

The SQL Server Database Deployment task will be added to the extension in the next update.

VSTS accounts that are using the **preview tasks** wiz. **IIS Web Application Deployment** or **SQL Server Database Deployment**, should move to this extension. All **future enhancements** to the IIS Web App Deployment task or to the SQL Server Database Deployment task will be provided in this extension.

## **Usage**

The extension installs the following tasks:

  ![IIS Web App Deployment Using WinRM](images/IISWebDeploymentTasks.png)

- **WinRM: IIS Web App Management**: Create or update IIS websites and app pools. The task's detailed documentation is in the [source repo](http://aka.ms/IISMgmt).

  ![WinRM: IIS Web App Management](images/IISWebManagement.png)

- **WinRM: IIS Web App Deployment**: Deploy an IIS Web App using Web Deploy. The task's detailed documentation is in the [source repo](http://aka.ms/IISWebDeploy).

  ![WinRM: IIS Web App Deployment](images/IISWebDeployment.png)

### **Contact Information**

For further information or to resolve issues, contact RM_Customer_Queries at Microsoft dot com.