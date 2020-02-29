---
title: Attribute
sidebarDepth: 2
---

:::warning
This page is currently being updated.
:::

## Properties

### `key`

**Type:** String

**Description:** Keys uniquely identify an attribute and may determine how animations are applied.

**Default:** `index`

<!-- ### `highlight`

**Type:** Object, Function

**Description:** Highlight to associate with an attribute that may be defined as an [object](#highlight-object) or a [function](../guide/attributes.md#using-functions) that returns an object.

**Default:** `undefined`

### `dot`

**Type:** Object, Function

**Description:** Dot to associate with an attribute that may be defined as an [object](#dot-object) or a [function](../guide/attributes.md#using-functions) that returns an object.

**Default:** `undefined`

### `bar`

**Type:** Object, Function

**Description:** Bar to associate with an attribute that may be defined as an [object](#bar-object) or a [function](../guide/attributes.md#using-functions) that returns an object.

**Default:** `undefined`

### `popover`

**Type:** Object, Function

**Description:** Popover to associate with an attribute that may be defined as an [object](#popover-object) or a [function](../guide/attributes.md#using-functions) that returns an object.

**Default:** `undefined`

### `contentClass`

**Type:** String

**Description:** Class to apply to day content that may be defined as a string or a [function](../guide/attributes.md#using-functions) that returns a string.

### `contentStyle`

**Type:** Object, Function

**Description:** Style to apply to day content that may be defined as an [object](#content-style-object) or a [function](../guide/attributes.md#using-functions) that returns an object.

**Default:** `undefined`

### `dates`

**Type:** Date, Object, Array[Date, Object]

**Description:** Date or date range objects (patterns supported) to include for the attribute.

**Default:** `undefined`

### `excludeDates`

**Type:** Date, Object, Array[Date, Object]

**Description:** Date or date range objects (patterns supported) to exclude. All other dates are included.

**Default:** `undefined`

### `customObject`

**Type:** Any

**Description:** Assign any custom data to this property for easy access within event handlers.

**Default:** `undefined`

### `order`

**Type:** Number

**Description:** Order that the attribute should be displayed. Higher numbers take precedence in appearance.

**Default:** `0`

<!-- 
### 

**Type:** 

**Description:** 

**Default:** 
-->

## Highlight

**Description:** Highlight to associate with the attribute

**Type:** Boolean

When `true` the current theme color is used

**Type:** String

Uses theme with the provided name

**Type:** Object

Set of options to configure the highlight

**Default:** `undefined`

### `highlight.color`

**Description:** Uses theme with the provided name

**Type:** String

<!-- 
### 

**Type:** 

**Description:** 

**Default:** 
-->

<!-- ## Bar Object

### `height`

**Type:** String

**Description:** Height of bar.

**Default:** `"5px"`

### `backgroundColor`

**Type:** String

**Description:** Background color of bar.

**Default:** `"rgba(0, 0, 0, 0.5)"`

### `borderColor`

**Type:** String

**Description:** Border color of bar.

**Default:** `undefined`

### `borderWidth`

**Type:** String

**Description:** Border width of bar.

**Default:** `0`

### `backgroundColor`

**Type:** String

**Description:** Background color of bar.

**Default:** `undefined`

### `opacity`

**Type:** Number

**Description:** Opacity of bar.

**Default:** `1` -->

<!-- 
### 

**Type:** 

**Description:** 

**Default:** 
-->

## Popover

**Type:** Object

**Description:** Popover to associate with the attribute

**Default:** `undefined`

### `popover.label`

**Description:** Text string content to display in the popover.

**Type:** String

**Default:** `undefined`

### `popover.labelClass`

**Description:** Class to apply to the label.

**Type:** String

**Default:** `undefined`

### `popover.labelStyle`

**Description:** Style to apply to the label.

**Type:** Object

**Default:** `undefined`

### `popover.hideIndicator`

**Description:** Hides the indicator that appears to the left of the label.

**Type:** Boolean

**Default:** `false`

### `popover.isInteractive`

**Description:** Allows user to interactive with the popover contents. For example, this keeps the popover open when user hovers over the popover when `visibility === "hover"`, instead of hiding it by default.

**Type:** Boolean

**Default:** `false`

### `popover.visibility`

**Description:**  Visibility mode for the popover (`"hover-focus"`, `"hover"`, `"focus"`, `"click"`, `"visible"`, `"hidden"`).

**Type:** String

**Default:** `"hover"`

### `popover.placement`

**Description:** Default or suggested placement of the popover. This may change as the browser window dimensions change. [Valid placements](https://popper.js.org/docs/v2/constructors/#placement) include `auto`, `top`, `right`, `bottom`, `left`. Each placement can have suffixed variations `-start` or `-end`.

**Type:** String

**Default:** `"bottom"`

### `popover.positionFixed` [Deprecated]

**Description:** Display the popover in `fixed` mode. Reference [`popper.js`](https://popper.js.org/popper-documentation.html#Popper.Defaults.positionFixed) for more details.

**Type:** Boolean

**Default:** `false`

::: warning
This option deprecated in `v1.1.0` in favor of the `strategy` option.
:::

### `popover.strategy`

**Description:** Describes the positioning strategy to use. By default, it is `absolute`, which in the simplest cases does not require repositioning of the popover. Reference [`popper.js`](https://popper.js.org/docs/v2/constructors/#strategy) for more details

**Type:** String

**Default:** `"absolute"`

::: tip
This option replaces the deprecated `positionFixed` option as of `v1.1.0`
:::

### `popover.modifiers`

**Description:** Used to modify the behavior of `popper.js` [`< v1.1.0`](https://popper.js.org/docs/v1/#modifiers) [`>= v1.1.0`](https://popper.js.org/docs/v2/modifiers/).

**Type:** Object `< v1.1.0`, Array `>= v1.1.0`

**Default:** `undefined`

<!-- 
### 

**Type:** 

**Description:** 

**Default:** 
-->