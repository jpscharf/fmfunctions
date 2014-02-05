## fmfunctions

### A collection of FileMaker functions.

##### [date.modifyByDays ( theDate; daysToModify )](date.modifyByDays.fmfn)
`Change the provided date, using the provided number of days.`

##### [field.getFieldName ( theFQFN; useQuotes )](field.getFieldName.fmfn)
`Extracts the field name from the FQFN (Fully Qualified Field Name).`

##### [field.getTableName ( theFQFN; useQuotes )](field.getFieldName.fmfn)
`Extracts the table name from the FQFN (Fully Qualified Field Name).`

##### [format.currency ( theNumber; decimalSeparator; thousandsDelimiter; currencySymbol, trailingCurrencySymbol )](format.currency.fmfn)
`Format as currency.`

>**Dependancies:** 

>[text.split](text.split.fmfn)

>[list.implode](list.implode.fmfn)

##### [get.platformAsText ( OSPlatform; OSVersion; appVersion )](get.platformAsText.fmfn)
`Get the system platform as a human readable text string.`

##### [list.diff ( list1; list2 )](list.diff.fmfn)
`Returns a list of values that are in list1 but not in list2.`

##### [list.implode ( glue; values )](list.implode.fmfn)
`Joins the values (list) with the provided glue (text).`

##### [list.in_list ( needle; haystack )](list.in_list.fmfn)
`Will determine if a value (needle) exists in the provided list (haystack).`

##### [list.position ( values; search )](list.position.fmfn)
`Returns the numerical position of the supplied value`

##### [list.in_list ( needle; haystack )](list.in_list.fmfn)
`Will return the index of the matching value (needle) in the list (haystack).`

##### [list.trim ( values )](list.trim.fmfn)
`Remove blank list items.`

##### [list.unique ( values )](list.unique.fmfn)
`Removes duplicate values from the list.`

##### [text.explode ( theDelimiter; theText )](text.explode.fmfn) **UPDATE - Major Bug Fixed** (January 23, 2013)
`Splits a string using the delimiter into a list.`

##### [text.fixedLength ( theText; thePaddingChar; theAlignment; theFixedLength )](text.fixedLength.fmfn)
`Fixed length text, padded and aligned.`

##### [text.pathsafe ( text )](text.pathsafe.fmfn)
`Converts a text string to a path safe string.`

##### [text.split ( theText; theLength )](text.split.fmfn)
`Converts a string into a list, using the provided length.`

##### [number.countWeekdays ( startDate; endDate )](number.countWeekdays.fmfn)
`Counts the number of weekdays within a date range.`

-
**NOTICE**: If you began using the text.explode function prior to January 23, 2013, there was a bug that broke the function if the theDelimiter = ¶, or the delimiterLength > 1.