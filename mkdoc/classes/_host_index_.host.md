

# Hierarchy

**Host**

# Constructors

<a id="constructor"></a>

##  constructor

⊕ **new Host**(): [Host](_host_index_.host.md)

*Defined in [host/index.ts:13](https://github.com/neovim/node-client/blob/97a65c6/src/host/index.ts#L13)*

**Returns:** [Host](_host_index_.host.md)

___

# Properties

<a id="loaded"></a>

##  loaded

**● loaded**: *`object`*

*Defined in [host/index.ts:12](https://github.com/neovim/node-client/blob/97a65c6/src/host/index.ts#L12)*

#### Type declaration

[index: `string`]: [NvimPlugin](_host_nvimplugin_.nvimplugin.md)

___
<a id="nvim"></a>

##  nvim

**● nvim**: *`any`*

*Defined in [host/index.ts:13](https://github.com/neovim/node-client/blob/97a65c6/src/host/index.ts#L13)*

___

# Methods

<a id="getplugin"></a>

##  getPlugin

▸ **getPlugin**(filename: *`string`*, options?: *[LoadPluginOptions](../modules/_host_factory_.md#loadpluginoptions)*): [NvimPlugin](_host_nvimplugin_.nvimplugin.md)

*Defined in [host/index.ts:22](https://github.com/neovim/node-client/blob/97a65c6/src/host/index.ts#L22)*

**Parameters:**

| Param | Type | Default value |
| ------ | ------ | ------ |
| filename | `string` | - |
| `Default value` options | [LoadPluginOptions](../modules/_host_factory_.md#loadpluginoptions) |  {} |

**Returns:** [NvimPlugin](_host_nvimplugin_.nvimplugin.md)

___
<a id="handleplugin"></a>

##  handlePlugin

▸ **handlePlugin**(method: *`string`*, args: *`any`[]*): `Promise`<`any`>

*Defined in [host/index.ts:44](https://github.com/neovim/node-client/blob/97a65c6/src/host/index.ts#L44)*

**Parameters:**

| Param | Type |
| ------ | ------ |
| method | `string` |
| args | `any`[] |

**Returns:** `Promise`<`any`>

___
<a id="handlerequestspecs"></a>

##  handleRequestSpecs

▸ **handleRequestSpecs**(method: *`string`*, args: *`any`[]*, res: *[Response](../interfaces/_host_index_.response.md)*): `void`

*Defined in [host/index.ts:77](https://github.com/neovim/node-client/blob/97a65c6/src/host/index.ts#L77)*

**Parameters:**

| Param | Type |
| ------ | ------ |
| method | `string` |
| args | `any`[] |
| res | [Response](../interfaces/_host_index_.response.md) |

**Returns:** `void`

___
<a id="handler"></a>

##  handler

▸ **handler**(method: *`string`*, args: *`any`[]*, res: *[Response](../interfaces/_host_index_.response.md)*): `Promise`<`void`>

*Defined in [host/index.ts:88](https://github.com/neovim/node-client/blob/97a65c6/src/host/index.ts#L88)*

**Parameters:**

| Param | Type |
| ------ | ------ |
| method | `string` |
| args | `any`[] |
| res | [Response](../interfaces/_host_index_.response.md) |

**Returns:** `Promise`<`void`>

___
<a id="start"></a>

##  start

▸ **start**(__namedParameters: *`object`*): `Promise`<`void`>

*Defined in [host/index.ts:110](https://github.com/neovim/node-client/blob/97a65c6/src/host/index.ts#L110)*

**Parameters:**

**__namedParameters: `object`**

| Param | Type |
| ------ | ------ |
| proc | `Process` |

**Returns:** `Promise`<`void`>

___

