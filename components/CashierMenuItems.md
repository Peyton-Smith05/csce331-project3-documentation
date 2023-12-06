# CashierMenuItems

## Props

<!-- @vuese:CashierMenuItems:props:start -->
|Name|Description|Type|Required|Default|
|---|---|---|---|---|
|filteredMenuItems|An array of menu items to display. Each item includes details like name and price.|`Array`|`false`|[]|

<!-- @vuese:CashierMenuItems:props:end -->


## Events

<!-- @vuese:CashierMenuItems:events:start -->
|Event Name|Description|Parameters|
|---|---|---|
|itemChosen|-|-|

<!-- @vuese:CashierMenuItems:events:end -->


## Methods

<!-- @vuese:CashierMenuItems:methods:start -->
|Method|Description|Parameters|
|---|---|---|
|redirectToToppings|When called, emits an 'itemChosen' event with the selected item and redirects to the CashierToppings page.|item - The selected menu item.|

<!-- @vuese:CashierMenuItems:methods:end -->


