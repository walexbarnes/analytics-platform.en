---
description: Manage logs for existing exports
keywords: Analysis Workspace
title: Troubleshoot failed exports
feature: Components
hide: yes
hidefromtoc: yes
---
# Troubleshoot failed exports

When you [export full tables from Analysis Workspace to cloud destinations](/help/analysis-workspace/export/export-cloud.md), you can view the status of those exports both from the [Exports tab](/help/components/exports/manage-exports.md) and from the [Logs tab](/help/components/exports/manage-export-logs.md). Failed exports show a status of [!UICONTROL **Failed**].

## Common failures and actions

Exports can fail for various reasons. The following table describes some of the most common reasons, with actions you can take to address the failures:

|Reason for failure | Suggested action | More information |
|---------|----------|---------|
| Invalid location or account information | Make sure your credentials and other information is correct for the cloud account and location you are exporting to. | [Configure cloud export accounts](/help/components/exports/cloud-export-accounts.md) and [Configure cloud export locations](/help/components/exports/cloud-export-locations.md). |
| A dimension or metric in the report was removed from the data view | Contact your system administrator to see which components were removed from the data view. You might need to use a different data view in your export, or remove components from your table that are no longer available.  | [Export Customer Journey Analytics reports to the cloud](/help/analysis-workspace/export/export-cloud.md) |
| A data governance policy that is enforced by your organization restricts components in your table from being exported | Contact your system administrator to see which components are restricted from being exported. Remove the restricted components prior to exporting. | *Filter on Data Governance policies in data views* section in [Labels and policies](/help/data-views/data-governance.md) | 

## Contact Adobe Customer Care

If you continue to experience issues, contact Adobe Customer Care. When contacting customer care regarding a failed export, make sure you have the following information available:

* Export name

* Export ID

* Instance ID

* Data view name

* Location

* Account

* Company Name

* Connection

* Data View