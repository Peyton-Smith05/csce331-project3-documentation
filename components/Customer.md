# Customer

## Data

<!-- @vuese:Customer:data:start -->
|Name|Type|Description|Default|
|---|---|---|---|
|orderedItems|`Array`|An array to store the ordered items.|-|
|empid|`Number`|Employee ID associated with the order.|0|
|filteredMenuItems|`Array`|An array of filtered menu items based on the selected category.|-|
|selectedCategory|`Number`|ID of the currently selected category.|0|
|respond|`Array`|An array to store response data from category API calls.|-|
|respondItems|`Array`|An array to store response data from menu item API calls.|-|
|itemsID|`Number`|A counter to assign unique IDs to ordered items.|0|
|selectedItem|`Object`|An object representing the menu item currently selected by the user. Contains details like id, name, price, category, and customization options like size, sugar level, etc.|-|

<!-- @vuese:Customer:data:end -->


