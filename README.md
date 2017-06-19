# Docusign-custom-buttons


Create custom buttons in Docusign extension.

1. Click the Settings Icon(Setup) -> Customization -> Modules -> Select the Module to which the Custom Button have to be create -> Layout -> Links and Buttons -> Create New Button.
2. Give the Name of the Button.
3. Add Description if you want.
4. Select the button to be placed.
5. Select "Invoke a URL" to perform the action.
6. Given the below URL in Construct Your URL :
 
https://extensions.zoho.com/plugin/docusign/handler?action=createenvelope&module=Module Name&rec_id=${Module.Module Id}&rec_name=${Module.Module Name}

For Ex : https://extensions.zoho.com/plugin/docusign/handler?action=createenvelope&module=Leads&rec_id=${Leads.Lead Id}&rec_name=${Leads.Last Name}
 
7. Select the button on Where to show the content of the button action.
8. Select Which Profiles to show this action.
9. Click Save.
