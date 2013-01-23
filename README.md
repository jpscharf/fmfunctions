##fmfunctions

###A collection of FileMaker functions.

#####[field.getFieldName ( theFQFN; useQuotes )](https://github.com/jpscharf/fmfunctions/blob/master/field.getFieldName.fmfn)
`Extracts the field name from the FQFN (Fully Qualified Field Name).`

#####[field.getTableName ( theFQFN; useQuotes )](https://github.com/jpscharf/fmfunctions/blob/master/field.getFieldName.fmfn)
`Extracts the table name from the FQFN (Fully Qualified Field Name).`

#####[format.currency ( theNumber; decimalSeparator; thousandsDelimiter; currencySymbol, trailingCurrencySymbol )](https://github.com/jpscharf/fmfunctions/blob/master/format.currency.fmfn)
`Format as currency.`

>**Dependancies:** 

>[text.split](fmfunctions/blob/master/text.split.fmfn)

>[list.implode](fmfunctions/blob/master/list.implode.fmfn)

#####[list.diff ( list1; list2 )](https://github.com/jpscharf/fmfunctions/blob/master/list.diff.fmfn)
`Returns a list of values that are in list1 but not in list2.`

#####[list.implode ( glue; values )](https://github.com/jpscharf/fmfunctions/blob/master/list.implode.fmfn)
`Joins the values (list) with the provided glue (text).`

#####[list.in_list ( needle; haystack )](https://github.com/jpscharf/fmfunctions/blob/master/list.in_list.fmfn)
`Will determine if a value (needle) exists in the provided list (haystack).`

#####[list.position ( values; search )](https://github.com/jpscharf/fmfunctions/blob/master/list.position.fmfn)
`Returns the numerical position of the supplied value`

#####[list.trim ( values )](https://github.com/jpscharf/fmfunctions/blob/master/list.trim.fmfn)
`Remove blank list items.`

#####[list.unique ( values )](https://github.com/jpscharf/fmfunctions/blob/master/list.unique.fmfn)
`Removes duplicate values from the list.`

#####[text.explode ( theDelimiter; theText )](https://github.com/jpscharf/fmfunctions/blob/master/text.explode.fmfn) **UPDATE - Major Bug Fixed** (January 23, 2013)
`Splits a string using the delimiter into a list.`

#####[text.pathsafe ( text )](https://github.com/jpscharf/fmfunctions/blob/master/text.pathsafe.fmfn)
`Converts a text string to a path safe string.`

#####[text.split ( theText; theLength )](https://github.com/jpscharf/fmfunctions/blob/master/text.split.fmfn)
`Converts a string into a list, using the provided length.`

-
**NOTICE**: If you began using the text.explode function prior to January 23, 2013, there was a bug that broke the function if the theDelimiter = ¶, or the delimiterLength > 1.