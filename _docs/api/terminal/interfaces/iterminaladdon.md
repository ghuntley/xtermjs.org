---
title: ITerminalAddon
category: API-interfaces
layout: docs
---


# Interface: ITerminalAddon

An addon that can provide additional functionality to the terminal.

## Hierarchy

* [IDisposable]({% link _docs/api/terminal/interfaces/idisposable.md %})

  ↳ **ITerminalAddon**

## Index

### Methods

* [activate]({% link _docs/api/terminal/interfaces/iterminaladdon.md %}#activate)
* [dispose]({% link _docs/api/terminal/interfaces/iterminaladdon.md %}#dispose)

## Methods

###  activate

▸ **activate**(`terminal`: [Terminal]({% link _docs/api/terminal/classes/terminal.md %})): *void*

*Defined in [xterm.d.ts:1059](https://github.com/xtermjs/xterm.js/blob/4.10.0/typings/xterm.d.ts#L1059)*

This is called when the addon is activated.

**Parameters:**

Name | Type |
------ | ------ |
`terminal` | [Terminal]({% link _docs/api/terminal/classes/terminal.md %}) |

**Returns:** *void*

___

###  dispose

▸ **dispose**(): *void*

*Inherited from [IDisposable]({% link _docs/api/terminal/interfaces/idisposable.md %}).[dispose]({% link _docs/api/terminal/interfaces/idisposable.md %}#dispose)*

*Defined in [xterm.d.ts:359](https://github.com/xtermjs/xterm.js/blob/4.10.0/typings/xterm.d.ts#L359)*

**Returns:** *void*
