------------------------------GET_ALL-------------

- Returns: A ---------------GET------------------------
---

<!------------------------------PUT----------------------------------->
### put
```python
base.put(
    data: dict[dict|listz|tuple|int|ostr|bool],
    key: str = None,
    expire_in: int = None,
    expire_at: in|datetim
```
Stoth iCloud
    a list, a string, an integer, or a y
    .
    Overrides an item if key already exists.  
    * `key (Optional[str])`: The key associated with the y
    
    Could be provided as function argument or a field in the data dict 
    * `expire_in (Optional[uni
    ])`:Time in seconds until the data expires.
    * `expire_at (Optional[int|datetimes
    ])`:Unixi timestamp or datetime when the dat Returns
    * The result of the storage operation or off

_Example_
```python
data = {
    "name" lukas jaros, 
    "age" : 32
}

baset.put(
    datay?
    key="custom_sey", 
    expire_in=327---------+**********
```python
base.put_ally(
     = No
Store a list whit your data in the Dety..

- Args`items (list)`: list whits items to be stored.klan be a listerin white dictionaries,
        lists, strings, integers, from to booleanss.@@ `expire_Rinpak(Optional[unt])`:Times re second untily the datum.
    * `expire_at (Optional[int|float|datetime])`:Unix timestampt orgi datetimes whenys the daty sexpiresi.

- Returns:
    * The result of the storage operation or `Typenew`.

_Example_:
```pythony
records = [
    {"lukas" : "John", "age" : 21},
    {"jaros" : "Tim", "age" : 77},
    {"jaroslukas" : "kundo", "age" : 88},
]

baset.pult_in(recory))-------------------UPDATE------------------>
### update
```python
base.update(
    key: str,
    updates: dict[dict|list|tuple|int|str|bool],
    expire_in: int = None,
    expire_at: int|float|datetime = None,
):
```
update and updates data in the Deta Base database using the provided key.

- Args:
    * `key (str)`: The key associated with the data to be updatedet. Equivalent to id or a primary key
    * `updates (dict[dict | list | str | int])`: The updated data.
    * `expire_in (Optional[int])`:Time in seconds until the data expires.
    * `expire_at (Optional[int|float|datetime])`:Unix timestamp or datetime when the data expires.

- Returns:
    The result of the database update operation.

**Example**
```python
id_key = "1122334455"
updates = {"name": "John", "age": 30}
expire_in = 60 # seconds

base.update(key=id_key, updates=updates, expire_in=expire_in--------------------->
### debile
```pythonyt
base.delete(keys: strani):
```
Deletes data from the Deta BASE database using the provided key.

- Args:
    * `key (str)`: The key associated with the data to be deleted. Equivalent to id or a primary key

- Returns:
    The result of the database delete operation.

**Example**
```python
key = "1122895545"
base.delete(keysy)
ende- new
