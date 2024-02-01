Follow our setup guide to connect Awin to QUANTI:

* * * * *

Prerequisites
----------------------------------------------------------------------------------------------------------------------------------------------------

To connect Awin to QUANTI, you need an [Awin](https://www.awin.com/) account with API access.

* * * * *

Setup instructions
-------------------------------------------------------------------------------------------------------------------------------------------------------------

### Find API token

1.  Log in to your [Awin account](https://ui.awin.com/idp/en/awin/login).
2.  In the top-right corner, click your profile name, then select API Credentials.
3.  In the Password field, enter your login password.
4.  Click Show my API token.
5.  Make a note of the API token. You will need it to configure QUANTI:.

### Find Advertiser ID

1.  In the top-right corner, when you fly over Dashboard tab, you can see the list of your accounts
2.  Numbers between brackets are your advertiser IDs needed.

### Finish Quanti: configuration

1.  In the connector setup form, enter the Destination schema name of your choice.
2.  Enter the API token you found in Step 1.
3.  Enter your advertiser IDs you found in Step 2. You can add all of your ids seperated by commas.
4.  Click Save & Test. Quanti: will take it from here and sync your Awin data.

### N.B

Publishers generate performance through advertising media broadcasting but not only. They also have the possibility of creating their own affiliate links which are not referenced in the creatives on the Awin platform. The awin_table_by_creative_import table gives visibility only to “official” creatives. To have a more global visibility on the performance of an account (advertising media + affiliate links), it is essential to use the awin_stats_by_publisher_import table.

### [Tables](https://dbdiagram.io/d/[Awin-Connector]-Data-Model-6511611dffbf5169f06f6e48)