# FileMaker Custom Function Guideline #

### General Header Format ###
````
/*
@description A description of the custom function, what it does.
@author Jason P. Scharf

@name text.explode ( theDelimiter; theText )

@param {text}	theDelimiter	param description goes here
@param {text}	theText 		param description goes here

@returns List

@requires NONE

@reference Modeled after PHP's explode: http://us.php.net/manual/en/function.explode.php

@note If the provided delimiter is a ¶ the function will return the original text. Also,
it will strip any existing ¶ as they would be ambiguous.

@log 2012-09-12, JPS, Created.
*/
````

### Parameter Delimitation ###

**Basic:**
````
@param paramOne
@param paramTwo
@param paramThree
````

**XML/plist:**
````
<params>
	<string>paramOne</string>
	<string>paramTwo</string>
	<string>paramThree<string>
</params>
````

**JSON:**
````
{
   "params":[
      "paramOne",
      "paramTwo",
      "paramThree"
   ]
}
````