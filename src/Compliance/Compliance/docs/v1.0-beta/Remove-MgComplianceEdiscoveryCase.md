---
external help file:
Module Name: Microsoft.Graph.Compliance
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.compliance/remove-mgcomplianceediscoverycase
schema: 2.0.0
---

# Remove-MgComplianceEdiscoveryCase

## SYNOPSIS
Delete navigation property cases for compliance

## SYNTAX

### Delete (Default)
```
Remove-MgComplianceEdiscoveryCase -CaseId <String> [-IfMatch <String>] [-PassThru] [-Confirm] [-WhatIf]
 [<CommonParameters>]
```

### DeleteViaIdentity
```
Remove-MgComplianceEdiscoveryCase -InputObject <IComplianceIdentity> [-IfMatch <String>] [-PassThru]
 [-Confirm] [-WhatIf] [<CommonParameters>]
```

## DESCRIPTION
Delete navigation property cases for compliance

## EXAMPLES

### Example 1: Using the Remove-MgComplianceEdiscoveryCase Cmdlet
```powershell
Import-Module Microsoft.Graph.Compliance
Remove-MgComplianceEdiscoveryCase -CaseId $caseId
```

This example shows how to use the Remove-MgComplianceEdiscoveryCase Cmdlet.
To learn about permissions for this resource, see the [permissions reference](/graph/permissions-reference).

## PARAMETERS

### -CaseId
The unique identifier of case

```yaml
Type: System.String
Parameter Sets: Delete
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -IfMatch
ETag

```yaml
Type: System.String
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -InputObject
Identity Parameter
To construct, please use Get-Help -Online and see NOTES section for INPUTOBJECT properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IComplianceIdentity
Parameter Sets: DeleteViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -PassThru
Returns true when the command succeeds

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Confirm
Prompts you for confirmation before running the cmdlet.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: (All)
Aliases: cf

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -WhatIf
Shows what would happen if the cmdlet runs.
The cmdlet is not run.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: (All)
Aliases: wi

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### Microsoft.Graph.PowerShell.Models.IComplianceIdentity

## OUTPUTS

### System.Boolean

## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


INPUTOBJECT <IComplianceIdentity>: Identity Parameter
  - `[CaseId <String>]`: The unique identifier of case
  - `[CaseOperationId <String>]`: The unique identifier of caseOperation
  - `[CustodianId <String>]`: The unique identifier of custodian
  - `[DataSourceId <String>]`: The unique identifier of dataSource
  - `[LegalHoldId <String>]`: The unique identifier of legalHold
  - `[NoncustodialDataSourceId <String>]`: The unique identifier of noncustodialDataSource
  - `[ReviewSetId <String>]`: The unique identifier of reviewSet
  - `[ReviewSetQueryId <String>]`: The unique identifier of reviewSetQuery
  - `[SiteSourceId <String>]`: The unique identifier of siteSource
  - `[SourceCollectionId <String>]`: The unique identifier of sourceCollection
  - `[TagId <String>]`: The unique identifier of tag
  - `[TagId1 <String>]`: The unique identifier of tag
  - `[UnifiedGroupSourceId <String>]`: The unique identifier of unifiedGroupSource
  - `[UserSourceId <String>]`: The unique identifier of userSource

## RELATED LINKS

