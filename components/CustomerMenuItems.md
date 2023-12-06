# CustomerMenuItems

## Props

<!-- @vuese:CustomerMenuItems:props:start -->
|Name|Description|Type|Required|Default|
|---|---|---|---|---|
|filteredMenuItems|An array of menu items to be displayed in the grid. Passed as a prop from a parent component.|`Array`|`false`|[]|
|addToOrder|Text for the 'Add To Order' button. Can be customized through props.|`String`|`false`|Add To Order|

<!-- @vuese:CustomerMenuItems:props:end -->


## Events

<!-- @vuese:CustomerMenuItems:events:start -->
|Event Name|Description|Parameters|
|---|---|---|
|itemChosen|-|-|

<!-- @vuese:CustomerMenuItems:events:end -->


## Methods

<!-- @vuese:CustomerMenuItems:methods:start -->
|Method|Description|Parameters|
|---|---|---|
|redirectToToppings|Emits the 'itemChosen' event with the selected item and navigates to the 'CustomerToppings' route for item customization.|-|

<!-- @vuese:CustomerMenuItems:methods:end -->


## Data

<!-- @vuese:CustomerMenuItems:data:start -->
|Name|Type|Description|Default|
|---|---|---|---|
|category|`Array`|An array to store categories derived from `filteredMenuItems`.|-|

<!-- @vuese:CustomerMenuItems:data:end -->


## Watch

<!-- @vuese:CustomerMenuItems:watch:start -->
|Name|Description|Parameters|
|---|---|---|
|filteredMenuItems|Watches for changes in `filteredMenuItems` and updates the `category` data property accordingly.|-|

<!-- @vuese:CustomerMenuItems:watch:end -->


