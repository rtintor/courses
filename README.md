## 2.0.2.102 - Preview release of the AzureADPreview module

### Release status 

05/14/2020: Released for installation and upgrade from the [PowerShell Gallery](https://www.powershellgallery.com/packages/AzureADPreview/2.0.2.102)

### New features and improvements 

The following new cmdlets were added to the AzureADPreview module:

- `New-AzureADMSApplicationFromApplicationTemplate`
- `New-AzureADMSPermissionGrantConditionSet`
- `Get-AzureADMSPermissionGrantConditionSet`
- `Set-AzureADMSPermissionGrantConditionSet`
- `Remove-AzureADMSPermissionGrantConditionSet`
- `New-AzureADMSConditionalAccessPolicy`
- `Get-AzureADMSConditionalAccessPolicy`
- `Set-AzureADMSConditionalAccessPolicy`
- `Remove-AzureADMSConditionalAccessPolicy`
- `New-AzureADMSNamedLocationPolicy`
- `Get-AzureADMSNamedLocationPolicy`
- `Set-AzureADMSNamedLocationPolicy`
- `Remove-AzureADMSNamedLocationPolicy`

The new **New-AzureADMSApplicationFromApplicationTemplate** cmdlet creates a new application based on a applicationTemplate (Azure AD Gallery app or Non-Gallery)

The new **New-AzureADMSPermissionGrantConditionSet** cmdlet creates a new permission grant conditional set in Azure Active Directory.

The new **Set-AzureADMSPermissionGrantConditionSet** cmdlet updates the properties of a permission grant conditional set in Azure Active Directory.

The new **Remove-AzureADMSPermissionGrantConditionSet** cmdlet deletes an Azure Active Directory permission grant conditional set.

The new **Get-AzureADMSPermissionGrantConditionSet** cmdlet retrieves the list of Azure Active Directory permission grant conditional set.

The new **New-AzureADMSConditionalAccessPolicy** cmdlet creates a new conditional access policy in Azure Active Directory.

The new **Get-AzureADMSNamedLocationPolicy** cmdlet retrieves the list of Azure Active Directory conditional acces policies.

The new **Set-AzureADMSConditionalAccessPolicy** cmdlet updates the properties of a conditional access policy in Azure Active Directory.

The new **Remove-AzureADMSConditionalAccessPolicy** cmdlet deletes an Azure Active Directory conditional access policy.

The new **Get-AzureADMSNamedLocationPolicy** cmdlet retrieves the list of Azure Active Directory named location policies.

The new **New-AzureADMSNamedLocationPolicy** cmdlet creates a new named location policy in Azure Active Directory.

The new **Set-AzureADMSNamedLocationPolicy** cmdlet updates the properties of a named location policy in Azure Active Directory.

The new **Remove-AzureADMSNamedLocationPolicy** cmdlet deletes an Azure Active Directory named location policy.

### Minor breaking changes:
- The cmdlet `New-AzureADMSPermissionGrantPolicy` no longer support the parameters “includes” and “excludes”.
- The cmdlet `Set-AzureADMSPermissionGrantPolicy` no longer support the parameters “includes” and “excludes”.
