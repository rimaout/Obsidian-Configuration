Status: #Complete
Created: June 14, 2023
Tag: [[Python MOC]], [[Python Dictionaries]]

---
**Index:**
1. [[Python Dictionary get() Method#Definition|Definition]]
2. [[Python Dictionary get() Method#Syntax|Syntax]]
3. [[Python Dictionary get() Method#Parameter Values|Parameter Values]]
4. [[Python Dictionary get() Method#Return Values|Return Values]]
5. [[Python Dictionary get() Method#Python get() method Vs dict [key ] to Access Elements|Python get() Vs dict [key] ]]

---
## Definition 
The `get()` method returns the value of the item with the specified key.

---
## Syntax
`dictionary.get(keyname, value)`

---
## Parameter Values

|Parameter|Description|
|---|---|
|_keyname_|Required. The keyname of the item you want to return the value from|
|_value_|Optional. A value to return if the specified key does not exist.  <br>Default value None|

---
## Return Values
- the value for the specified key if key is in the dictionary.
- None if the key is not found and value is not specified.
- value if the key is not found and value is specified.


**Example:**
```Python
car = {
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}

x = car.get("model")
y = car.get("price", 15000)  
  
print(x) # OutPut: "Ford"
print(y) # OutPut: "15000"
```

---
## Python get() method Vs dict \[key\] to Access Elements

`get()` method returns a default value if the `key` is missing.

However, if the key is not found when you use `dict[key]`, `KeyError` exception is raised.

```python
person = {}

# Using get() results in None
print('Salary: ', person.get('salary'))


# Using [] results in KeyError
print(person['salary'])
```

**Output:**
```python
Salary:  None
Traceback (most recent call last):
  File "", line 7, in 
    print(person['salary'])
KeyError: 'salary'
```
