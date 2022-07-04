# Python Cheat Sheet


## Dictionary 

Example `MyDict = {1:True,2:False,3:None} Key = (1,2,3) Value = 0`
|Method|Parameter Explain| Description|Sample Code| Effect |
|:---:|:---:|:---:|:----:|:----:|
|clear()| N.A|Removes all the elements from the dictionary|MyDict.clear()|MyDict: {}|
|copy() |N.A|Returns a copy of the dictionary|Clone = MyDict.copy()|Clone: {1:True,2:False,3:None}|
|fromkeys(Key,Value)|Keys[iterable]: Required, The set of Key\| Value[any]:Optional[None] The value for all Key |Returns a dictionary with the specified keys and value|Newdict = dict.fromkeys(Key,Value)|Newdict: {1:0,2:0,3:0}|
|get(keyname, value)|Keyname: Required\| value[any]: Optional[None], default value for cannot find |Returns the value of the specified key|||
|item()| |Returns a list containing a tuple for each key value pair|||
|keys()||Returns a list containing the dictionary's keys|||
|pop()||Removes the element with the specified key|||
|popitem()||Removes the last inserted key-value pair|||
|setdefault()||Returns the value of the specified key. If the key does not exist: insert the key, with the specified value|||
|update()||Updates the dictionary with the specified key-value pairs|||
|values()||Returns a list of all the values in the dictionary|||