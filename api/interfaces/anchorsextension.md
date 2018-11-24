[ReX.js](../README.md) > [AnchorsExtension](../interfaces/anchorsextension.md)

# Interface: AnchorsExtension

RegEx anchor-related methods ReX.js extension.

## Hierarchy

**AnchorsExtension**

↳  [Matcher](../classes/matcher.md)

## Index

### Properties

* [boundary](anchorsextension.md#boundary)

### Methods

* [begin](anchorsextension.md#begin)
* [end](anchorsextension.md#end)
* [wordBoundary](anchorsextension.md#wordboundary)

---

## Properties

<a id="boundary"></a>

###  boundary

**● boundary**: *[wordBoundary](anchorsextension.md#wordboundary)*

*Defined in [extensions/anchors.ts:20](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/anchors.ts#L20)*

___

## Methods

<a id="begin"></a>

###  begin

▸ **begin**(): [Matcher](../classes/matcher.md)

*Defined in [extensions/anchors.ts:11](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/anchors.ts#L11)*

Matches beginning of passed string or line ( if multiline is applied ).

**Returns:** [Matcher](../classes/matcher.md)

___
<a id="end"></a>

###  end

▸ **end**(): [Matcher](../classes/matcher.md)

*Defined in [extensions/anchors.ts:15](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/anchors.ts#L15)*

Matches ending of passed string or line ( if multiline is applied ).

**Returns:** [Matcher](../classes/matcher.md)

___
<a id="wordboundary"></a>

###  wordBoundary

▸ **wordBoundary**(): [Matcher](../classes/matcher.md)

*Defined in [extensions/anchors.ts:19](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/anchors.ts#L19)*

States that match starts with non-word character e.g. space, -, tab etc.

**Returns:** [Matcher](../classes/matcher.md)

___

