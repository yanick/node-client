

# Hierarchy

**NvimPlugin**

# Constructors

<a id="constructor"></a>

##  constructor

⊕ **new NvimPlugin**(filename: *`string`*, plugin: *`any`*, nvim: *[Neovim](_api_neovim_.neovim.md)*): [NvimPlugin](_host_nvimplugin_.nvimplugin.md)

*Defined in [host/NvimPlugin.ts:61](https://github.com/neovim/node-client/blob/97a65c6/src/host/NvimPlugin.ts#L61)*

**Parameters:**

| Param | Type |
| ------ | ------ |
| filename | `string` |
| plugin | `any` |
| nvim | [Neovim](_api_neovim_.neovim.md) |

**Returns:** [NvimPlugin](_host_nvimplugin_.nvimplugin.md)

___

# Properties

<a id="alwaysinit"></a>

##  alwaysInit

**● alwaysInit**: *`boolean`*

*Defined in [host/NvimPlugin.ts:57](https://github.com/neovim/node-client/blob/97a65c6/src/host/NvimPlugin.ts#L57)*

___
<a id="autocmds"></a>

##  autocmds

**● autocmds**: *`object`*

*Defined in [host/NvimPlugin.ts:59](https://github.com/neovim/node-client/blob/97a65c6/src/host/NvimPlugin.ts#L59)*

#### Type declaration

[index: `string`]: [Handler](../interfaces/_host_nvimplugin_.handler.md)

___
<a id="commands"></a>

##  commands

**● commands**: *`object`*

*Defined in [host/NvimPlugin.ts:60](https://github.com/neovim/node-client/blob/97a65c6/src/host/NvimPlugin.ts#L60)*

#### Type declaration

[index: `string`]: [Handler](../interfaces/_host_nvimplugin_.handler.md)

___
<a id="dev"></a>

##  dev

**● dev**: *`boolean`*

*Defined in [host/NvimPlugin.ts:56](https://github.com/neovim/node-client/blob/97a65c6/src/host/NvimPlugin.ts#L56)*

___
<a id="filename"></a>

##  filename

**● filename**: *`string`*

*Defined in [host/NvimPlugin.ts:52](https://github.com/neovim/node-client/blob/97a65c6/src/host/NvimPlugin.ts#L52)*

___
<a id="functions"></a>

##  functions

**● functions**: *`object`*

*Defined in [host/NvimPlugin.ts:61](https://github.com/neovim/node-client/blob/97a65c6/src/host/NvimPlugin.ts#L61)*

#### Type declaration

[index: `string`]: [Handler](../interfaces/_host_nvimplugin_.handler.md)

___
<a id="instance"></a>

##  instance

**● instance**: *`any`*

*Defined in [host/NvimPlugin.ts:54](https://github.com/neovim/node-client/blob/97a65c6/src/host/NvimPlugin.ts#L54)*

___
<a id="nvim"></a>

##  nvim

**● nvim**: *[Neovim](_api_neovim_.neovim.md)*

*Defined in [host/NvimPlugin.ts:53](https://github.com/neovim/node-client/blob/97a65c6/src/host/NvimPlugin.ts#L53)*

___

# Accessors

<a id="shouldcachemodule"></a>

##  shouldCacheModule

getshouldCacheModule(): `boolean`

*Defined in [host/NvimPlugin.ts:91](https://github.com/neovim/node-client/blob/97a65c6/src/host/NvimPlugin.ts#L91)*

**Returns:** `boolean`

___
<a id="specs"></a>

##  specs

getspecs(): [Spec](../modules/_types_spec_.md#spec)[]

*Defined in [host/NvimPlugin.ts:194](https://github.com/neovim/node-client/blob/97a65c6/src/host/NvimPlugin.ts#L194)*

**Returns:** [Spec](../modules/_types_spec_.md#spec)[]

___

# Methods

<a id="handlerequest"></a>

##  handleRequest

▸ **handleRequest**(name: *`string`*, type: *`string`*, args: *`any`[]*): `Promise`<`any`>

*Defined in [host/NvimPlugin.ts:207](https://github.com/neovim/node-client/blob/97a65c6/src/host/NvimPlugin.ts#L207)*

**Parameters:**

| Param | Type |
| ------ | ------ |
| name | `string` |
| type | `string` |
| args | `any`[] |

**Returns:** `Promise`<`any`>

___
<a id="registerautocmd"></a>

##  registerAutocmd

▸ **registerAutocmd**(name: *`string`*, fn: *`Function`*, options: *[AutocmdOptions](../interfaces/_host_nvimplugin_.autocmdoptions.md)*): `void`

▸ **registerAutocmd**(name: *`string`*, fn: *[`any`, `Function`]*, options: *[AutocmdOptions](../interfaces/_host_nvimplugin_.autocmdoptions.md)*): `void`

*Defined in [host/NvimPlugin.ts:95](https://github.com/neovim/node-client/blob/97a65c6/src/host/NvimPlugin.ts#L95)*

**Parameters:**

| Param | Type |
| ------ | ------ |
| name | `string` |
| fn | `Function` |
| options | [AutocmdOptions](../interfaces/_host_nvimplugin_.autocmdoptions.md) |

**Returns:** `void`

*Defined in [host/NvimPlugin.ts:96](https://github.com/neovim/node-client/blob/97a65c6/src/host/NvimPlugin.ts#L96)*

**Parameters:**

| Param | Type |
| ------ | ------ |
| name | `string` |
| fn | [`any`, `Function`] |
| options | [AutocmdOptions](../interfaces/_host_nvimplugin_.autocmdoptions.md) |

**Returns:** `void`

___
<a id="registercommand"></a>

##  registerCommand

▸ **registerCommand**(name: *`string`*, fn: *`Function`*, options?: *[CommandOptions](../interfaces/_host_nvimplugin_.commandoptions.md)*): `void`

▸ **registerCommand**(name: *`string`*, fn: *[`any`, `Function`]*, options?: *[CommandOptions](../interfaces/_host_nvimplugin_.commandoptions.md)*): `void`

*Defined in [host/NvimPlugin.ts:130](https://github.com/neovim/node-client/blob/97a65c6/src/host/NvimPlugin.ts#L130)*

**Parameters:**

| Param | Type |
| ------ | ------ |
| name | `string` |
| fn | `Function` |
| `Optional` options | [CommandOptions](../interfaces/_host_nvimplugin_.commandoptions.md) |

**Returns:** `void`

*Defined in [host/NvimPlugin.ts:131](https://github.com/neovim/node-client/blob/97a65c6/src/host/NvimPlugin.ts#L131)*

**Parameters:**

| Param | Type |
| ------ | ------ |
| name | `string` |
| fn | [`any`, `Function`] |
| `Optional` options | [CommandOptions](../interfaces/_host_nvimplugin_.commandoptions.md) |

**Returns:** `void`

___
<a id="registerfunction"></a>

##  registerFunction

▸ **registerFunction**(name: *`string`*, fn: *`Function`*, options?: *[NvimFunctionOptions](../interfaces/_host_nvimplugin_.nvimfunctionoptions.md)*): `void`

▸ **registerFunction**(name: *`string`*, fn: *[`any`, `Function`]*, options?: *[NvimFunctionOptions](../interfaces/_host_nvimplugin_.nvimfunctionoptions.md)*): `void`

*Defined in [host/NvimPlugin.ts:160](https://github.com/neovim/node-client/blob/97a65c6/src/host/NvimPlugin.ts#L160)*

**Parameters:**

| Param | Type |
| ------ | ------ |
| name | `string` |
| fn | `Function` |
| `Optional` options | [NvimFunctionOptions](../interfaces/_host_nvimplugin_.nvimfunctionoptions.md) |

**Returns:** `void`

*Defined in [host/NvimPlugin.ts:165](https://github.com/neovim/node-client/blob/97a65c6/src/host/NvimPlugin.ts#L165)*

**Parameters:**

| Param | Type |
| ------ | ------ |
| name | `string` |
| fn | [`any`, `Function`] |
| `Optional` options | [NvimFunctionOptions](../interfaces/_host_nvimplugin_.nvimfunctionoptions.md) |

**Returns:** `void`

___
<a id="setoptions"></a>

##  setOptions

▸ **setOptions**(options: *[NvimPluginOptions](../interfaces/_host_nvimplugin_.nvimpluginoptions.md)*): `void`

*Defined in [host/NvimPlugin.ts:85](https://github.com/neovim/node-client/blob/97a65c6/src/host/NvimPlugin.ts#L85)*

**Parameters:**

| Param | Type |
| ------ | ------ |
| options | [NvimPluginOptions](../interfaces/_host_nvimplugin_.nvimpluginoptions.md) |

**Returns:** `void`

___

