# adb-arm-templates-ext
Specific / Nuanced ARM Templates for Azure Databricks Workspace Provisioning

Following types of templates are available here:
* Ones with LRS DBFS (as default is GRS) - with databricks-managed VNET and with VNET Injection (Bring your own VNET - also includes No Public IP variant)
* Ones with Audit Logs - with databricks-managed VNET and with VNET Injection (Bring your own VNET - also includes No Public IP variants)

*Note:* No Public IP variant is a private preview feature that is available only after Databricks has qualified / validated the requirements. It needs whitelisting of particular Azure subscriptions. Please reach out to your MSFT or Databricks account team for access to the preview.

