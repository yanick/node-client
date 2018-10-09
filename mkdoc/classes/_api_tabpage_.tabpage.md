

# Hierarchy

↳  [BaseApi](_api_base_.baseapi.md)

**↳ Tabpage**

↳  [AsyncTabpage](../interfaces/_api_tabpage_.asynctabpage.md)

# Constructors

<a id="constructor"></a>

##  constructor

⊕ **new Tabpage**(__namedParameters: *`object`*): [Tabpage](_api_tabpage_.tabpage.md)

*Inherited from [BaseApi](_api_base_.baseapi.md).[constructor](_api_base_.baseapi.md#constructor)*

*Defined in [api/Base.ts:33](https://github.com/neovim/node-client/blob/97a65c6/src/api/Base.ts#L33)*

**Parameters:**

**__namedParameters: `object`**

| Param | Type |
| ------ | ------ |
| client | `any` |
| data | `Buffer` |
| logger | `LoggerInstance` |
| metadata | `any` |
| transport | [Transport](_utils_transport_.transport.md) |

**Returns:** [Tabpage](_api_tabpage_.tabpage.md)

___

# Properties

<a id="_isready"></a>

## `<Protected>` _isReady

**● _isReady**: *`Promise`<`boolean`>*

*Inherited from [BaseApi](_api_base_.baseapi.md).[_isReady](_api_base_.baseapi.md#_isready)*

*Defined in [api/Base.ts:29](https://github.com/neovim/node-client/blob/97a65c6/src/api/Base.ts#L29)*

___
<a id="client"></a>

## `<Protected>` client

**● client**: *`any`*

*Inherited from [BaseApi](_api_base_.baseapi.md).[client](_api_base_.baseapi.md#client)*

*Defined in [api/Base.ts:33](https://github.com/neovim/node-client/blob/97a65c6/src/api/Base.ts#L33)*

___
<a id="data"></a>

##  data

**● data**: * `Buffer` &#124; `Number`
*

*Inherited from [BaseApi](_api_base_.baseapi.md).[data](_api_base_.baseapi.md#data)*

*Defined in [api/Base.ts:32](https://github.com/neovim/node-client/blob/97a65c6/src/api/Base.ts#L32)*

___
<a id="logger"></a>

##  logger

**● logger**: *[ILogger](../modules/_utils_logger_.md#ilogger)*

*Inherited from [BaseApi](_api_base_.baseapi.md).[logger](_api_base_.baseapi.md#logger)*

*Defined in [api/Base.ts:31](https://github.com/neovim/node-client/blob/97a65c6/src/api/Base.ts#L31)*

___
<a id="prefix"></a>

##  prefix

**● prefix**: *`string`* =  Metadata[ExtType.Tabpage].prefix

*Overrides [BaseApi](_api_base_.baseapi.md).[prefix](_api_base_.baseapi.md#prefix)*

*Defined in [api/Tabpage.ts:7](https://github.com/neovim/node-client/blob/97a65c6/src/api/Tabpage.ts#L7)*

___
<a id="transport"></a>

## `<Protected>` transport

**● transport**: *[Transport](_utils_transport_.transport.md)*

*Inherited from [BaseApi](_api_base_.baseapi.md).[transport](_api_base_.baseapi.md#transport)*

*Defined in [api/Base.ts:28](https://github.com/neovim/node-client/blob/97a65c6/src/api/Base.ts#L28)*

___
<a id="defaultmaxlisteners"></a>

## `<Static>` defaultMaxListeners

**● defaultMaxListeners**: *`number`*

*Inherited from EventEmitter.defaultMaxListeners*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:712*

___

# Accessors

<a id="number"></a>

##  number

getnumber(): `Promise`<`number`>

*Defined in [api/Tabpage.ts:28](https://github.com/neovim/node-client/blob/97a65c6/src/api/Tabpage.ts#L28)*

Tabpage number

**Returns:** `Promise`<`number`>

___
<a id="valid"></a>

##  valid

getvalid(): `Promise`<`boolean`>

*Defined in [api/Tabpage.ts:23](https://github.com/neovim/node-client/blob/97a65c6/src/api/Tabpage.ts#L23)*

Is current tabpage valid

**Returns:** `Promise`<`boolean`>

___
<a id="window"></a>

##  window

getwindow(): [AsyncWindow](../interfaces/_api_window_.asyncwindow.md)

*Defined in [api/Tabpage.ts:15](https://github.com/neovim/node-client/blob/97a65c6/src/api/Tabpage.ts#L15)*

Gets the current window of tabpage

**Returns:** [AsyncWindow](../interfaces/_api_window_.asyncwindow.md)

___
<a id="windows"></a>

##  windows

getwindows(): `Promise`<[Window](_api_window_.window.md)[]>

*Defined in [api/Tabpage.ts:10](https://github.com/neovim/node-client/blob/97a65c6/src/api/Tabpage.ts#L10)*

Returns all windows of tabpage

**Returns:** `Promise`<[Window](_api_window_.window.md)[]>

___

# Methods

<a id="__computed"></a>

##  __computed

▸ **__computed**(name: *`string`*, args?: *`any`[]*): `Promise`<`any`>

*Inherited from [BaseApi](_api_base_.baseapi.md).[__computed](_api_base_.baseapi.md#__computed)*

*Defined in [api/Base.ts:66](https://github.com/neovim/node-client/blob/97a65c6/src/api/Base.ts#L66)*

**Parameters:**

| Param | Type | Default value |
| ------ | ------ | ------ |
| name | `string` | - |
| `Default value` args | `any`[] |  [] |

**Returns:** `Promise`<`any`>

___
<a id="_getargsbyprefix"></a>

##  _getArgsByPrefix

▸ **_getArgsByPrefix**(...args: *`any`[]*): `this`[]

*Inherited from [BaseApi](_api_base_.baseapi.md).[_getArgsByPrefix](_api_base_.baseapi.md#_getargsbyprefix)*

*Defined in [api/Base.ts:89](https://github.com/neovim/node-client/blob/97a65c6/src/api/Base.ts#L89)*

**Parameters:**

| Param | Type |
| ------ | ------ |
| `Rest` args | `any`[] |

**Returns:** `this`[]

___
<a id="addlistener"></a>

##  addListener

▸ **addListener**(event: * `string` &#124; `symbol`*, listener: *`Function`*): `this`

*Inherited from EventEmitter.addListener*

*Overrides EventEmitter.addListener*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:714*

**Parameters:**

| Param | Type |
| ------ | ------ |
| event |  `string` &#124; `symbol`|
| listener | `Function` |

**Returns:** `this`

___
<a id="deletevar"></a>

##  deleteVar

▸ **deleteVar**(name: *`string`*): `Promise`<`void`>

*Inherited from [BaseApi](_api_base_.baseapi.md).[deleteVar](_api_base_.baseapi.md#deletevar)*

*Defined in [api/Base.ts:121](https://github.com/neovim/node-client/blob/97a65c6/src/api/Base.ts#L121)*

Delete a scoped variable

**Parameters:**

| Param | Type |
| ------ | ------ |
| name | `string` |

**Returns:** `Promise`<`void`>

___
<a id="emit"></a>

##  emit

▸ **emit**(event: * `string` &#124; `symbol`*, ...args: *`any`[]*): `boolean`

*Inherited from EventEmitter.emit*

*Overrides EventEmitter.emit*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:724*

**Parameters:**

| Param | Type |
| ------ | ------ |
| event |  `string` &#124; `symbol`|
| `Rest` args | `any`[] |

**Returns:** `boolean`

___
<a id="equals"></a>

##  equals

▸ **equals**(other: *[BaseApi](_api_base_.baseapi.md)*): `boolean`

*Inherited from [BaseApi](_api_base_.baseapi.md).[equals](_api_base_.baseapi.md#equals)*

*Defined in [api/Base.ts:58](https://github.com/neovim/node-client/blob/97a65c6/src/api/Base.ts#L58)*

**Parameters:**

| Param | Type |
| ------ | ------ |
| other | [BaseApi](_api_base_.baseapi.md) |

**Returns:** `boolean`

___
<a id="eventnames"></a>

##  eventNames

▸ **eventNames**(): ( `string` &#124; `symbol`)[]

*Inherited from EventEmitter.eventNames*

*Overrides EventEmitter.eventNames*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:725*

**Returns:** ( `string` &#124; `symbol`)[]

___
<a id="getmaxlisteners"></a>

##  getMaxListeners

▸ **getMaxListeners**(): `number`

*Inherited from EventEmitter.getMaxListeners*

*Overrides EventEmitter.getMaxListeners*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:722*

**Returns:** `number`

___
<a id="getoption"></a>

##  getOption

▸ **getOption**(): `void`

*Overrides [BaseApi](_api_base_.baseapi.md).[getOption](_api_base_.baseapi.md#getoption)*

*Defined in [api/Tabpage.ts:33](https://github.com/neovim/node-client/blob/97a65c6/src/api/Tabpage.ts#L33)*

Invalid

**Returns:** `void`

___
<a id="getvar"></a>

##  getVar

▸ **getVar**(name: *`string`*): `Promise`<[VimValue](../modules/_types_vimvalue_.md#vimvalue)>

*Inherited from [BaseApi](_api_base_.baseapi.md).[getVar](_api_base_.baseapi.md#getvar)*

*Defined in [api/Base.ts:100](https://github.com/neovim/node-client/blob/97a65c6/src/api/Base.ts#L100)*

Retrieves a scoped variable depending on type (using `this.prefix`)

**Parameters:**

| Param | Type |
| ------ | ------ |
| name | `string` |

**Returns:** `Promise`<[VimValue](../modules/_types_vimvalue_.md#vimvalue)>

___
<a id="listenercount"></a>

##  listenerCount

▸ **listenerCount**(type: * `string` &#124; `symbol`*): `number`

*Inherited from EventEmitter.listenerCount*

*Overrides EventEmitter.listenerCount*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:726*

**Parameters:**

| Param | Type |
| ------ | ------ |
| type |  `string` &#124; `symbol`|

**Returns:** `number`

___
<a id="listeners"></a>

##  listeners

▸ **listeners**(event: * `string` &#124; `symbol`*): `Function`[]

*Inherited from EventEmitter.listeners*

*Overrides EventEmitter.listeners*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:723*

**Parameters:**

| Param | Type |
| ------ | ------ |
| event |  `string` &#124; `symbol`|

**Returns:** `Function`[]

___
<a id="notify"></a>

##  notify

▸ **notify**(name: *`string`*, args: *`any`[]*): `void`

*Inherited from [BaseApi](_api_base_.baseapi.md).[notify](_api_base_.baseapi.md#notify)*

*Defined in [api/Base.ts:140](https://github.com/neovim/node-client/blob/97a65c6/src/api/Base.ts#L140)*

`request` is basically the same except you can choose to wait forpromise to be resolved

**Parameters:**

| Param | Type |
| ------ | ------ |
| name | `string` |
| args | `any`[] |

**Returns:** `void`

___
<a id="on"></a>

##  on

▸ **on**(event: * `string` &#124; `symbol`*, listener: *`Function`*): `this`

*Inherited from EventEmitter.on*

*Overrides EventEmitter.on*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:715*

**Parameters:**

| Param | Type |
| ------ | ------ |
| event |  `string` &#124; `symbol`|
| listener | `Function` |

**Returns:** `this`

___
<a id="once"></a>

##  once

▸ **once**(event: * `string` &#124; `symbol`*, listener: *`Function`*): `this`

*Inherited from EventEmitter.once*

*Overrides EventEmitter.once*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:716*

**Parameters:**

| Param | Type |
| ------ | ------ |
| event |  `string` &#124; `symbol`|
| listener | `Function` |

**Returns:** `this`

___
<a id="prependlistener"></a>

##  prependListener

▸ **prependListener**(event: * `string` &#124; `symbol`*, listener: *`Function`*): `this`

*Inherited from EventEmitter.prependListener*

*Overrides EventEmitter.prependListener*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:717*

**Parameters:**

| Param | Type |
| ------ | ------ |
| event |  `string` &#124; `symbol`|
| listener | `Function` |

**Returns:** `this`

___
<a id="prependoncelistener"></a>

##  prependOnceListener

▸ **prependOnceListener**(event: * `string` &#124; `symbol`*, listener: *`Function`*): `this`

*Inherited from EventEmitter.prependOnceListener*

*Overrides EventEmitter.prependOnceListener*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:718*

**Parameters:**

| Param | Type |
| ------ | ------ |
| event |  `string` &#124; `symbol`|
| listener | `Function` |

**Returns:** `this`

___
<a id="removealllisteners"></a>

##  removeAllListeners

▸ **removeAllListeners**(event?: * `string` &#124; `symbol`*): `this`

*Inherited from EventEmitter.removeAllListeners*

*Overrides EventEmitter.removeAllListeners*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:720*

**Parameters:**

| Param | Type |
| ------ | ------ |
| `Optional` event |  `string` &#124; `symbol`|

**Returns:** `this`

___
<a id="removelistener"></a>

##  removeListener

▸ **removeListener**(event: * `string` &#124; `symbol`*, listener: *`Function`*): `this`

*Inherited from EventEmitter.removeListener*

*Overrides EventEmitter.removeListener*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:719*

**Parameters:**

| Param | Type |
| ------ | ------ |
| event |  `string` &#124; `symbol`|
| listener | `Function` |

**Returns:** `this`

___
<a id="request"></a>

##  request

▸ **request**(name: *`string`*, args?: *`any`[]*): `Promise`<`any`>

*Inherited from [BaseApi](_api_base_.baseapi.md).[request](_api_base_.baseapi.md#request)*

*Defined in [api/Base.ts:79](https://github.com/neovim/node-client/blob/97a65c6/src/api/Base.ts#L79)*

**Parameters:**

| Param | Type | Default value |
| ------ | ------ | ------ |
| name | `string` | - |
| `Default value` args | `any`[] |  [] |

**Returns:** `Promise`<`any`>

___
<a id="setmaxlisteners"></a>

##  setMaxListeners

▸ **setMaxListeners**(n: *`number`*): `this`

*Inherited from EventEmitter.setMaxListeners*

*Overrides EventEmitter.setMaxListeners*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:721*

**Parameters:**

| Param | Type |
| ------ | ------ |
| n | `number` |

**Returns:** `this`

___
<a id="setoption"></a>

##  setOption

▸ **setOption**(): `void`

*Overrides [BaseApi](_api_base_.baseapi.md).[setOption](_api_base_.baseapi.md#setoption)*

*Defined in [api/Tabpage.ts:38](https://github.com/neovim/node-client/blob/97a65c6/src/api/Tabpage.ts#L38)*

Invalid

**Returns:** `void`

___
<a id="settransport"></a>

## `<Protected>` setTransport

▸ **setTransport**(transport: *[Transport](_utils_transport_.transport.md)*): `void`

*Inherited from [BaseApi](_api_base_.baseapi.md).[setTransport](_api_base_.baseapi.md#settransport)*

*Defined in [api/Base.ts:54](https://github.com/neovim/node-client/blob/97a65c6/src/api/Base.ts#L54)*

**Parameters:**

| Param | Type |
| ------ | ------ |
| transport | [Transport](_utils_transport_.transport.md) |

**Returns:** `void`

___
<a id="setvar"></a>

##  setVar

▸ **setVar**(name: *`string`*, value: *[VimValue](../modules/_types_vimvalue_.md#vimvalue)*): `Promise`<`void`>

*Inherited from [BaseApi](_api_base_.baseapi.md).[setVar](_api_base_.baseapi.md#setvar)*

*Defined in [api/Base.ts:115](https://github.com/neovim/node-client/blob/97a65c6/src/api/Base.ts#L115)*

Set a scoped variable

**Parameters:**

| Param | Type |
| ------ | ------ |
| name | `string` |
| value | [VimValue](../modules/_types_vimvalue_.md#vimvalue) |

**Returns:** `Promise`<`void`>

___
<a id="listenercount-1"></a>

## `<Static>` listenerCount

▸ **listenerCount**(emitter: *`EventEmitter`*, event: * `string` &#124; `symbol`*): `number`

*Inherited from EventEmitter.listenerCount*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:711*

**Parameters:**

| Param | Type |
| ------ | ------ |
| emitter | `EventEmitter` |
| event |  `string` &#124; `symbol`|

**Returns:** `number`

___

