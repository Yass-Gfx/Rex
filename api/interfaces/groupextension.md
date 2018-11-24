[ReX.js](../README.md) > [GroupExtension](../interfaces/groupextension.md)

# Interface: GroupExtension

RegEx grouping-related methods ReX.js extension.

## Hierarchy

**GroupExtension**

↳  [Matcher](../classes/matcher.md)

## Index

### Properties

* [group](groupextension.md#group)
* [reference](groupextension.md#reference)

### Methods

* [as](groupextension.md#as)
* [capture](groupextension.md#capture)
* [ref](groupextension.md#ref)

---

## Properties

<a id="group"></a>

###  group

**● group**: *[capture](groupextension.md#capture)*

*Defined in [extensions/group.ts:20](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/group.ts#L20)*

___
<a id="reference"></a>

###  reference

**● reference**: *[ref](groupextension.md#ref)*

*Defined in [extensions/group.ts:27](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/group.ts#L27)*

___

## Methods

<a id="as"></a>

###  as

▸ **as**(name: *`string`*): [Matcher](../classes/matcher.md)

*Defined in [extensions/group.ts:13](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/group.ts#L13)*

Sets name of preceding expression.

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| name | `string` |  Name for the previously applied expression. |

**Returns:** [Matcher](../classes/matcher.md)

___
<a id="capture"></a>

###  capture

▸ **capture**(expr: * `string` &#124; [FuncExpr](funcexpr.md)<[Matcher](../classes/matcher.md)>*): [Matcher](../classes/matcher.md)

*Defined in [extensions/group.ts:19](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/group.ts#L19)*

Captures multiple characters together. Negate creates group of characters but doesn't capture them.

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| expr |  `string` &#124; [FuncExpr](funcexpr.md)<[Matcher](../classes/matcher.md)>|  Set's body as string of characters or expression body ( function ). |

**Returns:** [Matcher](../classes/matcher.md)

___
<a id="ref"></a>

###  ref

▸ **ref**(name: *`string`*): [Matcher](../classes/matcher.md)

*Defined in [extensions/group.ts:26](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/group.ts#L26)*

Matches result of previous group.

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| name | `string` |  Name of expression to be referenced. Previously set by 'as()' method. |

**Returns:** [Matcher](../classes/matcher.md)

___

