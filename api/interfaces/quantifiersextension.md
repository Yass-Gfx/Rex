[ReX.js](../README.md) > [QuantifiersExtension](../interfaces/quantifiersextension.md)

# Interface: QuantifiersExtension

RegEx quantifiers methods ReX.js extension.

## Hierarchy

**QuantifiersExtension**

↳  [Matcher](../classes/matcher.md)

## Index

### Properties

* [additional](quantifiersextension.md#additional)
* [alternative](quantifiersextension.md#alternative)
* [plus](quantifiersextension.md#plus)
* [quantify](quantifiersextension.md#quantify)
* [star](quantifiersextension.md#star)
* [unnecessary](quantifiersextension.md#unnecessary)

### Methods

* [more](quantifiersextension.md#more)
* [moreOrNot](quantifiersextension.md#moreornot)
* [optional](quantifiersextension.md#optional)
* [or](quantifiersextension.md#or)
* [withLimits](quantifiersextension.md#withlimits)

---

## Properties

<a id="additional"></a>

###  additional

**● additional**: *[optional](quantifiersextension.md#optional)*

*Defined in [extensions/quantifiers.ts:31](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/quantifiers.ts#L31)*

___
<a id="alternative"></a>

###  alternative

**● alternative**: *[or](quantifiersextension.md#or)*

*Defined in [extensions/quantifiers.ts:38](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/quantifiers.ts#L38)*

___
<a id="plus"></a>

###  plus

**● plus**: *[more](quantifiersextension.md#more)*

*Defined in [extensions/quantifiers.ts:20](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/quantifiers.ts#L20)*

___
<a id="quantify"></a>

###  quantify

**● quantify**: *[withLimits](quantifiersextension.md#withlimits)*

*Defined in [extensions/quantifiers.ts:45](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/quantifiers.ts#L45)*

___
<a id="star"></a>

###  star

**● star**: *[moreOrNot](quantifiersextension.md#moreornot)*

*Defined in [extensions/quantifiers.ts:25](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/quantifiers.ts#L25)*

___
<a id="unnecessary"></a>

###  unnecessary

**● unnecessary**: *[optional](quantifiersextension.md#optional)*

*Defined in [extensions/quantifiers.ts:30](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/quantifiers.ts#L30)*

___

## Methods

<a id="more"></a>

###  more

▸ **more**(): [Quantifier](quantifier.md)

*Defined in [extensions/quantifiers.ts:19](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/quantifiers.ts#L19)*

Matches 1 or more of preceding tokens.

**Returns:** [Quantifier](quantifier.md)

___
<a id="moreornot"></a>

###  moreOrNot

▸ **moreOrNot**(): [Quantifier](quantifier.md)

*Defined in [extensions/quantifiers.ts:24](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/quantifiers.ts#L24)*

Matches 0 or more of preceding tokens.

**Returns:** [Quantifier](quantifier.md)

___
<a id="optional"></a>

###  optional

▸ **optional**(): [Matcher](../classes/matcher.md)

*Defined in [extensions/quantifiers.ts:29](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/quantifiers.ts#L29)*

Makes preceding token optional.

**Returns:** [Matcher](../classes/matcher.md)

___
<a id="or"></a>

###  or

▸ **or**(expr: * `string` &#124; [FuncExpr](funcexpr.md)<[Matcher](../classes/matcher.md)>*): [Matcher](../classes/matcher.md)

*Defined in [extensions/quantifiers.ts:37](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/quantifiers.ts#L37)*

Matches the expression before or QuantifiersExtension currently provided.

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| expr |  `string` &#124; [FuncExpr](funcexpr.md)<[Matcher](../classes/matcher.md)>|  *   as string of characters or expression body ( function ). |

**Returns:** [Matcher](../classes/matcher.md)

___
<a id="withlimits"></a>

###  withLimits

▸ **withLimits**(lowerLimit: *`number`*, upperLimit: *`number`*): [Quantifier](quantifier.md)

*Defined in [extensions/quantifiers.ts:44](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/quantifiers.ts#L44)*

Matches more of preceding tokens within given limits.

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| lowerLimit | `number` |  Lowest number of tokens to match. |
| upperLimit | `number` |  Highest number of tokens to match. |

**Returns:** [Quantifier](quantifier.md)

___

