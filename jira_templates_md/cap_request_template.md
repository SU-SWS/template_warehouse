

## CAP Credential Request
You request credentials from the "Access API Credentials for Stanford Profiles (CAP)" page in ServiceNow, then enter them into the website.

### Gather credential information
You'll need the following information before filling out the ServiceNow ticket.

* Business Contact Name(s)
* Business Contact Email(s)
* Technical Contact Name(s)
* Technical Contact Email(s)
* Technical Contact SUNetID(s)
* Application/Department Name
* Application Description
* Application URL
* Application Client ID (optional)

Is this an intranet? (Yes/No)
*If the request is for an intranet, be sure to state that.*

### Enter credential information into ServiceNow

1. Log into ServiceNow
https://stanford.service-now.com/services/?id=services_portal_home

1. Go to the "Access API Credentials for Stanford Profiles (CAP)" page:
https://stanford.service-now.com/it_services?id=sc_cat_item&sys_id=3ecd311a13b832008a9175c36144b069
1. Do not select **This request is on behalf of someone else**

1. Paste credential information into the **Describe what you need** text area
1. **Submit**

### Enter credentials into a Drupal site
After submitting your information, your request will need to be approved. Then the University IT OAuth team will setup the credentials and send you the Client ID and Password via a SECURE email.

#### For Drupal 9

1. Go to **Configuration** > **Importers** or `/admin/config/importers/person-importer`
1. Click on **Authorization**
1. Copy and paste the Username and Password from the email
1. **Save**
2. Test connection by importing a person (consider using your SUNetID) at **Structure** > **Migrations**
3. Find the imported person at `/people`
4. If necessary:
   *  **edit** and **delete** node
   * Remove from importer

### Record Credentials
SWS keeps a record of CAP credentials on Confluence and Dashlane (in testing). After putting the credentials on the site, copy them to:
https://asconfluence.stanford.edu/confluence/display/SWS/CAP+Credentials

Dashlane: https://app.dashlane.com/credentials#/login

