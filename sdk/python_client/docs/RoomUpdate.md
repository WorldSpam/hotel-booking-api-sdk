# RoomUpdate


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**number** | **str** |  | [optional] 
**type** | **str** |  | [optional] 
**price** | **float** |  | [optional] 
**status** | **str** |  | [optional] 

## Example

```python
from hotel_sdk.models.room_update import RoomUpdate

# TODO update the JSON string below
json = "{}"
# create an instance of RoomUpdate from a JSON string
room_update_instance = RoomUpdate.from_json(json)
# print the JSON string representation of the object
print(RoomUpdate.to_json())

# convert the object into a dict
room_update_dict = room_update_instance.to_dict()
# create an instance of RoomUpdate from a dict
room_update_from_dict = RoomUpdate.from_dict(room_update_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


