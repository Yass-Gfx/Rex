[ReX.js](../README.md) > [ReplaceExtension](../interfaces/replaceextension.md)

# Interface: ReplaceExtension

RegEx replacement-related methods ReX.js extension.

## Hierarchy

**ReplaceExtension**

↳  [Replacer](../classes/replacer.md)

## Index

### Methods

* [afterMatched](replaceextension.md#aftermatched)
* [beforeMatched](replaceextension.md#beforematched)
* [captured](replaceextension.md#captured)
* [dollar](replaceextension.md#dollar)
* [matched](replaceextension.md#matched)

---

## Methods

<a id="aftermatched"></a>

###  afterMatched

▸ **afterMatched**(): [Replacer](../classes/replacer.md)

*Defined in [extensions/replace.ts:24](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/replace.ts#L24)*

Includes portion of string that follows matched part in replacer.

**Returns:** [Replacer](../classes/replacer.md)

___
<a id="beforematched"></a>

###  beforeMatched

▸ **beforeMatched**(): [Replacer](../classes/replacer.md)

*Defined in [extensions/replace.ts:20](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/replace.ts#L20)*

Includes portion of string that precedes matched part in replacer.

**Returns:** [Replacer](../classes/replacer.md)

___
<a id="captured"></a>

###  captured

▸ **captured**(name: *`string`*): [Replacer](../classes/replacer.md)

*Defined in [extensions/replace.ts:16](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/replace.ts#L16)*

Includes matched named group in replacer.

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| name | `string` |  Name of the group to be referenced. |

**Returns:** [Replacer](../classes/replacer.md)

___
<a id="dollar"></a>

###  dollar

▸ **dollar**(): [Replacer](../classes/replacer.md)

*Defined in [extensions/replace.ts:28](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/replace.ts#L28)*

Includes dollar character in replacer

**Returns:** [Replacer](../classes/replacer.md)

___
<a id="matched"></a>

###  matched

▸ **matched**(): [Replacer](../classes/replacer.md)

*Defined in [extensions/replace.ts:11](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/replace.ts#L11)*

Includes matched string in its replacer.

**Returns:** [Replacer](../classes/replacer.md)

___

