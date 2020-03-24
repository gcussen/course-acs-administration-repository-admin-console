## What is this for?
The Google Docs Console allows the Alfresco Administrator to configure  the integration between Alfresco Content Services and [Google Docs](https://en.wikipedia.org/wiki/Google_Docs).

[Alfresco Content Services integration with Google Docs](https://docs.alfresco.com/googledocs/concepts/googledocs-intro.html) is available to ACS Share users through the Share function [Edit in Google Docs](https://docs.alfresco.com/6.2/tasks/library-edit-content-googledocs.html) and is also available to ACS developers through Google API access.

## When is it used?
It is used whenever Share users report a problem with Edit in Google Docs function, or when ACS developers are working with a custom Google API integration with Google Docs.

### Current Installed Version
The version displayed here reports the Google Docs AMP version deployed in the Alfresco Repository.

???+ note
There is also Google Docs AMP deployed separately in ACS Share. The Share Google Docs AMP version is reported in `Share Admin Tools > Module Browser`. The Repository and Share AMP versions should be the same, e.g. `Version 3.1.0` in the same Alfresco instance.

### Enable/Disable
It may be necessary for the Alfresco Administrator to disable the ACS Google Docs integration for business or security reasons.

In containerized and zip ACS deployments, the integration to Google Docs is enabled out of the box by default. It can be disabled here by simply clearing  `Google Docs Enabled`. If this is disabled and a `Save` selected, then the `Edit in Google Docs` link is disabled for existing Share sessions, and completely removed from new Alfresco Share sessions.

### Google Docs Idle Threshold

The default value (600 seconds) listed here may need to be changed, but in most cases the default works fine. It may need changing if users collaborating on a document being edited in Google Docs are seeing their changes missed or overwritten when the document is saved by another user in Share. In this case the Administrator can consider changing the value. Changing the value here has an immediate effect.

### Google Docs Oauth Config
There is no value listed here by default as it will only be used when Alfresco developers are using the Google API to integrate ACS and Google Docs with a custom solution. Refer to [Authenticating Google Accounts with Alfresco Content Services](https://docs.alfresco.com/googledocs/tasks/googledocs-config-auth.html) for more information.
