---
external help file: pshtml-help.xml
Module Name: PSHTML
online version:
schema: 2.0.0
---

# a

## SYNOPSIS
Generates a a HTML tag.

## SYNTAX

```
a [[-Content] <ScriptBlock>] [[-Class] <String>] [[-Id] <String>] [[-Style] <String>]
 [[-Attributes] <Hashtable>] -href <String> [-Target <String>] [<CommonParameters>]
```

## DESCRIPTION
{{Fill in the Description}}

## EXAMPLES

### EXAMPLE 1
```
The following exapmles show cases how to create an empty a, with a class, an ID, and, custom attributes.
```

a -Class "myclass1 MyClass2" -Id myid -Attributes @{"custom1"='val1';custom2='val2'}

Generates the following code:

\<a Class="myclass1 MyClass2" Id="myid" custom1="val1" custom2="val2"  \>
\</a\>

## PARAMETERS

### -Content
Allows to add child element(s) inside the current opening and closing HTML tag(s).

```yaml
Type: ScriptBlock
Parameter Sets: (All)
Aliases:

Required: False
Position: 1
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -Class
Allows to specify one (or more) class(es) to assign the html element.
More then one class can be assigned by seperating them with a white space.

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: 2
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Id
Allows to specify an id to assign the html element.

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: 3
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Style
Allows to specify in line CSS style to assign the html element.

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: 4
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Attributes
{{Fill Attributes Description}}

```yaml
Type: Hashtable
Parameter Sets: (All)
Aliases:

Required: False
Position: 5
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -href
{{Fill href Description}}

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Target
{{Fill Target Description}}

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: _self
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable.
For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES
Current version 1.0
History:
    2018.04.10;Stephanevg; Added parameters
    2018.04.01;Stephanevg;Creation.

## RELATED LINKS
