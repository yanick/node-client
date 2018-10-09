

# Hierarchy

 `EventEmitter`

**↳ Transport**

# Constructors

<a id="constructor"></a>

##  constructor

⊕ **new Transport**(): [Transport](_utils_transport_.transport.md)

*Defined in [utils/transport.ts:48](https://github.com/neovim/node-client/blob/97a65c6/src/utils/transport.ts#L48)*

**Returns:** [Transport](_utils_transport_.transport.md)

___

# Properties

<a id="client"></a>

## `<Private>` client

**● client**: *`any`*

*Defined in [utils/transport.ts:48](https://github.com/neovim/node-client/blob/97a65c6/src/utils/transport.ts#L48)*

___
<a id="codec"></a>

## `<Protected>` codec

**● codec**: *`Codec`*

*Defined in [utils/transport.ts:45](https://github.com/neovim/node-client/blob/97a65c6/src/utils/transport.ts#L45)*

___
<a id="decodestream"></a>

## `<Private>` decodeStream

**● decodeStream**: *`any`*

*Defined in [utils/transport.ts:42](https://github.com/neovim/node-client/blob/97a65c6/src/utils/transport.ts#L42)*

___
<a id="encodestream"></a>

## `<Private>` encodeStream

**● encodeStream**: *`any`*

*Defined in [utils/transport.ts:41](https://github.com/neovim/node-client/blob/97a65c6/src/utils/transport.ts#L41)*

___
<a id="nextrequestid"></a>

## `<Private>` nextRequestId

**● nextRequestId**: *`number`* = 1

*Defined in [utils/transport.ts:40](https://github.com/neovim/node-client/blob/97a65c6/src/utils/transport.ts#L40)*

___
<a id="pending"></a>

## `<Private>` pending

**● pending**: *`Map`<`number`, `Function`>* =  new Map()

*Defined in [utils/transport.ts:39](https://github.com/neovim/node-client/blob/97a65c6/src/utils/transport.ts#L39)*

___
<a id="reader"></a>

## `<Private>` reader

**● reader**: *`ReadableStream`*

*Defined in [utils/transport.ts:43](https://github.com/neovim/node-client/blob/97a65c6/src/utils/transport.ts#L43)*

___
<a id="writer"></a>

## `<Private>` writer

**● writer**: *`WritableStream`*

*Defined in [utils/transport.ts:44](https://github.com/neovim/node-client/blob/97a65c6/src/utils/transport.ts#L44)*

___
<a id="defaultmaxlisteners"></a>

## `<Static>` defaultMaxListeners

**● defaultMaxListeners**: *`number`*

*Inherited from EventEmitter.defaultMaxListeners*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:712*

___

# Methods

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
<a id="attach"></a>

##  attach

▸ **attach**(writer: *`WritableStream`*, reader: *`ReadableStream`*, client: *`any`*): `void`

*Defined in [utils/transport.ts:89](https://github.com/neovim/node-client/blob/97a65c6/src/utils/transport.ts#L89)*

**Parameters:**

| Param | Type |
| ------ | ------ |
| writer | `WritableStream` |
| reader | `ReadableStream` |
| client | `any` |

**Returns:** `void`

___
<a id="detach"></a>

##  detach

▸ **detach**(): `void`

*Defined in [utils/transport.ts:102](https://github.com/neovim/node-client/blob/97a65c6/src/utils/transport.ts#L102)*

**Returns:** `void`

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

▸ **notify**(method: *`string`*, args: *`any`[]*): `void`

*Defined in [utils/transport.ts:117](https://github.com/neovim/node-client/blob/97a65c6/src/utils/transport.ts#L117)*

**Parameters:**

| Param | Type |
| ------ | ------ |
| method | `string` |
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
<a id="parsemessage"></a>

##  parseMessage

▸ **parseMessage**(msg: *`any`[]*): `void`

*Defined in [utils/transport.ts:121](https://github.com/neovim/node-client/blob/97a65c6/src/utils/transport.ts#L121)*

**Parameters:**

| Param | Type |
| ------ | ------ |
| msg | `any`[] |

**Returns:** `void`

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

▸ **request**(method: *`string`*, args: *`any`[]*, cb: *`Function`*): `void`

*Defined in [utils/transport.ts:107](https://github.com/neovim/node-client/blob/97a65c6/src/utils/transport.ts#L107)*

**Parameters:**

| Param | Type |
| ------ | ------ |
| method | `string` |
| args | `any`[] |
| cb | `Function` |

**Returns:** `void`

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
<a id="setupcodec"></a>

##  setupCodec

▸ **setupCodec**(): `Codec`

*Defined in [utils/transport.ts:65](https://github.com/neovim/node-client/blob/97a65c6/src/utils/transport.ts#L65)*

**Returns:** `Codec`

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

