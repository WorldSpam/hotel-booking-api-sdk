# Room


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** |  | [optional] 
**hotel_id** | **str** |  | [optional] 
**number** | **str** |  | [optional] 
**type** | **str** |  | [optional] 
**price** | **float** |  | [optional] 
**status** | **str** |  | [optional] 

## Example

```python
from hotel_sdk.models.room import Room

# TODO update the JSON string below
json = "{}"
# create an instance of Room from a JSON string
room_instance = Room.from_json(json)
# print the JSON string representation of the object
print(Room.to_json())

# convert the object into a dict
room_dict = room_instance.to_dict()
# create an instance of Room from a dict
room_from_dict = Room.from_dict(room_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


