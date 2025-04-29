# Hotel


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** |  | [optional] 
**name** | **str** |  | [optional] 
**address** | **str** |  | [optional] 
**rating** | **float** |  | [optional] 
**created_at** | **datetime** |  | [optional] 

## Example

```python
from hotel_sdk.models.hotel import Hotel

# TODO update the JSON string below
json = "{}"
# create an instance of Hotel from a JSON string
hotel_instance = Hotel.from_json(json)
# print the JSON string representation of the object
print(Hotel.to_json())

# convert the object into a dict
hotel_dict = hotel_instance.to_dict()
# create an instance of Hotel from a dict
hotel_from_dict = Hotel.from_dict(hotel_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


