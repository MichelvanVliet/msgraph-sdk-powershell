---
external help file:
Module Name: Microsoft.Graph.Education
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.education/update-mgeducationmeusermailboxsetting
schema: 2.0.0
---

# Update-MgEducationMeUserMailboxSetting

## SYNOPSIS
Update property mailboxSettings value.

## SYNTAX

### UpdateExpanded1 (Default)
```
Update-MgEducationMeUserMailboxSetting [-AdditionalProperties <Hashtable>] [-ArchiveFolder <String>]
 [-AutomaticRepliesSetting <IMicrosoftGraphAutomaticRepliesSetting>] [-DateFormat <String>]
 [-DelegateMeetingMessageDeliveryOptions <String>] [-Language <IMicrosoftGraphLocaleInfo>]
 [-TimeFormat <String>] [-TimeZone <String>] [-UserPurpose <String>]
 [-WorkingHours <IMicrosoftGraphWorkingHours>] [-PassThru] [-Confirm] [-WhatIf] [<CommonParameters>]
```

### Update1
```
Update-MgEducationMeUserMailboxSetting -BodyParameter <IMicrosoftGraphMailboxSettings1> [-PassThru] [-Confirm]
 [-WhatIf] [<CommonParameters>]
```

## DESCRIPTION
Update property mailboxSettings value.

## EXAMPLES

## PARAMETERS

### -AdditionalProperties
Additional Parameters

```yaml
Type: System.Collections.Hashtable
Parameter Sets: UpdateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ArchiveFolder
Folder ID of an archive folder for the user.

```yaml
Type: System.String
Parameter Sets: UpdateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AutomaticRepliesSetting
automaticRepliesSetting
To construct, please use Get-Help -Online and see NOTES section for AUTOMATICREPLIESSETTING properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphAutomaticRepliesSetting
Parameter Sets: UpdateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -BodyParameter
mailboxSettings
To construct, please use Get-Help -Online and see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphMailboxSettings1
Parameter Sets: Update1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -DateFormat
The date format for the user's mailbox.

```yaml
Type: System.String
Parameter Sets: UpdateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DelegateMeetingMessageDeliveryOptions
delegateMeetingMessageDeliveryOptions

```yaml
Type: System.String
Parameter Sets: UpdateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Language
localeInfo
To construct, please use Get-Help -Online and see NOTES section for LANGUAGE properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphLocaleInfo
Parameter Sets: UpdateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
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

### -TimeFormat
The time format for the user's mailbox.

```yaml
Type: System.String
Parameter Sets: UpdateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -TimeZone
The default time zone for the user's mailbox.

```yaml
Type: System.String
Parameter Sets: UpdateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -UserPurpose
.

```yaml
Type: System.String
Parameter Sets: UpdateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -WorkingHours
workingHours
To construct, please use Get-Help -Online and see NOTES section for WORKINGHOURS properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphWorkingHours
Parameter Sets: UpdateExpanded1
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

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphMailboxSettings1

## OUTPUTS

### System.Boolean

## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


AUTOMATICREPLIESSETTING <IMicrosoftGraphAutomaticRepliesSetting>: automaticRepliesSetting
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[ExternalAudience <String>]`: externalAudienceScope
  - `[ExternalReplyMessage <String>]`: The automatic reply to send to the specified external audience, if Status is AlwaysEnabled or Scheduled.
  - `[InternalReplyMessage <String>]`: The automatic reply to send to the audience internal to the signed-in user's organization, if Status is AlwaysEnabled or Scheduled.
  - `[ScheduledEndDateTime <IMicrosoftGraphDateTimeZone>]`: dateTimeTimeZone
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[DateTime <String>]`: A single point of time in a combined date and time representation ({date}T{time}; for example, 2017-08-29T04:00:00.0000000).
    - `[TimeZone <String>]`: Represents a time zone, for example, 'Pacific Standard Time'. See below for more possible values.
  - `[ScheduledStartDateTime <IMicrosoftGraphDateTimeZone>]`: dateTimeTimeZone
  - `[Status <String>]`: automaticRepliesStatus

BODYPARAMETER <IMicrosoftGraphMailboxSettings1>: mailboxSettings
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[ArchiveFolder <String>]`: Folder ID of an archive folder for the user.
  - `[AutomaticRepliesSetting <IMicrosoftGraphAutomaticRepliesSetting>]`: automaticRepliesSetting
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[ExternalAudience <String>]`: externalAudienceScope
    - `[ExternalReplyMessage <String>]`: The automatic reply to send to the specified external audience, if Status is AlwaysEnabled or Scheduled.
    - `[InternalReplyMessage <String>]`: The automatic reply to send to the audience internal to the signed-in user's organization, if Status is AlwaysEnabled or Scheduled.
    - `[ScheduledEndDateTime <IMicrosoftGraphDateTimeZone>]`: dateTimeTimeZone
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[DateTime <String>]`: A single point of time in a combined date and time representation ({date}T{time}; for example, 2017-08-29T04:00:00.0000000).
      - `[TimeZone <String>]`: Represents a time zone, for example, 'Pacific Standard Time'. See below for more possible values.
    - `[ScheduledStartDateTime <IMicrosoftGraphDateTimeZone>]`: dateTimeTimeZone
    - `[Status <String>]`: automaticRepliesStatus
  - `[DateFormat <String>]`: The date format for the user's mailbox.
  - `[DelegateMeetingMessageDeliveryOptions <String>]`: delegateMeetingMessageDeliveryOptions
  - `[Language <IMicrosoftGraphLocaleInfo>]`: localeInfo
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[DisplayName <String>]`: A name representing the user's locale in natural language, for example, 'English (United States)'.
    - `[Locale <String>]`: A locale representation for the user, which includes the user's preferred language and country/region. For example, 'en-us'. The language component follows 2-letter codes as defined in ISO 639-1, and the country component follows 2-letter codes as defined in ISO 3166-1 alpha-2.
  - `[TimeFormat <String>]`: The time format for the user's mailbox.
  - `[TimeZone <String>]`: The default time zone for the user's mailbox.
  - `[UserPurpose <String>]`: 
  - `[WorkingHours <IMicrosoftGraphWorkingHours>]`: workingHours
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[DaysOfWeek <String[]>]`: The days of the week on which the user works.
    - `[EndTime <String>]`: The time of the day that the user stops working.
    - `[StartTime <String>]`: The time of the day that the user starts working.
    - `[TimeZone <IMicrosoftGraphTimeZoneBase>]`: timeZoneBase
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[Name <String>]`: The name of a time zone. It can be a standard time zone name such as 'Hawaii-Aleutian Standard Time', or 'Customized Time Zone' for a custom time zone.

LANGUAGE <IMicrosoftGraphLocaleInfo>: localeInfo
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[DisplayName <String>]`: A name representing the user's locale in natural language, for example, 'English (United States)'.
  - `[Locale <String>]`: A locale representation for the user, which includes the user's preferred language and country/region. For example, 'en-us'. The language component follows 2-letter codes as defined in ISO 639-1, and the country component follows 2-letter codes as defined in ISO 3166-1 alpha-2.

WORKINGHOURS <IMicrosoftGraphWorkingHours>: workingHours
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[DaysOfWeek <String[]>]`: The days of the week on which the user works.
  - `[EndTime <String>]`: The time of the day that the user stops working.
  - `[StartTime <String>]`: The time of the day that the user starts working.
  - `[TimeZone <IMicrosoftGraphTimeZoneBase>]`: timeZoneBase
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[Name <String>]`: The name of a time zone. It can be a standard time zone name such as 'Hawaii-Aleutian Standard Time', or 'Customized Time Zone' for a custom time zone.

## RELATED LINKS

