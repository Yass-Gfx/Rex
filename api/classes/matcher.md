[ReX.js](../README.md) > [Matcher](../classes/matcher.md)

# Class: Matcher

Class for constructing matching expressions.

## Hierarchy

 [ReXer](rexer.md)

 [AnchorsExtension](../interfaces/anchorsextension.md)

 [CharactersExtension](../interfaces/charactersextension.md)

 [EscapedCharactersExtension](../interfaces/escapedcharactersextension.md)

 [FlagsExtension](../interfaces/flagsextension.md)

 [GroupExtension](../interfaces/groupextension.md)

 [LookAroundExtension](../interfaces/lookaroundextension.md)

 [QuantifiersExtension](../interfaces/quantifiersextension.md)

**↳ Matcher**

↳  [Quantifier](../interfaces/quantifier.md)

## Index

### Constructors

* [constructor](matcher.md#constructor)

### Properties

* [additional](matcher.md#additional)
* [after](matcher.md#after)
* [alternative](matcher.md#alternative)
* [any](matcher.md#any)
* [before](matcher.md#before)
* [boundary](matcher.md#boundary)
* [char](matcher.md#char)
* [enter](matcher.md#enter)
* [g](matcher.md#g)
* [global](matcher.md#global)
* [group](matcher.md#group)
* [i](matcher.md#i)
* [lastOperation](matcher.md#lastoperation)
* [m](matcher.md#m)
* [plus](matcher.md#plus)
* [quantify](matcher.md#quantify)
* [reference](matcher.md#reference)
* [star](matcher.md#star)
* [sticky](matcher.md#sticky)
* [u](matcher.md#u)
* [unnecessary](matcher.md#unnecessary)
* [vTab](matcher.md#vtab)
* [whitespace](matcher.md#whitespace)
* [y](matcher.md#y)
* [AnchorsExtension](matcher.md#anchorsextension)
* [CharactersExtension](matcher.md#charactersextension)
* [EscapedCharactersExtension](matcher.md#escapedcharactersextension)
* [FlagsExtension](matcher.md#flagsextension)
* [GroupExtension](matcher.md#groupextension)
* [LookAroundExtension](matcher.md#lookaroundextension)
* [QuantifiersExtension](matcher.md#quantifiersextension)

### Methods

* [add](matcher.md#add)
* [addFlag](matcher.md#addflag)
* [anyButBreak](matcher.md#anybutbreak)
* [anyWhitespace](matcher.md#anywhitespace)
* [as](matcher.md#as)
* [begin](matcher.md#begin)
* [capture](matcher.md#capture)
* [carriageReturn](matcher.md#carriagereturn)
* [codeZero](matcher.md#codezero)
* [containsFlag](matcher.md#containsflag)
* [control](matcher.md#control)
* [createChannel](matcher.md#createchannel)
* [createSnippet](matcher.md#createsnippet)
* [digit](matcher.md#digit)
* [end](matcher.md#end)
* [extendedUnicodes](matcher.md#extendedunicodes)
* [find](matcher.md#find)
* [follow](matcher.md#follow)
* [formFeed](matcher.md#formfeed)
* [getExpr](matcher.md#getexpr)
* [globalize](matcher.md#globalize)
* [hex](matcher.md#hex)
* [ignoreCase](matcher.md#ignorecase)
* [insertSnippet](matcher.md#insertsnippet)
* [lineFeed](matcher.md#linefeed)
* [match](matcher.md#match)
* [matchAll](matcher.md#matchall)
* [more](matcher.md#more)
* [moreOrNot](matcher.md#moreornot)
* [multiline](matcher.md#multiline)
* [negate](matcher.md#negate)
* [octal](matcher.md#octal)
* [optional](matcher.md#optional)
* [or](matcher.md#or)
* [precede](matcher.md#precede)
* [range](matcher.md#range)
* [ref](matcher.md#ref)
* [removeFlag](matcher.md#removeflag)
* [repeat](matcher.md#repeat)
* [search](matcher.md#search)
* [set](matcher.md#set)
* [setChannel](matcher.md#setchannel)
* [singleByIndex](matcher.md#singlebyindex)
* [split](matcher.md#split)
* [stringifyChannel](matcher.md#stringifychannel)
* [stringifyExpression](matcher.md#stringifyexpression)
* [tab](matcher.md#tab)
* [test](matcher.md#test)
* [unicode](matcher.md#unicode)
* [useExtension](matcher.md#useextension)
* [useMethod](matcher.md#usemethod)
* [verticalTab](matcher.md#verticaltab)
* [withLimits](matcher.md#withlimits)
* [wordBoundary](matcher.md#wordboundary)
* [wordChar](matcher.md#wordchar)

---

## Constructors

<a id="constructor"></a>

###  constructor

⊕ **new Matcher**(): [Matcher](matcher.md)

*Defined in [matcher.ts:22](https://github.com/areknawo/Rex/blob/cd201a2/src/matcher.ts#L22)*

**Returns:** [Matcher](matcher.md)

___

## Properties

<a id="additional"></a>

###  additional

**● additional**: *[optional](../interfaces/quantifiersextension.md#optional)*

*Inherited from [QuantifiersExtension](../interfaces/quantifiersextension.md).[additional](../interfaces/quantifiersextension.md#additional)*

*Defined in [extensions/quantifiers.ts:31](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/quantifiers.ts#L31)*

___
<a id="after"></a>

###  after

**● after**: *[follow](../interfaces/lookaroundextension.md#follow)*

*Inherited from [LookAroundExtension](../interfaces/lookaroundextension.md).[after](../interfaces/lookaroundextension.md#after)*

*Defined in [extensions/look.ts:16](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/look.ts#L16)*

___
<a id="alternative"></a>

###  alternative

**● alternative**: *[or](../interfaces/quantifiersextension.md#or)*

*Inherited from [QuantifiersExtension](../interfaces/quantifiersextension.md).[alternative](../interfaces/quantifiersextension.md#alternative)*

*Defined in [extensions/quantifiers.ts:38](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/quantifiers.ts#L38)*

___
<a id="any"></a>

###  any

**● any**: *[anyButBreak](../interfaces/charactersextension.md#anybutbreak)*

*Inherited from [CharactersExtension](../interfaces/charactersextension.md).[any](../interfaces/charactersextension.md#any)*

*Defined in [extensions/characters.ts:13](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/characters.ts#L13)*

___
<a id="before"></a>

###  before

**● before**: *[precede](../interfaces/lookaroundextension.md#precede)*

*Inherited from [LookAroundExtension](../interfaces/lookaroundextension.md).[before](../interfaces/lookaroundextension.md#before)*

*Defined in [extensions/look.ts:22](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/look.ts#L22)*

___
<a id="boundary"></a>

###  boundary

**● boundary**: *[wordBoundary](../interfaces/anchorsextension.md#wordboundary)*

*Inherited from [AnchorsExtension](../interfaces/anchorsextension.md).[boundary](../interfaces/anchorsextension.md#boundary)*

*Defined in [extensions/anchors.ts:20](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/anchors.ts#L20)*

___
<a id="char"></a>

###  char

**● char**: *[wordChar](../interfaces/charactersextension.md#wordchar)*

*Inherited from [CharactersExtension](../interfaces/charactersextension.md).[char](../interfaces/charactersextension.md#char)*

*Defined in [extensions/characters.ts:27](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/characters.ts#L27)*

___
<a id="enter"></a>

###  enter

**● enter**: *[lineFeed](../interfaces/escapedcharactersextension.md#linefeed)*

*Inherited from [EscapedCharactersExtension](../interfaces/escapedcharactersextension.md).[enter](../interfaces/escapedcharactersextension.md#enter)*

*Defined in [extensions/escaped.ts:25](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/escaped.ts#L25)*

___
<a id="g"></a>

###  g

**● g**: *[globalize](../interfaces/flagsextension.md#globalize)*

*Inherited from [FlagsExtension](../interfaces/flagsextension.md).[g](../interfaces/flagsextension.md#g)*

*Defined in [extensions/flags.ts:18](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/flags.ts#L18)*

___
<a id="global"></a>

###  global

**● global**: *[globalize](../interfaces/flagsextension.md#globalize)*

*Inherited from [FlagsExtension](../interfaces/flagsextension.md).[global](../interfaces/flagsextension.md#global)*

*Defined in [extensions/flags.ts:19](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/flags.ts#L19)*

___
<a id="group"></a>

###  group

**● group**: *[capture](../interfaces/groupextension.md#capture)*

*Inherited from [GroupExtension](../interfaces/groupextension.md).[group](../interfaces/groupextension.md#group)*

*Defined in [extensions/group.ts:20](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/group.ts#L20)*

___
<a id="i"></a>

###  i

**● i**: *[ignoreCase](../interfaces/flagsextension.md#ignorecase)*

*Inherited from [FlagsExtension](../interfaces/flagsextension.md).[i](../interfaces/flagsextension.md#i)*

*Defined in [extensions/flags.ts:24](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/flags.ts#L24)*

___
<a id="lastoperation"></a>

###  lastOperation

**● lastOperation**: * [Operation](operation.md)<`this`> &#124; `null`
* =  null

*Inherited from [ReXer](rexer.md).[lastOperation](rexer.md#lastoperation)*

*Defined in [rexer.ts:21](https://github.com/areknawo/Rex/blob/cd201a2/src/rexer.ts#L21)*

Last added operation to main channel.

___
<a id="m"></a>

###  m

**● m**: *[multiline](../interfaces/flagsextension.md#multiline)*

*Inherited from [FlagsExtension](../interfaces/flagsextension.md).[m](../interfaces/flagsextension.md#m)*

*Defined in [extensions/flags.ts:29](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/flags.ts#L29)*

___
<a id="plus"></a>

###  plus

**● plus**: *[more](../interfaces/quantifiersextension.md#more)*

*Inherited from [QuantifiersExtension](../interfaces/quantifiersextension.md).[plus](../interfaces/quantifiersextension.md#plus)*

*Defined in [extensions/quantifiers.ts:20](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/quantifiers.ts#L20)*

___
<a id="quantify"></a>

###  quantify

**● quantify**: *[withLimits](../interfaces/quantifiersextension.md#withlimits)*

*Inherited from [QuantifiersExtension](../interfaces/quantifiersextension.md).[quantify](../interfaces/quantifiersextension.md#quantify)*

*Defined in [extensions/quantifiers.ts:45](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/quantifiers.ts#L45)*

___
<a id="reference"></a>

###  reference

**● reference**: *[ref](../interfaces/groupextension.md#ref)*

*Inherited from [GroupExtension](../interfaces/groupextension.md).[reference](../interfaces/groupextension.md#reference)*

*Defined in [extensions/group.ts:27](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/group.ts#L27)*

___
<a id="star"></a>

###  star

**● star**: *[moreOrNot](../interfaces/quantifiersextension.md#moreornot)*

*Inherited from [QuantifiersExtension](../interfaces/quantifiersextension.md).[star](../interfaces/quantifiersextension.md#star)*

*Defined in [extensions/quantifiers.ts:25](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/quantifiers.ts#L25)*

___
<a id="sticky"></a>

###  sticky

**● sticky**: *[singleByIndex](../interfaces/flagsextension.md#singlebyindex)*

*Inherited from [FlagsExtension](../interfaces/flagsextension.md).[sticky](../interfaces/flagsextension.md#sticky)*

*Defined in [extensions/flags.ts:37](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/flags.ts#L37)*

___
<a id="u"></a>

###  u

**● u**: *[extendedUnicodes](../interfaces/flagsextension.md#extendedunicodes)*

*Inherited from [FlagsExtension](../interfaces/flagsextension.md).[u](../interfaces/flagsextension.md#u)*

*Defined in [extensions/flags.ts:13](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/flags.ts#L13)*

___
<a id="unnecessary"></a>

###  unnecessary

**● unnecessary**: *[optional](../interfaces/quantifiersextension.md#optional)*

*Inherited from [QuantifiersExtension](../interfaces/quantifiersextension.md).[unnecessary](../interfaces/quantifiersextension.md#unnecessary)*

*Defined in [extensions/quantifiers.ts:30](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/quantifiers.ts#L30)*

___
<a id="vtab"></a>

###  vTab

**● vTab**: *[verticalTab](../interfaces/escapedcharactersextension.md#verticaltab)*

*Inherited from [EscapedCharactersExtension](../interfaces/escapedcharactersextension.md).[vTab](../interfaces/escapedcharactersextension.md#vtab)*

*Defined in [extensions/escaped.ts:53](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/escaped.ts#L53)*

___
<a id="whitespace"></a>

###  whitespace

**● whitespace**: *[anyWhitespace](../interfaces/charactersextension.md#anywhitespace)*

*Inherited from [CharactersExtension](../interfaces/charactersextension.md).[whitespace](../interfaces/charactersextension.md#whitespace)*

*Defined in [extensions/characters.ts:18](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/characters.ts#L18)*

___
<a id="y"></a>

###  y

**● y**: *[singleByIndex](../interfaces/flagsextension.md#singlebyindex)*

*Inherited from [FlagsExtension](../interfaces/flagsextension.md).[y](../interfaces/flagsextension.md#y)*

*Defined in [extensions/flags.ts:36](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/flags.ts#L36)*

___
<a id="anchorsextension"></a>

### `<Static>` AnchorsExtension

**● AnchorsExtension**: *[Method](../interfaces/method.md)<[Matcher](matcher.md)>[]* =  [
  {
    name: 'begin',
    func() {
      this.add('^')

      return this
    },
  },
  {
    name: 'end',
    func() {
      this.add('$')

      return this
    },
  },
  {
    name: ['wordBoundary', 'boundary'],
    func() {
      this.add({
        expr: '\\b',
        negate() {
          this.setExpr('\\B')
        },
      })

      return this
    },
  },
]

*Defined in [extensions/anchors.ts:25](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/anchors.ts#L25)*

RegEx anchor-related methods ReX.js extension.

___
<a id="charactersextension"></a>

### `<Static>` CharactersExtension

**● CharactersExtension**: *[Method](../interfaces/method.md)<[Matcher](matcher.md)>[]* =  [
  {
    name: 'set',
    func(set: string | FuncExpr<Matcher>) {
      let expr
      if (typeof set === 'string') {
        expr = set.replace(/\\|]|-/g, '\\$&')
      } else {
        expr = set
      }
      this.add({
        expr,
        closure: {
          close: ']',
          open: '[',
        },
        negate() {
          this.setClosure({
            close: ']',
            open: '[^',
          })
        },
      })

      return this
    },
  },
  {
    name: 'range',
    func(start: string | number, end: string | number) {
      this.add({
        closure: {
          close: ']',
          open: '[',
        },
        expr: `${start}-${end}`,
        negate() {
          this.setClosure({
            close: ']',
            open: '[^',
          })
        },
      })

      return this
    },
  },
  {
    name: ['any', 'anyButBreak'],
    func() {
      this.add('.')

      return this
    },
  },
  {
    name: ['char', 'wordChar'],
    func() {
      this.add({
        expr: '\\w',
        negate() {
          this.setExpr('\\W')
        },
      })

      return this
    },
  },
  {
    name: 'digit',
    func() {
      this.add({
        expr: '\\d',
        negate() {
          this.setExpr('\\D')
        },
      })

      return this
    },
  },
  {
    name: ['whitespace', 'anyWhitespace'],
    func() {
      this.add({
        expr: '\\s',
        negate() {
          this.setExpr('\\S')
        },
      })

      return this
    },
  },
]

*Defined in [extensions/characters.ts:44](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/characters.ts#L44)*

RegEx character matching methods ReX.js extension.

___
<a id="escapedcharactersextension"></a>

### `<Static>` EscapedCharactersExtension

**● EscapedCharactersExtension**: *[Method](../interfaces/method.md)<[Matcher](matcher.md)>[]* =  [
  {
    name: 'octal',
    func(oct: string) {
      const maxOctDigits: number = 3
      const maxOctNumber: number = 377
      if (oct.length === maxOctDigits && Number(oct) <= maxOctNumber) {
        this.add(`\\${oct}`)
      } else {
        console.warn('Too big octal number - omitted!')
      }

      return this
    },
  },
  {
    name: 'hex',
    func(hex: string) {
      const maxHexDigits: number = 2
      if (hex.length === maxHexDigits) {
        this.add(`\\x${hex}`)
      } else {
        console.warn('Not enough characters supplied - omitted!')
      }

      return this
    },
  },
  {
    name: 'unicode',
    func(code: string) {
      const maxHexDigits: number = 4
      if (code.length === maxHexDigits) {
        this.add(`\\u${code}`)
      } else if (code.length > maxHexDigits && this.containsFlag('u')) {
        this.add(`\\u{${code}}`)
      } else {
        console.warn(
          'Not enough characters supplied or too many without `u` flag applied - omitted!',
        )
      }

      return this
    },
  },
  {
    name: 'control',
    func(letter: string) {
      if (letter.length === 1) {
        this.add(`\\c${letter}`)
      } else {
        console.warn('Character was not supplied correctly - omitted!')
      }

      return this
    },
  },
  {
    name: 'tab',
    func() {
      this.add('\\t')

      return this
    },
  },
  {
    name: ['enter', 'lineFeed'],
    func() {
      this.add('\\n')

      return this
    },
  },
  {
    name: ['vTab', 'verticalTab'],
    func() {
      this.add('\\v')

      return this
    },
  },
  {
    name: 'formFeed',
    /**
     * Matches form feed character ( char code 12 ).
     */
    func() {
      this.add('\\f')

      return this
    },
  },
  {
    name: 'carriageReturn',
    func() {
      this.add('\\r')

      return this
    },
  },
  {
    name: 'codeZero',
    func() {
      this.add('\\0')

      return this
    },
  },
]

*Defined in [extensions/escaped.ts:59](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/escaped.ts#L59)*

RegEx escaped characters matching methods ReX.js extension.

___
<a id="flagsextension"></a>

### `<Static>` FlagsExtension

**● FlagsExtension**: *[Method](../interfaces/method.md)<[Matcher](matcher.md)>[]* =  [
  {
    name: ['ignoreCase', 'i'],
    func() {
      this.addFlag('i')

      return this
    },
  },
  {
    name: ['globalize', 'g', 'global'],
    func() {
      this.addFlag('g')

      return this
    },
  },
  {
    name: ['extendedUnicodes', 'u'],
    func() {
      this.addFlag('u')

      return this
    },
  },
  {
    name: ['multiline', 'm'],
    func() {
      this.addFlag('m')

      return this
    },
  },
  {
    name: ['singleByIndex', 'y', 'sticky'],
    func() {
      this.addFlag('y')

      return this
    },
  },
]

*Defined in [extensions/flags.ts:43](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/flags.ts#L43)*

RegEx flags-related methods ReX.js extension.

___
<a id="groupextension"></a>

### `<Static>` GroupExtension

**● GroupExtension**: *[Method](../interfaces/method.md)<[Matcher](matcher.md)>[]* =  [
  {
    name: ['capture', 'group'],
    func(expr: string | FuncExpr<Matcher>) {
      this.add({
        expr,
        closure: {
          close: ')',
          open: '(',
        },
        negate() {
          this.setClosure({
            close: ')',
            open: '(?:',
          })
        },
      })

      return this
    },
  },
  {
    name: ['ref', 'reference'],
    func(name: string) {
      this.add(`\\k<${name}>`)

      return this
    },
  },
  {
    name: 'as',
    func(name: string) {
      const { open, close } = this.lastOperation
        ? this.lastOperation.closure
        : { open: '', close: '' }
      if (this.lastOperation && open === '(' && close === ')') {
        this.lastOperation.setClosure({
          open: `(?<${name}>`,
        })
      } else {
        if (this.lastOperation) {
          this.lastOperation.setClosure({
            open: `(?<${name}>${open}`,
            close: `${close})`,
          })
        } else {
          console.warn('No operation to be referenced - omitted!')
        }
      }

      return this
    },
  },
]

*Defined in [extensions/group.ts:32](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/group.ts#L32)*

RegEx grouping-related methods ReX.js extension.

___
<a id="lookaroundextension"></a>

### `<Static>` LookAroundExtension

**● LookAroundExtension**: *[Method](../interfaces/method.md)<[Matcher](matcher.md)>[]* =  [
  {
    name: ['follow', 'after'],
    func(expr: string | FuncExpr<Matcher>) {
      this.add({
        expr,
        closure: {
          close: ')',
          open: '(?=',
        },
        negate() {
          this.setClosure({ open: '(?!' })
        },
      })

      return this
    },
  },
  {
    name: ['precede', 'before'],
    func(expr: string | FuncExpr<Matcher>) {
      this.add({
        expr,
        closure: {
          close: ')',
          open: '(?<=',
        },
        negate() {
          this.setClosure({ open: '(?<!' })
        },
      })

      return this
    },
  },
]

*Defined in [extensions/look.ts:28](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/look.ts#L28)*

RegEx look around methods ReX.js extension.

___
<a id="quantifiersextension"></a>

### `<Static>` QuantifiersExtension

**● QuantifiersExtension**: *[Method](../interfaces/method.md)<[Matcher](matcher.md)>[]* =  [
  {
    name: ['or', 'alternative'],
    func(expr: string | FuncExpr<Matcher>) {
      this.add('|')
      this.add({
        expr,
      })

      return this
    },
  },
  {
    name: ['lazy', 'minimum'],
    func() {
      this.add('?')

      return this
    },
  },
  {
    name: ['optional', 'unnecessary', 'additional'],
    func() {
      this.add('?')

      return this
    },
  },
  {
    name: ['withLimits', 'quantify'],
    func(lowerLimit: number, upperLimit: number) {
      this.add(`{${lowerLimit},${upperLimit}}`)

      return this
    },
  },
  {
    name: ['moreOrNot', 'star'],
    func() {
      this.add('*')

      return this
    },
  },
  {
    name: ['more', 'plus'],
    func() {
      this.add('+')

      return this
    },
  },
]

*Defined in [extensions/quantifiers.ts:50](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/quantifiers.ts#L50)*

RegEx quantifiers methods ReX.js extension.

___

## Methods

<a id="add"></a>

###  add

▸ **add**(operationConfig: * [OperationConfig](../interfaces/operationconfig.md)<`this`> &#124; `string`*): `this`

*Inherited from [ReXer](rexer.md).[add](rexer.md#add)*

*Defined in [rexer.ts:38](https://github.com/areknawo/Rex/blob/cd201a2/src/rexer.ts#L38)*

Appends operation to current channel.

**Parameters:**

| Name | Type |
| ------ | ------ |
| operationConfig |  [OperationConfig](../interfaces/operationconfig.md)<`this`> &#124; `string`|

**Returns:** `this`

___
<a id="addflag"></a>

###  addFlag

▸ **addFlag**(flag: *`string`*): `this`

*Defined in [matcher.ts:114](https://github.com/areknawo/Rex/blob/cd201a2/src/matcher.ts#L114)*

Appends given flag to regEx.

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| flag | `string` |  Flag to append. |

**Returns:** `this`

___
<a id="anybutbreak"></a>

###  anyButBreak

▸ **anyButBreak**(): [Matcher](matcher.md)

*Inherited from [CharactersExtension](../interfaces/charactersextension.md).[anyButBreak](../interfaces/charactersextension.md#anybutbreak)*

*Defined in [extensions/characters.ts:12](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/characters.ts#L12)*

Matches any character except line breaks.

**Returns:** [Matcher](matcher.md)

___
<a id="anywhitespace"></a>

###  anyWhitespace

▸ **anyWhitespace**(): [Matcher](matcher.md)

*Inherited from [CharactersExtension](../interfaces/charactersextension.md).[anyWhitespace](../interfaces/charactersextension.md#anywhitespace)*

*Defined in [extensions/characters.ts:17](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/characters.ts#L17)*

Matches any whitespace character - spaces, tabs, line breaks.

**Returns:** [Matcher](matcher.md)

___
<a id="as"></a>

###  as

▸ **as**(name: *`string`*): [Matcher](matcher.md)

*Inherited from [GroupExtension](../interfaces/groupextension.md).[as](../interfaces/groupextension.md#as)*

*Defined in [extensions/group.ts:13](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/group.ts#L13)*

Sets name of preceding expression.

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| name | `string` |  Name for the previously applied expression. |

**Returns:** [Matcher](matcher.md)

___
<a id="begin"></a>

###  begin

▸ **begin**(): [Matcher](matcher.md)

*Inherited from [AnchorsExtension](../interfaces/anchorsextension.md).[begin](../interfaces/anchorsextension.md#begin)*

*Defined in [extensions/anchors.ts:11](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/anchors.ts#L11)*

Matches beginning of passed string or line ( if multiline is applied ).

**Returns:** [Matcher](matcher.md)

___
<a id="capture"></a>

###  capture

▸ **capture**(expr: * `string` &#124; [FuncExpr](../interfaces/funcexpr.md)<[Matcher](matcher.md)>*): [Matcher](matcher.md)

*Inherited from [GroupExtension](../interfaces/groupextension.md).[capture](../interfaces/groupextension.md#capture)*

*Defined in [extensions/group.ts:19](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/group.ts#L19)*

Captures multiple characters together. Negate creates group of characters but doesn't capture them.

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| expr |  `string` &#124; [FuncExpr](../interfaces/funcexpr.md)<[Matcher](matcher.md)>|  Set's body as string of characters or expression body ( function ). |

**Returns:** [Matcher](matcher.md)

___
<a id="carriagereturn"></a>

###  carriageReturn

▸ **carriageReturn**(): [Matcher](matcher.md)

*Inherited from [EscapedCharactersExtension](../interfaces/escapedcharactersextension.md).[carriageReturn](../interfaces/escapedcharactersextension.md#carriagereturn)*

*Defined in [extensions/escaped.ts:11](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/escaped.ts#L11)*

Matches carriage return character ( char code 13 ).

**Returns:** [Matcher](matcher.md)

___
<a id="codezero"></a>

###  codeZero

▸ **codeZero**(): [Matcher](matcher.md)

*Inherited from [EscapedCharactersExtension](../interfaces/escapedcharactersextension.md).[codeZero](../interfaces/escapedcharactersextension.md#codezero)*

*Defined in [extensions/escaped.ts:15](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/escaped.ts#L15)*

Matches null character ( char code 0 ).

**Returns:** [Matcher](matcher.md)

___
<a id="containsflag"></a>

###  containsFlag

▸ **containsFlag**(flag: *`string`*): `boolean`

*Defined in [matcher.ts:139](https://github.com/areknawo/Rex/blob/cd201a2/src/matcher.ts#L139)*

Checks if expression contains given flag.

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| flag | `string` |  Flag to check. |

**Returns:** `boolean`
If expression contains flag.

___
<a id="control"></a>

###  control

▸ **control**(letter: *`string`*): [Matcher](matcher.md)

*Inherited from [EscapedCharactersExtension](../interfaces/escapedcharactersextension.md).[control](../interfaces/escapedcharactersextension.md#control)*

*Defined in [extensions/escaped.ts:20](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/escaped.ts#L20)*

Matches given control escaped character.

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| letter | `string` |  Control letter ( A for char code 1 up to Z for char code 26 ) |

**Returns:** [Matcher](matcher.md)

___
<a id="createchannel"></a>

###  createChannel

▸ **createChannel**(): `number`

*Inherited from [ReXer](rexer.md).[createChannel](rexer.md#createchannel)*

*Defined in [rexer.ts:129](https://github.com/areknawo/Rex/blob/cd201a2/src/rexer.ts#L129)*

Creates new operations channel.

**Returns:** `number`
New channel's index.

___
<a id="createsnippet"></a>

###  createSnippet

▸ **createSnippet**(name: *`string`*, snippet: * [OperationConfig](../interfaces/operationconfig.md)<`this`> &#124; "string"*): `this`

*Inherited from [ReXer](rexer.md).[createSnippet](rexer.md#createsnippet)*

*Defined in [rexer.ts:85](https://github.com/areknawo/Rex/blob/cd201a2/src/rexer.ts#L85)*

Creates snippet for given operation.

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| name | `string` |  Snippet's name. |
| snippet |  [OperationConfig](../interfaces/operationconfig.md)<`this`> &#124; "string"|  Operation's snippet. |

**Returns:** `this`

___
<a id="digit"></a>

###  digit

▸ **digit**(): [Matcher](matcher.md)

*Inherited from [CharactersExtension](../interfaces/charactersextension.md).[digit](../interfaces/charactersextension.md#digit)*

*Defined in [extensions/characters.ts:22](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/characters.ts#L22)*

Matches any digit.

**Returns:** [Matcher](matcher.md)

___
<a id="end"></a>

###  end

▸ **end**(): [Matcher](matcher.md)

*Inherited from [AnchorsExtension](../interfaces/anchorsextension.md).[end](../interfaces/anchorsextension.md#end)*

*Defined in [extensions/anchors.ts:15](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/anchors.ts#L15)*

Matches ending of passed string or line ( if multiline is applied ).

**Returns:** [Matcher](matcher.md)

___
<a id="extendedunicodes"></a>

###  extendedUnicodes

▸ **extendedUnicodes**(): [Matcher](matcher.md)

*Inherited from [FlagsExtension](../interfaces/flagsextension.md).[extendedUnicodes](../interfaces/flagsextension.md#extendedunicodes)*

*Defined in [extensions/flags.ts:12](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/flags.ts#L12)*

Allows extended use of unicodes. See browser support!

**Returns:** [Matcher](matcher.md)

___
<a id="find"></a>

###  find

▸ **find**(str: *`string`*): `this`

*Defined in [matcher.ts:92](https://github.com/areknawo/Rex/blob/cd201a2/src/matcher.ts#L92)*

Inserts given expression to regEx. Standard string characters are automatically escaped.

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| str | `string` |  RegEx string to append. |

**Returns:** `this`

___
<a id="follow"></a>

###  follow

▸ **follow**(expr: * `string` &#124; [FuncExpr](../interfaces/funcexpr.md)<[Matcher](matcher.md)>*): [Matcher](matcher.md)

*Inherited from [LookAroundExtension](../interfaces/lookaroundextension.md).[follow](../interfaces/lookaroundextension.md#follow)*

*Defined in [extensions/look.ts:15](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/look.ts#L15)*

Matches group after last expression without including it in the result.

**Parameters:**

| Name | Type |
| ------ | ------ |
| expr |  `string` &#124; [FuncExpr](../interfaces/funcexpr.md)<[Matcher](matcher.md)>|

**Returns:** [Matcher](matcher.md)

___
<a id="formfeed"></a>

###  formFeed

▸ **formFeed**(): [Matcher](matcher.md)

*Inherited from [EscapedCharactersExtension](../interfaces/escapedcharactersextension.md).[formFeed](../interfaces/escapedcharactersextension.md#formfeed)*

*Defined in [extensions/escaped.ts:29](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/escaped.ts#L29)*

Matches form feed character ( char code 12 ).

**Returns:** [Matcher](matcher.md)

___
<a id="getexpr"></a>

###  getExpr

▸ **getExpr**(): `string`

*Defined in [matcher.ts:84](https://github.com/areknawo/Rex/blob/cd201a2/src/matcher.ts#L84)*

Returns constructed matching expression.

**Returns:** `string`

___
<a id="globalize"></a>

###  globalize

▸ **globalize**(): [Matcher](matcher.md)

*Inherited from [FlagsExtension](../interfaces/flagsextension.md).[globalize](../interfaces/flagsextension.md#globalize)*

*Defined in [extensions/flags.ts:17](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/flags.ts#L17)*

Allows to regiser more than 1 matches.

**Returns:** [Matcher](matcher.md)

___
<a id="hex"></a>

###  hex

▸ **hex**(hex: *`string`*): [Matcher](matcher.md)

*Inherited from [EscapedCharactersExtension](../interfaces/escapedcharactersextension.md).[hex](../interfaces/escapedcharactersextension.md#hex)*

*Defined in [extensions/escaped.ts:34](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/escaped.ts#L34)*

Matches given hexadecimal escaped character.

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| hex | `string` |  Sting of two hex digits e.g. "ff". |

**Returns:** [Matcher](matcher.md)

___
<a id="ignorecase"></a>

###  ignoreCase

▸ **ignoreCase**(): [Matcher](matcher.md)

*Inherited from [FlagsExtension](../interfaces/flagsextension.md).[ignoreCase](../interfaces/flagsextension.md#ignorecase)*

*Defined in [extensions/flags.ts:23](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/flags.ts#L23)*

Disables case sensitivity.

**Returns:** [Matcher](matcher.md)

___
<a id="insertsnippet"></a>

###  insertSnippet

▸ **insertSnippet**(name: *`string`*): `this`

*Inherited from [ReXer](rexer.md).[insertSnippet](rexer.md#insertsnippet)*

*Defined in [rexer.ts:94](https://github.com/areknawo/Rex/blob/cd201a2/src/rexer.ts#L94)*

Inserts specified snippet in expression.

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| name | `string` |  Snippet's name. |

**Returns:** `this`

___
<a id="linefeed"></a>

###  lineFeed

▸ **lineFeed**(): [Matcher](matcher.md)

*Inherited from [EscapedCharactersExtension](../interfaces/escapedcharactersextension.md).[lineFeed](../interfaces/escapedcharactersextension.md#linefeed)*

*Defined in [extensions/escaped.ts:24](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/escaped.ts#L24)*

Matches line feed character a.k.a. 'enter' ( char code 10 ).

**Returns:** [Matcher](matcher.md)

___
<a id="match"></a>

###  match

▸ **match**(str: *`string`*):  `null` &#124; [Result](../interfaces/result.md)

*Defined in [matcher.ts:48](https://github.com/areknawo/Rex/blob/cd201a2/src/matcher.ts#L48)*

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

*Defined in [matcher.ts:57](https://github.com/areknawo/Rex/blob/cd201a2/src/matcher.ts#L57)*

Matches all matches in string for regEx and returns array of result arrays.

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| str | `string` |  String to run operation against. |

**Returns:**  `null` &#124; [Result](../interfaces/result.md)[]

___
<a id="more"></a>

###  more

▸ **more**(): [Quantifier](../interfaces/quantifier.md)

*Inherited from [QuantifiersExtension](../interfaces/quantifiersextension.md).[more](../interfaces/quantifiersextension.md#more)*

*Defined in [extensions/quantifiers.ts:19](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/quantifiers.ts#L19)*

Matches 1 or more of preceding tokens.

**Returns:** [Quantifier](../interfaces/quantifier.md)

___
<a id="moreornot"></a>

###  moreOrNot

▸ **moreOrNot**(): [Quantifier](../interfaces/quantifier.md)

*Inherited from [QuantifiersExtension](../interfaces/quantifiersextension.md).[moreOrNot](../interfaces/quantifiersextension.md#moreornot)*

*Defined in [extensions/quantifiers.ts:24](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/quantifiers.ts#L24)*

Matches 0 or more of preceding tokens.

**Returns:** [Quantifier](../interfaces/quantifier.md)

___
<a id="multiline"></a>

###  multiline

▸ **multiline**(): [Matcher](matcher.md)

*Inherited from [FlagsExtension](../interfaces/flagsextension.md).[multiline](../interfaces/flagsextension.md#multiline)*

*Defined in [extensions/flags.ts:28](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/flags.ts#L28)*

Takes into account new lines.

**Returns:** [Matcher](matcher.md)

___
<a id="negate"></a>

###  negate

▸ **negate**(): `this`

*Defined in [matcher.ts:101](https://github.com/areknawo/Rex/blob/cd201a2/src/matcher.ts#L101)*

Negates last appended operation.

**Returns:** `this`

___
<a id="octal"></a>

###  octal

▸ **octal**(oct: *`string`*): [Matcher](matcher.md)

*Inherited from [EscapedCharactersExtension](../interfaces/escapedcharactersextension.md).[octal](../interfaces/escapedcharactersextension.md#octal)*

*Defined in [extensions/escaped.ts:39](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/escaped.ts#L39)*

Matches given octal escaped character.

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| oct | `string` |  Sting of three octal digits e.g. "021" with max being "377". |

**Returns:** [Matcher](matcher.md)

___
<a id="optional"></a>

###  optional

▸ **optional**(): [Matcher](matcher.md)

*Inherited from [QuantifiersExtension](../interfaces/quantifiersextension.md).[optional](../interfaces/quantifiersextension.md#optional)*

*Defined in [extensions/quantifiers.ts:29](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/quantifiers.ts#L29)*

Makes preceding token optional.

**Returns:** [Matcher](matcher.md)

___
<a id="or"></a>

###  or

▸ **or**(expr: * `string` &#124; [FuncExpr](../interfaces/funcexpr.md)<[Matcher](matcher.md)>*): [Matcher](matcher.md)

*Inherited from [QuantifiersExtension](../interfaces/quantifiersextension.md).[or](../interfaces/quantifiersextension.md#or)*

*Defined in [extensions/quantifiers.ts:37](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/quantifiers.ts#L37)*

Matches the expression before or QuantifiersExtension currently provided.

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| expr |  `string` &#124; [FuncExpr](../interfaces/funcexpr.md)<[Matcher](matcher.md)>|  *   as string of characters or expression body ( function ). |

**Returns:** [Matcher](matcher.md)

___
<a id="precede"></a>

###  precede

▸ **precede**(expr: * `string` &#124; [FuncExpr](../interfaces/funcexpr.md)<[Matcher](matcher.md)>*): [Matcher](matcher.md)

*Inherited from [LookAroundExtension](../interfaces/lookaroundextension.md).[precede](../interfaces/lookaroundextension.md#precede)*

*Defined in [extensions/look.ts:21](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/look.ts#L21)*

Matches group before last expression without including it in the result.

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| expr |  `string` &#124; [FuncExpr](../interfaces/funcexpr.md)<[Matcher](matcher.md)>|  Lookbehind body as string of characters or expression body ( function ) |

**Returns:** [Matcher](matcher.md)

___
<a id="range"></a>

###  range

▸ **range**<`T`>(start: *`T`*, end: *`T`*): [Matcher](matcher.md)

*Inherited from [CharactersExtension](../interfaces/charactersextension.md).[range](../interfaces/charactersextension.md#range)*

*Defined in [extensions/characters.ts:33](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/characters.ts#L33)*

Matches set of chararacters of same type between desired limits.

**Type parameters:**

#### T :   `string` &#124; `number`

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| start | `T` |  Range starting character. |
| end | `T` |  Range ending character of same type e.g. 1,5 or a,f |

**Returns:** [Matcher](matcher.md)

___
<a id="ref"></a>

###  ref

▸ **ref**(name: *`string`*): [Matcher](matcher.md)

*Inherited from [GroupExtension](../interfaces/groupextension.md).[ref](../interfaces/groupextension.md#ref)*

*Defined in [extensions/group.ts:26](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/group.ts#L26)*

Matches result of previous group.

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| name | `string` |  Name of expression to be referenced. Previously set by 'as()' method. |

**Returns:** [Matcher](matcher.md)

___
<a id="removeflag"></a>

###  removeFlag

▸ **removeFlag**(flag: *`string`*): `this`

*Defined in [matcher.ts:124](https://github.com/areknawo/Rex/blob/cd201a2/src/matcher.ts#L124)*

Removes given flag from regEx.

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| flag | `string` |  Flag to remove. |

**Returns:** `this`

___
<a id="repeat"></a>

###  repeat

▸ **repeat**(): `this`

*Inherited from [ReXer](rexer.md).[repeat](rexer.md#repeat)*

*Defined in [rexer.ts:48](https://github.com/areknawo/Rex/blob/cd201a2/src/rexer.ts#L48)*

Repeats last appended operation.

**Returns:** `this`

___
<a id="search"></a>

###  search

▸ **search**(str: *`string`*): `number`

*Defined in [matcher.ts:66](https://github.com/areknawo/Rex/blob/cd201a2/src/matcher.ts#L66)*

Search for match in given string. Returns beginning index of match or -1 if not found.

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| str | `string` |  String to run operation against. |

**Returns:** `number`

___
<a id="set"></a>

###  set

▸ **set**(set: * `string` &#124; `function`*): [Matcher](matcher.md)

*Inherited from [CharactersExtension](../interfaces/charactersextension.md).[set](../interfaces/charactersextension.md#set)*

*Defined in [extensions/characters.ts:38](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/characters.ts#L38)*

Matches set of characters.

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| set |  `string` &#124; `function`|  String of characters to be included in set. |

**Returns:** [Matcher](matcher.md)

___
<a id="setchannel"></a>

###  setChannel

▸ **setChannel**(channelIndex: *`number`*): `number`

*Inherited from [ReXer](rexer.md).[setChannel](rexer.md#setchannel)*

*Defined in [rexer.ts:139](https://github.com/areknawo/Rex/blob/cd201a2/src/rexer.ts#L139)*

Sets current operations channel.

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| channelIndex | `number` |  Channel index. |

**Returns:** `number`
Passed channel index.

___
<a id="singlebyindex"></a>

###  singleByIndex

▸ **singleByIndex**(): [Matcher](matcher.md)

*Inherited from [FlagsExtension](../interfaces/flagsextension.md).[singleByIndex](../interfaces/flagsextension.md#singlebyindex)*

*Defined in [extensions/flags.ts:35](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/flags.ts#L35)*

Register only one match, starting from selected index. Automatically ignores 'globalize()' function See browser support!

**Returns:** [Matcher](matcher.md)

___
<a id="split"></a>

###  split

▸ **split**(str: *`string`*, n?: * `undefined` &#124; `number`*): `string`[]

*Defined in [matcher.ts:76](https://github.com/areknawo/Rex/blob/cd201a2/src/matcher.ts#L76)*

Splits the string in places that match regEx.

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| str | `string` |  String to run operation against. |
| `Optional` n |  `undefined` &#124; `number`|  How many times to split the string - minimum 1 |

**Returns:** `string`[]

___
<a id="stringifychannel"></a>

###  stringifyChannel

▸ **stringifyChannel**(channelIndex: *`number`*): `string`

*Inherited from [ReXer](rexer.md).[stringifyChannel](rexer.md#stringifychannel)*

*Defined in [rexer.ts:116](https://github.com/areknawo/Rex/blob/cd201a2/src/rexer.ts#L116)*

Creates string from channel's operations.

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| channelIndex | `number` |  Channel index. |

**Returns:** `string`
All operation in given channel in form of string.

___
<a id="stringifyexpression"></a>

###  stringifyExpression

▸ **stringifyExpression**(expr: *[FuncExpr](../interfaces/funcexpr.md)<`this`>*): `string`

*Inherited from [ReXer](rexer.md).[stringifyExpression](rexer.md#stringifyexpression)*

*Defined in [rexer.ts:103](https://github.com/areknawo/Rex/blob/cd201a2/src/rexer.ts#L103)*

Creates string from function expression.

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| expr | [FuncExpr](../interfaces/funcexpr.md)<`this`> |  Function expression. |

**Returns:** `string`

___
<a id="tab"></a>

###  tab

▸ **tab**(): [Matcher](matcher.md)

*Inherited from [EscapedCharactersExtension](../interfaces/escapedcharactersextension.md).[tab](../interfaces/escapedcharactersextension.md#tab)*

*Defined in [extensions/escaped.ts:43](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/escaped.ts#L43)*

Matches tab character ( char code 9 ).

**Returns:** [Matcher](matcher.md)

___
<a id="test"></a>

###  test

▸ **test**(str: *`string`*): `boolean`

*Defined in [matcher.ts:38](https://github.com/areknawo/Rex/blob/cd201a2/src/matcher.ts#L38)*

Tests string against regEx and returns boolean if matched. Similar to 'RegExp.test()' method.

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| str | `string` |  String to run operation against. |

**Returns:** `boolean`

___
<a id="unicode"></a>

###  unicode

▸ **unicode**(code: *`string`*): [Matcher](matcher.md)

*Inherited from [EscapedCharactersExtension](../interfaces/escapedcharactersextension.md).[unicode](../interfaces/escapedcharactersextension.md#unicode)*

*Defined in [extensions/escaped.ts:48](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/escaped.ts#L48)*

Matches given unicode escaped character.

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| code | `string` |  Sting of four ( can be more with extendedUnicodes applied ) hex digits. |

**Returns:** [Matcher](matcher.md)

___
<a id="useextension"></a>

###  useExtension

▸ **useExtension**<`T`>(ext: *[Method](../interfaces/method.md)<`T`>[]*): `void`

*Inherited from [ReXer](rexer.md).[useExtension](rexer.md#useextension)*

*Defined in [rexer.ts:75](https://github.com/areknawo/Rex/blob/cd201a2/src/rexer.ts#L75)*

Appends array of extension method to ReXer for their later reuse.

**Type parameters:**

#### T :  [ReXer](rexer.md)
**Parameters:**

| Name | Type |
| ------ | ------ |
| ext | [Method](../interfaces/method.md)<`T`>[] |

**Returns:** `void`

___
<a id="usemethod"></a>

###  useMethod

▸ **useMethod**<`T`>(method: *[Method](../interfaces/method.md)<`T`>*): `void`

*Inherited from [ReXer](rexer.md).[useMethod](rexer.md#usemethod)*

*Defined in [rexer.ts:61](https://github.com/areknawo/Rex/blob/cd201a2/src/rexer.ts#L61)*

Appends extension method to ReXer for its later reuse.

**Type parameters:**

#### T :  [ReXer](rexer.md)
**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| method | [Method](../interfaces/method.md)<`T`> |  Extension method. |

**Returns:** `void`

___
<a id="verticaltab"></a>

###  verticalTab

▸ **verticalTab**(): [Matcher](matcher.md)

*Inherited from [EscapedCharactersExtension](../interfaces/escapedcharactersextension.md).[verticalTab](../interfaces/escapedcharactersextension.md#verticaltab)*

*Defined in [extensions/escaped.ts:52](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/escaped.ts#L52)*

Matches vertical tab character ( char code 11 ).

**Returns:** [Matcher](matcher.md)

___
<a id="withlimits"></a>

###  withLimits

▸ **withLimits**(lowerLimit: *`number`*, upperLimit: *`number`*): [Quantifier](../interfaces/quantifier.md)

*Inherited from [QuantifiersExtension](../interfaces/quantifiersextension.md).[withLimits](../interfaces/quantifiersextension.md#withlimits)*

*Defined in [extensions/quantifiers.ts:44](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/quantifiers.ts#L44)*

Matches more of preceding tokens within given limits.

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| lowerLimit | `number` |  Lowest number of tokens to match. |
| upperLimit | `number` |  Highest number of tokens to match. |

**Returns:** [Quantifier](../interfaces/quantifier.md)

___
<a id="wordboundary"></a>

###  wordBoundary

▸ **wordBoundary**(): [Matcher](matcher.md)

*Inherited from [AnchorsExtension](../interfaces/anchorsextension.md).[wordBoundary](../interfaces/anchorsextension.md#wordboundary)*

*Defined in [extensions/anchors.ts:19](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/anchors.ts#L19)*

States that match starts with non-word character e.g. space, -, tab etc.

**Returns:** [Matcher](matcher.md)

___
<a id="wordchar"></a>

###  wordChar

▸ **wordChar**(): [Matcher](matcher.md)

*Inherited from [CharactersExtension](../interfaces/charactersextension.md).[wordChar](../interfaces/charactersextension.md#wordchar)*

*Defined in [extensions/characters.ts:26](https://github.com/areknawo/Rex/blob/cd201a2/src/extensions/characters.ts#L26)*

Matches any word character - upper & lower case letters, numbers and underscores.

**Returns:** [Matcher](matcher.md)

___

