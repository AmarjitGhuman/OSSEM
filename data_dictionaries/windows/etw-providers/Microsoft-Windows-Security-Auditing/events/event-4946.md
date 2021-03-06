# Event ID 4946: A change has been made to Windows Firewall exception list. A rule was added.
###### Version: 0

## Description
This event generates when new rule was locally added to Windows Firewall.

## Data Dictionary
|Standard Name|Field Name|Type|Description|Sample Value|
|---|---|---|---|---|
|profile_changed|ProfileChanged|UnicodeString|the list of profiles to which new rule was applied.|`All`|
|rule_id|RuleId|UnicodeString|the unique new firewall rule identifier.|`{F2649D59-1355-4E3C-B886-CDD08B683199}`|
|rule_name|RuleName|UnicodeString|the name of the rule which was added.|`Allow All Rule`|

## References
* [MS Source](https://github.com/MicrosoftDocs/windows-itpro-docs/blob/public/windows/security/threat-protection/auditing/event-4946.md)
* [MS Security Auditing Category - Policy Change](https://docs.microsoft.com/en-us/windows/security/threat-protection/auditing/advanced-security-audit-policy-settings#policy-change)
* [MS Security Auditing Sub-category - Audit MPSSVC Rule-Level Policy Change](https://github.com/MicrosoftDocs/windows-itpro-docs/tree/master/windows/security/threat-protection/auditing/audit-mpssvc-rule-level-policy-change.md)

## Tags
* etw_level_Informational
* etw_task_task_0
* Policy Change
* Audit MPSSVC Rule-Level Policy Change