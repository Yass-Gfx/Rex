[ReX.js](../README.md) > [EscapedCharactersExtension](../interfaces/escapedcharactersextension.md)

# Interface: EscapedCharactersExtension

RegEx escaped characters matching methods ReX.js extension.

## Hierarchy

**EscapedCharactersExtension**

↳  [Matcher](../classes/matcher.md)

## Index

### Properties

* [enter](escapedcharactersextension.md#enter)
* [vTab](escapedcharactersextension.md#vtab)

### Methods

* [carriageReturn](escapedcharactersextension.md#carriagereturn)
* [codeZero](escapedcharactersextension.md#codezero)
* [control](escapedcharactersextension.md#control)
* [formFeed](escapedcharactersextension.md#formfeed)
* [hex](escapedcharactersextension.md#hex)
* [lineFeed](escapedcharactersextension.md#linefeed)
* [octal](escapedcharactersextension.md#octal)
* [tab](escapedcharactersextension.md#tab)
* [unicode](escapedcharactersextension.md#unicode)
* [verticalTab](escapedcharactersextension.md#verticaltab)

---

## Properties

<a id="enter"></a>

###  enter

**● enter**: *[lineFeed](escapedcharactersextension.md#linefeed)*

*Defined in [extensions/escaped.ts:25](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/escaped.ts#L25)*

___
<a id="vtab"></a>

###  vTab

**● vTab**: *[verticalTab](escapedcharactersextension.md#verticaltab)*

*Defined in [extensions/escaped.ts:53](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/escaped.ts#L53)*

___

## Methods

<a id="carriagereturn"></a>

###  carriageReturn

▸ **carriageReturn**(): [Matcher](../classes/matcher.md)

*Defined in [extensions/escaped.ts:11](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/escaped.ts#L11)*

Matches carriage return character ( char code 13 ).

**Returns:** [Matcher](../classes/matcher.md)

___
<a id="codezero"></a>

###  codeZero

▸ **codeZero**(): [Matcher](../classes/matcher.md)

*Defined in [extensions/escaped.ts:15](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/escaped.ts#L15)*

Matches null character ( char code 0 ).

**Returns:** [Matcher](../classes/matcher.md)

___
<a id="control"></a>

###  control

▸ **control**(letter: *`string`*): [Matcher](../classes/matcher.md)

*Defined in [extensions/escaped.ts:20](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/escaped.ts#L20)*

Matches given control escaped character.

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| letter | `string` |  Control letter ( A for char code 1 up to Z for char code 26 ) |

**Returns:** [Matcher](../classes/matcher.md)

___
<a id="formfeed"></a>

###  formFeed

▸ **formFeed**(): [Matcher](../classes/matcher.md)

*Defined in [extensions/escaped.ts:29](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/escaped.ts#L29)*

Matches form feed character ( char code 12 ).

**Returns:** [Matcher](../classes/matcher.md)

___
<a id="hex"></a>

###  hex

▸ **hex**(hex: *`string`*): [Matcher](../classes/matcher.md)

*Defined in [extensions/escaped.ts:34](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/escaped.ts#L34)*

Matches given hexadecimal escaped character.

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| hex | `string` |  Sting of two hex digits e.g. "ff". |

**Returns:** [Matcher](../classes/matcher.md)

___
<a id="linefeed"></a>

###  lineFeed

▸ **lineFeed**(): [Matcher](../classes/matcher.md)

*Defined in [extensions/escaped.ts:24](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/escaped.ts#L24)*

Matches line feed character a.k.a. 'enter' ( char code 10 ).

**Returns:** [Matcher](../classes/matcher.md)

___
<a id="octal"></a>

###  octal

▸ **octal**(oct: *`string`*): [Matcher](../classes/matcher.md)

*Defined in [extensions/escaped.ts:39](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/escaped.ts#L39)*

Matches given octal escaped character.

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| oct | `string` |  Sting of three octal digits e.g. "021" with max being "377". |

**Returns:** [Matcher](../classes/matcher.md)

___
<a id="tab"></a>

###  tab

▸ **tab**(): [Matcher](../classes/matcher.md)

*Defined in [extensions/escaped.ts:43](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/escaped.ts#L43)*

Matches tab character ( char code 9 ).

**Returns:** [Matcher](../classes/matcher.md)

___
<a id="unicode"></a>

###  unicode

▸ **unicode**(code: *`string`*): [Matcher](../classes/matcher.md)

*Defined in [extensions/escaped.ts:48](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/escaped.ts#L48)*

Matches given unicode escaped character.

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| code | `string` |  Sting of four ( can be more with extendedUnicodes applied ) hex digits. |

**Returns:** [Matcher](../classes/matcher.md)

___
<a id="verticaltab"></a>

###  verticalTab

▸ **verticalTab**(): [Matcher](../classes/matcher.md)

*Defined in [extensions/escaped.ts:52](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/escaped.ts#L52)*

Matches vertical tab character ( char code 11 ).

**Returns:** [Matcher](../classes/matcher.md)

___

