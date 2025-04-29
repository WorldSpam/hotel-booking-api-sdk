# HotelUpdate


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | [optional] 
**address** | **str** |  | [optional] 
**rating** | **float** |  | [optional] 

## Example

```python
from hotel_sdk.models.hotel_update import HotelUpdate

# TODO update the JSON string below
json = "{}"
# create an instance of HotelUpdate from a JSON string
hotel_update_instance = HotelUpdate.from_json(json)
# print the JSON string representation of the object
print(HotelUpdate.to_json())

# convert the object into a dict
hotel_update_dict = hotel_update_instance.to_dict()
# create an instance of HotelUpdate from a dict
hotel_update_from_dict = HotelUpdate.from_dict(hotel_update_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


