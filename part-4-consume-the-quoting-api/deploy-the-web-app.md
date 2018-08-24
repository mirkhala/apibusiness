## Deploy the sample web application

* Go to htps://master.REPLACE\_SUFFIX:8443
* Login as ...
* Click on **Select from Project.**
* Select **openshift** project.
* Select the **quoting-app** template.
* Click **Next**.
* Click **Next.**
* Select **Create Project.**
* Enter "**quoting-app**" as the **Project Name**
* Enter "**Quoting WebApp" **as the** Project Display Name.**
* Open a new browser tab and go to 3scale admin console.
* * Enter the following paramteres:

| Parameter | Value |
| :--- | :--- |
| **Application Hostname** | quoting.REPLACE\_SUFFIX |
| **Quotes API URL** | https://3scale.3scale.REPLACE\_SUFFIX/swagger/spec/quotes.json |
| **Quotes API Client Secret** |  |
| **Quotes API ClientID** |  |
| **RH Single Sign-On URL** |  |

* 


