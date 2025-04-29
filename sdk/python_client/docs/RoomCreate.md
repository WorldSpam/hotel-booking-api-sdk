# RoomCreate


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**number** | **str** |  | 
**type** | **str** |  | 
**price** | **float** |  | 

## Example

```python
from hotel_sdk.models.room_create import RoomCreate

# TODO update the JSON string below
json = "{}"
# create an instance of RoomCreate from a JSON string
room_create_instance = RoomCreate.from_json(json)
# print the JSON string representation of the object
print(RoomCreate.to_json())

# convert the object into a dict
room_create_dict = room_create_instance.to_dict()
# create an instance of RoomCreate from a dict
room_create_from_dict = RoomCreate.from_dict(room_create_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


