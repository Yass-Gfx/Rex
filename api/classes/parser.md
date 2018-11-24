[ReX.js](../README.md) > [Parser](../classes/parser.md)

# Class: Parser

Parser class for executing extended regExs.

## Hierarchy

**Parser**

## Index

### Constructors

* [constructor](parser.md#constructor)

### Properties

* [expr](parser.md#expr)
* [flags](parser.md#flags)

### Methods

* [match](parser.md#match)
* [matchAll](parser.md#matchall)
* [search](parser.md#search)
* [split](parser.md#split)
* [test](parser.md#test)
* [update](parser.md#update)

---

## Constructors

<a id="constructor"></a>

###  constructor

⊕ **new Parser**(expr?: * `undefined` &#124; `string`*, flags?: * `undefined` &#124; `string`*): [Parser](parser.md)

*Defined in [parser.ts:31](https://github.com/areknawo/Rex/blob/cd201a2/src/parser.ts#L31)*

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| `Optional` expr |  `undefined` &#124; `string`|  Rex regEx string. |
| `Optional` flags |  `undefined` &#124; `string`|  Regular Expression flags. |

**Returns:** [Parser](parser.md)

___

## Properties

<a id="expr"></a>

###  expr

**● expr**: *`string`* = ""

*Defined in [parser.ts:23](https://github.com/areknawo/Rex/blob/cd201a2/src/parser.ts#L23)*

Parser regEx as string.

___
<a id="flags"></a>

###  flags

**● flags**: *`string`[]* =  []

*Defined in [parser.ts:19](https://github.com/areknawo/Rex/blob/cd201a2/src/parser.ts#L19)*

Flags applied to parser regEx.

___

## Methods

<a id="match"></a>

###  match

▸ **match**(str: *`string`*):  `null` &#124; [Result](../interfaces/result.md)

*Defined in [parser.ts:65](https://github.com/areknawo/Rex/blob/cd201a2/src/parser.ts#L65)*

Matches string against regEx and returns result as array. Similar to 'RegExp.exec()' method.

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| str | `string` |  String to run operation against. |

**Returns:**  `null` &#124; [Result](../interfaces/result.md)

___
<a id="matchall"></a>

###  matchAll

▸ **matchAll**(str: *`string`*):  `null` &#124; [Result](../interfaces/result.md)[]

*Defined in [parser.ts:80](https://github.com/areknawo/Rex/blob/cd201a2/src/parser.ts#L80)*

Matches all matches in string for regEx and returns array of result arrays.

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| str | `string` |  String to run operation against. |

**Returns:**  `null` &#124; [Result](../interfaces/result.md)[]

___
<a id="search"></a>

###  search

▸ **search**(str: *`string`*): `number`

*Defined in [parser.ts:108](https://github.com/areknawo/Rex/blob/cd201a2/src/parser.ts#L108)*

Search for match in given string. Returns beginning index of match or -1 if not found.

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| str | `string` |  String to run operation against. |

**Returns:** `number`

___
<a id="split"></a>

###  split

▸ **split**(str: *`string`*, n?: * `undefined` &#124; `number`*): `string`[]

*Defined in [parser.ts:118](https://github.com/areknawo/Rex/blob/cd201a2/src/parser.ts#L118)*

Splits the string in places that match regEx.

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| str | `string` |  String to run operation against. |
| `Optional` n |  `undefined` &#124; `number`|  How many times to split the string - minimum 1 |

**Returns:** `string`[]

___
<a id="test"></a>

###  test

▸ **test**(str: *`string`*): `boolean`

*Defined in [parser.ts:55](https://github.com/areknawo/Rex/blob/cd201a2/src/parser.ts#L55)*

Tests string against regEx and returns boolean if matched. Similar to 'RegExp.test()' method.

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| str | `string` |  String to run operation against. |

**Returns:** `boolean`

___
<a id="update"></a>

###  update

▸ **update**(expr: *`string`*, flags: *`string`*): `void`

*Defined in [parser.ts:44](https://github.com/areknawo/Rex/blob/cd201a2/src/parser.ts#L44)*

Updates parser data.

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| expr | `string` |  Parser Rex regEx. |
| flags | `string` |  Parser Rex regEx flags string. |

**Returns:** `void`

___

