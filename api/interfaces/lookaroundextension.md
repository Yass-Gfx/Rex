[ReX.js](../README.md) > [LookAroundExtension](../interfaces/lookaroundextension.md)

# Interface: LookAroundExtension

RegEx look around methods ReX.js extension.

## Hierarchy

**LookAroundExtension**

↳  [Matcher](../classes/matcher.md)

## Index

### Properties

* [after](lookaroundextension.md#after)
* [before](lookaroundextension.md#before)

### Methods

* [follow](lookaroundextension.md#follow)
* [precede](lookaroundextension.md#precede)

---

## Properties

<a id="after"></a>

###  after

**● after**: *[follow](lookaroundextension.md#follow)*

*Defined in [extensions/look.ts:16](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/look.ts#L16)*

___
<a id="before"></a>

###  before

**● before**: *[precede](lookaroundextension.md#precede)*

*Defined in [extensions/look.ts:22](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/look.ts#L22)*

___

## Methods

<a id="follow"></a>

###  follow

▸ **follow**(expr: * `string` &#124; [FuncExpr](funcexpr.md)<[Matcher](../classes/matcher.md)>*): [Matcher](../classes/matcher.md)

*Defined in [extensions/look.ts:15](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/look.ts#L15)*

Matches group after last expression without including it in the result.

**Parameters:**

| Name | Type |
| ------ | ------ |
| expr |  `string` &#124; [FuncExpr](funcexpr.md)<[Matcher](../classes/matcher.md)>|

**Returns:** [Matcher](../classes/matcher.md)

___
<a id="precede"></a>

###  precede

▸ **precede**(expr: * `string` &#124; [FuncExpr](funcexpr.md)<[Matcher](../classes/matcher.md)>*): [Matcher](../classes/matcher.md)

*Defined in [extensions/look.ts:21](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/look.ts#L21)*

Matches group before last expression without including it in the result.

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| expr |  `string` &#124; [FuncExpr](funcexpr.md)<[Matcher](../classes/matcher.md)>|  Lookbehind body as string of characters or expression body ( function ) |

**Returns:** [Matcher](../classes/matcher.md)

___

