# HotelCreate


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**address** | **str** |  | 
**rating** | **float** |  | [optional] 

## Example

```python
from hotel_sdk.models.hotel_create import HotelCreate

# TODO update the JSON string below
json = "{}"
# create an instance of HotelCreate from a JSON string
hotel_create_instance = HotelCreate.from_json(json)
# print the JSON string representation of the object
print(HotelCreate.to_json())

# convert the object into a dict
hotel_create_dict = hotel_create_instance.to_dict()
# create an instance of HotelCreate from a dict
hotel_create_from_dict = HotelCreate.from_dict(hotel_create_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


