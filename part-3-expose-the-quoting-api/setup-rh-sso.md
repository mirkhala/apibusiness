## Setup RH-SSO

* Go to [https://sso-rh-sso.REPLACE\_SUFFX/auth](https://sso-rh-sso.REPLACE_SUFFX/auth)
* Login as admin/password
* Make sure the **3scaleRealm **realm is selected.
* Click on the **Login **tab.
* Click on the **Save **button.
* Select **none **for the **Require SSL **field.

![](/assets/sso-setupRealm.png)

* Click on **Clients. **
* Click on the **Create **button.

![](/assets/ssosetup-CreateClient.png)

* Enter the following values:
  * **Client ID**: 3scale-client
  * **Client Protocol**: openid-connect
* Click on the **Save** button.

![](/assets/sso-setup-Client2.png)

* Set the following parameters:

| Parameter | Value |
| :--- | :--- |
| **Access Type** | confidential |
| **Standard Flow Enabled** | OFF |
| **Direct Access Grants Enabled** | OFF |
| **Service Accounts Enabled** | ON |

* Click on the **Save **button.

![](/assets/sso-setup3scaleclient.png)

* Click on the **Service Account Roles **tab.
* Select** realm-management **in the **Client Roles** drop-down.
* Select **manage-clients** in the **Available Roles** list.
* Click on the **Add selected &gt;&gt;** button.

![](/assets/sso-setup-configure3scaleClient.png)

* Click on the **Credentials** tab.

* Take note of the **Secret**, you will need it later.

![](/assets/sso-setup-3scaleclient-secret.png)

* Click on **Users** \(under **Manage**\).

* Click on the **Add user** button.

* 


