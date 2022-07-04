# Python Cheat Sheet


## Dictionary 

Example `MyDict = {1:True,2:False,3:None} Key = (1,2,3) Value = 0`
|Method|Parameter Explain| Sample Code| Effect |Description|
|:---:|:---:|:---:|:----:|:----:|
|clear()| N.A|MyDict.clear()|MyDict: {}|Removes all the elements from the dictionary|
|copy() |N.A|Clone = MyDict.copy()|Clone: {1:True,2:False,3:None}|Returns a copy of the dictionary|
|fromkeys(Key,Value)|Keys[iterable]: Required, The set of Key\| Value[any]:Optional[None] The value for all Key |Newdict = dict.fromkeys(Key,Value)|Newdict: {1:0,2:0,3:0}|Returns a dictionary with the specified keys and value|
|get(keyname, value)|Keyname[any]: Required\| value[any]: Optional[None], default value for cannot find |MyDict.get(1)|Return: True|Returns the value of the specified key|
|items()|N.A|Mydict.items()|Return:[(1,True),(2,False),(3,None)]|Returns a list containing a tuple for each key value pair|
|keys()|N.A|Mydict.keys()|Return: [1,2,3]|Returns a list containing the dictionary's keys|
|pop(keyname, defaultvalue)|Keyname[any]: Required\| defaultvalue[any]: Optional[], error would be raise if not default value is set and not fojnd | Mydict.pop(1) \| Mydict.pop(4,-1)|Return: True; MyDict:{1:True,2:False}\| -1;Unchanged|Removes the element with the specified key|
|popitem()|N.A|MyDict.popitem()|Return: (|Removes the last inserted key-value pair|
|setdefault()||||Returns the value of the specified key. If the key does not exist: insert the key, with the specified value|
|update()||||Updates the dictionary with the specified key-value pairs|
|values()||||Returns a list of all the values in the dictionary|