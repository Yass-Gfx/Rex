[ReX.js](../README.md) > [FlagsExtension](../interfaces/flagsextension.md)

# Interface: FlagsExtension

RegEx flags-related methods ReX.js extension.

## Hierarchy

**FlagsExtension**

↳  [Matcher](../classes/matcher.md)

## Index

### Properties

* [g](flagsextension.md#g)
* [global](flagsextension.md#global)
* [i](flagsextension.md#i)
* [m](flagsextension.md#m)
* [sticky](flagsextension.md#sticky)
* [u](flagsextension.md#u)
* [y](flagsextension.md#y)

### Methods

* [extendedUnicodes](flagsextension.md#extendedunicodes)
* [globalize](flagsextension.md#globalize)
* [ignoreCase](flagsextension.md#ignorecase)
* [multiline](flagsextension.md#multiline)
* [singleByIndex](flagsextension.md#singlebyindex)

---

## Properties

<a id="g"></a>

###  g

**● g**: *[globalize](flagsextension.md#globalize)*

*Defined in [extensions/flags.ts:18](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/flags.ts#L18)*

___
<a id="global"></a>

###  global

**● global**: *[globalize](flagsextension.md#globalize)*

*Defined in [extensions/flags.ts:19](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/flags.ts#L19)*

___
<a id="i"></a>

###  i

**● i**: *[ignoreCase](flagsextension.md#ignorecase)*

*Defined in [extensions/flags.ts:24](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/flags.ts#L24)*

___
<a id="m"></a>

###  m

**● m**: *[multiline](flagsextension.md#multiline)*

*Defined in [extensions/flags.ts:29](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/flags.ts#L29)*

___
<a id="sticky"></a>

###  sticky

**● sticky**: *[singleByIndex](flagsextension.md#singlebyindex)*

*Defined in [extensions/flags.ts:37](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/flags.ts#L37)*

___
<a id="u"></a>

###  u

**● u**: *[extendedUnicodes](flagsextension.md#extendedunicodes)*

*Defined in [extensions/flags.ts:13](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/flags.ts#L13)*

___
<a id="y"></a>

###  y

**● y**: *[singleByIndex](flagsextension.md#singlebyindex)*

*Defined in [extensions/flags.ts:36](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/flags.ts#L36)*

___

## Methods

<a id="extendedunicodes"></a>

###  extendedUnicodes

▸ **extendedUnicodes**(): [Matcher](../classes/matcher.md)

*Defined in [extensions/flags.ts:12](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/flags.ts#L12)*

Allows extended use of unicodes. See browser support!

**Returns:** [Matcher](../classes/matcher.md)

___
<a id="globalize"></a>

###  globalize

▸ **globalize**(): [Matcher](../classes/matcher.md)

*Defined in [extensions/flags.ts:17](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/flags.ts#L17)*

Allows to regiser more than 1 matches.

**Returns:** [Matcher](../classes/matcher.md)

___
<a id="ignorecase"></a>

###  ignoreCase

▸ **ignoreCase**(): [Matcher](../classes/matcher.md)

*Defined in [extensions/flags.ts:23](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/flags.ts#L23)*

Disables case sensitivity.

**Returns:** [Matcher](../classes/matcher.md)

___
<a id="multiline"></a>

###  multiline

▸ **multiline**(): [Matcher](../classes/matcher.md)

*Defined in [extensions/flags.ts:28](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/flags.ts#L28)*

Takes into account new lines.

**Returns:** [Matcher](../classes/matcher.md)

___
<a id="singlebyindex"></a>

###  singleByIndex

▸ **singleByIndex**(): [Matcher](../classes/matcher.md)

*Defined in [extensions/flags.ts:35](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/flags.ts#L35)*

Register only one match, starting from selected index. Automatically ignores 'globalize()' function See browser support!

**Returns:** [Matcher](../classes/matcher.md)

___

