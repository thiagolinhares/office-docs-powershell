---
applicable: Exchange Server 2010, Exchange Server 2013, Exchange Server 2016
schema: 2.0.0
---

# Get-EdgeSyncServiceConfig

## SYNOPSIS
!!! Exchange Server 2010

Use the Get-EdgeSyncServiceConfig cmdlet to retrieve the edge synchronization services settings that control the general synchronization behavior shared by all Microsoft Exchange EdgeSync services.

!!! Exchange Server 2013, Exchange Server 2016

This cmdlet is available only in on-premises Exchange.

Use the Get-EdgeSyncServiceConfig cmdlet to retrieve the edge synchronization services settings that control the general synchronization behavior shared by all Microsoft Exchange EdgeSync services.

## SYNTAX

```
Get-EdgeSyncServiceConfig [[-Identity] <EdgeSyncServiceConfigIdParameter>] [-DomainController <Fqdn>]
 [-Site <AdSiteIdParameter>] [<CommonParameters>]
```

## DESCRIPTION
!!! Exchange Server 2010

You need to be assigned permissions before you can run this cmdlet. Although all parameters for this cmdlet are listed in this topic, you may not have access to some parameters if they're not included in the permissions assigned to you. To see what permissions you need, see the "EdgeSync" entry in the Transport Permissions topic.

!!! Exchange Server 2013

You need to be assigned permissions before you can run this cmdlet. Although all parameters for this cmdlet are listed in this topic, you may not have access to some parameters if they're not included in the permissions assigned to you. To see what permissions you need, see the "EdgeSync" entry in the Mail flow permissions topic.

!!! Exchange Server 2016

You need to be assigned permissions before you can run this cmdlet. Although this topic lists all parameters for the cmdlet, you may not have access to some parameters if they're not included in the permissions assigned to you. To find the permissions required to run any cmdlet or parameter in your organization, see Find the permissions required to run any Exchange cmdlet (https://technet.microsoft.com/library/mt432940.aspx).

## EXAMPLES

### Example 1 -------------------------- (Exchange Server 2010)
```
Get-EdgeSyncServiceConfig "Primary EdgeSync Settings" | Format-List
```

This example reads the configuration of the Microsoft Exchange EdgeSync service settings Primary EdgeSync Settings from Active Directory and displays all its properties in a list format.

### Example 1 -------------------------- (Exchange Server 2013)
```
Get-EdgeSyncServiceConfig "Primary EdgeSync Settings" | Format-List
```

This example reads the configuration of the Microsoft Exchange EdgeSync service settings named Primary EdgeSync Settings from Active Directory and displays all its properties in a list format.

### Example 1 -------------------------- (Exchange Server 2016)
```
Get-EdgeSyncServiceConfig "Primary EdgeSync Settings" | Format-List
```

This example reads the configuration of the Microsoft Exchange EdgeSync service settings named Primary EdgeSync Settings from Active Directory and displays all its properties in a list format.

## PARAMETERS

### -Identity
The Identity parameter specifies the name of the Microsoft Exchange EdgeSync service configuration you want to view.

```yaml
Type: EdgeSyncServiceConfigIdParameter
Parameter Sets: (All)
Aliases:
Applicable: Exchange Server 2010, Exchange Server 2013, Exchange Server 2016

Required: False
Position: 1
Default value: None
Accept pipeline input: True
Accept wildcard characters: False
```

### -DomainController
The DomainController parameter specifies the domain controller that's used by this cmdlet to read data from or write data to Active Directory. You identify the domain controller by its fully qualified domain name (FQDN). For example, dc01.contoso.com.

```yaml
Type: Fqdn
Parameter Sets: (All)
Aliases:
Applicable: Exchange Server 2010, Exchange Server 2013, Exchange Server 2016

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Site
The Site parameter specifies the Active Directory site that EdgeSync connects to for synchronizing configuration and recipient data.

```yaml
Type: AdSiteIdParameter
Parameter Sets: (All)
Aliases:
Applicable: Exchange Server 2010, Exchange Server 2013, Exchange Server 2016

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (https://go.microsoft.com/fwlink/p/?LinkID=113216).

## INPUTS

###  
To see the input types that this cmdlet accepts, see Cmdlet Input and Output Types (https://go.microsoft.com/fwlink/p/?LinkId=616387). If the Input Type field for a cmdlet is blank, the cmdlet doesn't accept input data.

## OUTPUTS

###  
To see the return types, which are also known as output types, that this cmdlet accepts, see Cmdlet Input and Output Types (https://go.microsoft.com/fwlink/p/?LinkId=616387). If the Output Type field is blank, the cmdlet doesn't return data.

## NOTES

## RELATED LINKS

[Online Version](https://technet.microsoft.com/library/0864f701-484d-4a57-9291-ea63e25c1f1b.aspx)
