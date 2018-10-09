

# Type aliases

<a id="loadpluginoptions"></a>

##  LoadPluginOptions

**Ƭ LoadPluginOptions**: *`object`*

*Defined in [host/factory.ts:25](https://github.com/neovim/node-client/blob/97a65c6/src/host/factory.ts#L25)*

#### Type declaration

`Optional`  cache: `boolean`

___

# Variables

<a id="module"></a>

## `<Const>` Module

**● Module**: *[IModule](../interfaces/_host_factory_.imodule.md)* =  require('module')

*Defined in [host/factory.ts:29](https://github.com/neovim/node-client/blob/97a65c6/src/host/factory.ts#L29)*

___
<a id="removed_globals"></a>

## `<Const>` REMOVED_GLOBALS

**● REMOVED_GLOBALS**: *`string`[]* =  [
  'reallyExit',
  'abort',
  'chdir',
  'umask',
  'setuid',
  'setgid',
  'setgroups',
  '_kill',
  'EventEmitter',
  '_maxListeners',
  '_fatalException',
  'exit',
  'kill',
]

*Defined in [host/factory.ts:31](https://github.com/neovim/node-client/blob/97a65c6/src/host/factory.ts#L31)*

___

# Functions

<a id="compileinsandbox"></a>

##  compileInSandbox

▸ **compileInSandbox**(sandbox: *[ISandbox](../interfaces/_host_factory_.isandbox.md)*): `(Anonymous function)`

*Defined in [host/factory.ts:65](https://github.com/neovim/node-client/blob/97a65c6/src/host/factory.ts#L65)*

**Parameters:**

| Param | Type |
| ------ | ------ |
| sandbox | [ISandbox](../interfaces/_host_factory_.isandbox.md) |

**Returns:** `(Anonymous function)`

___
<a id="createdebugfunction"></a>

##  createDebugFunction

▸ **createDebugFunction**(filename: *`string`*): `(Anonymous function)`

*Defined in [host/factory.ts:80](https://github.com/neovim/node-client/blob/97a65c6/src/host/factory.ts#L80)*

**Parameters:**

| Param | Type |
| ------ | ------ |
| filename | `string` |

**Returns:** `(Anonymous function)`

___
<a id="createplugin"></a>

##  createPlugin

▸ **createPlugin**(filename: *`string`*, nvim: *[Neovim](../classes/_api_neovim_.neovim.md)*, options?: *[LoadPluginOptions](_host_factory_.md#loadpluginoptions)*):  [NvimPlugin](../classes/_host_nvimplugin_.nvimplugin.md) &#124; `null`

*Defined in [host/factory.ts:149](https://github.com/neovim/node-client/blob/97a65c6/src/host/factory.ts#L149)*

**Parameters:**

| Param | Type | Default value |
| ------ | ------ | ------ |
| filename | `string` | - |
| nvim | [Neovim](../classes/_api_neovim_.neovim.md) | - |
| `Default value` options | [LoadPluginOptions](_host_factory_.md#loadpluginoptions) |  {} |

**Returns:**  [NvimPlugin](../classes/_host_nvimplugin_.nvimplugin.md) &#124; `null`

___
<a id="createsandbox"></a>

##  createSandbox

▸ **createSandbox**(filename: *`string`*): [ISandbox](../interfaces/_host_factory_.isandbox.md)

*Defined in [host/factory.ts:95](https://github.com/neovim/node-client/blob/97a65c6/src/host/factory.ts#L95)*

**Parameters:**

| Param | Type |
| ------ | ------ |
| filename | `string` |

**Returns:** [ISandbox](../interfaces/_host_factory_.isandbox.md)

___
<a id="loadplugin"></a>

##  loadPlugin

▸ **loadPlugin**(filename: *`string`*, nvim: *[Neovim](../classes/_api_neovim_.neovim.md)*, options?: *[LoadPluginOptions](_host_factory_.md#loadpluginoptions)*): [NvimPlugin](../classes/_host_nvimplugin_.nvimplugin.md)

*Defined in [host/factory.ts:184](https://github.com/neovim/node-client/blob/97a65c6/src/host/factory.ts#L184)*

**Parameters:**

| Param | Type | Default value |
| ------ | ------ | ------ |
| filename | `string` | - |
| nvim | [Neovim](../classes/_api_neovim_.neovim.md) | - |
| `Default value` options | [LoadPluginOptions](_host_factory_.md#loadpluginoptions) |  {} |

**Returns:** [NvimPlugin](../classes/_host_nvimplugin_.nvimplugin.md)

___
<a id="makerequirefunction"></a>

##  makeRequireFunction

▸ **makeRequireFunction**(): `any`

*Defined in [host/factory.ts:54](https://github.com/neovim/node-client/blob/97a65c6/src/host/factory.ts#L54)*

**Returns:** `any`

___
<a id="removedglobalstub"></a>

##  removedGlobalStub

▸ **removedGlobalStub**(name: *`string`*): `(Anonymous function)`

*Defined in [host/factory.ts:47](https://github.com/neovim/node-client/blob/97a65c6/src/host/factory.ts#L47)*

**Parameters:**

| Param | Type |
| ------ | ------ |
| name | `string` |

**Returns:** `(Anonymous function)`

___

