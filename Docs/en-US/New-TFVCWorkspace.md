---
external help file: TFVC-help.xml
Module Name: TFVC
online version:
schema: 2.0.0
---

# New-TFVCWorkspace

## SYNOPSIS

## SYNTAX

```
New-TFVCWorkspace [[-Name] <String>] [-TFVCSession <TFVCSession>] [-SetActiveWorkspace] [-WhatIf] [-Confirm]
 [<CommonParameters>]
```

## DESCRIPTION
{{Fill in the Description}}

## EXAMPLES

### EXAMPLE 1
```
New-TFVCWorkspace -Path $Path
```

## PARAMETERS

### -Name
Parameter help description

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: 1
Default value: "${env:COMPUTERNAME}-Default"
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -SetActiveWorkspace
{{Fill SetActiveWorkspace Description}}

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: False
Accept pipeline input: False
Accept wildcard characters: False
```

### -TFVCSession
Active TFVC Session

```yaml
Type: TFVCSession
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: (Get-TFVCSession)
Accept pipeline input: False
Accept wildcard characters: False
```

### -Confirm
Prompts you for confirmation before running the cmdlet.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: cf

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -WhatIf
Shows what would happen if the cmdlet runs. The cmdlet is not run.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: wi

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS
