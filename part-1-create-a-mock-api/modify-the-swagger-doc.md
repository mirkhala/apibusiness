* Go to [http://apicurio.REPLACE\_SUFFIX](http://apicurio.REPLACE_SUFFIX)
* Click on the **Register** link.

![](/assets/apicurio-register.png)

* Complete the form with the following values:  
  | Parameter | Value |
  | :--- | :--- |
  | **First Name** | Username |
  | **Last Name** | Lastname |
  | **Email** | [user@mail.com](mailto:user@mail.com) |
  | **Password** | password |
  | **Confirm Password** | password |

* Click on the **Register **button.

![](/assets/apicurio-register2.png)

* Click on the** Import API** button.  
  [![](https://github.com/pszuster/3scaleTD_gitbook/raw/master/assets/Selection_342.png)](https://github.com/pszuster/3scaleTD_gitbook/blob/master/assets/Selection_342.png)

* Enter the URL copied in the previous step.

* Click on the **Import API** button.

![](/assets/apicurio-importAPI.png)

* Click on the **Edit API** button.

![](/assets/apicurio-editAPI.png)

* Click on the **Add** button in the **Definitions **section**.**

* Enter **Driver** and click on the **Add** button.

![](/assets/apicurio-addDefinition.png)

* Add the following properties:

| Property name | Type |
| :--- | :--- |
| driverID | String |
| firstName | String |
| lastName | String |
| fines | Integer |
| validLicense | Boolean |

![](/assets/apicurio-DriverProps.png)

* Click on the **/Driver/:id** path.
* Click on the **GET** operation.

![](/assets/apicurio-DriverGetOP.png)

* Click on the **Edit** button next to the **200 OK** Response, in the **Responses **section.

![](/assets/apicurio-EditResponse.png)

* Select **Driver** as the **Type.**

* Click on the **OK** button.

![](/assets/apicurio-DriverPropsResponse.png)

* Click on **Driver** in the breadcrumb.

* Click on the three dots in the **Driver **API, and select **Download \(JSON\)**.

![](/assets/apicurio-SaveJSON.png)

* Save the file to your disk.



