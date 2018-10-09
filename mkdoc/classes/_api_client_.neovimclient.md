

# Hierarchy

↳  [Neovim](_api_neovim_.neovim.md)

**↳ NeovimClient**

# Constructors

<a id="constructor"></a>

##  constructor

⊕ **new NeovimClient**(options?: *`object`*): [NeovimClient](_api_client_.neovimclient.md)

*Overrides [BaseApi](_api_base_.baseapi.md).[constructor](_api_base_.baseapi.md#constructor)*

*Defined in [api/client.ts:14](https://github.com/neovim/node-client/blob/97a65c6/src/api/client.ts#L14)*

**Parameters:**

**`Default value` options: `object`**

| Param | Type |
| ------ | ------ |
| `Optional` logger | [ILogger](../modules/_utils_logger_.md#ilogger) |
| `Optional` transport | [Transport](_utils_transport_.transport.md) |

**Returns:** [NeovimClient](_api_client_.neovimclient.md)

___

# Properties

<a id="buffer"></a>

##  Buffer

**● Buffer**: *[Buffer](_api_buffer_.buffer.md)* =  Buffer

*Inherited from [Neovim](_api_neovim_.neovim.md).[Buffer](_api_neovim_.neovim.md#buffer)*

*Defined in [api/Neovim.ts:32](https://github.com/neovim/node-client/blob/97a65c6/src/api/Neovim.ts#L32)*

___
<a id="tabpage"></a>

##  Tabpage

**● Tabpage**: *[Tabpage](_api_tabpage_.tabpage.md)* =  Tabpage

*Inherited from [Neovim](_api_neovim_.neovim.md).[Tabpage](_api_neovim_.neovim.md#tabpage)*

*Defined in [api/Neovim.ts:34](https://github.com/neovim/node-client/blob/97a65c6/src/api/Neovim.ts#L34)*

___
<a id="window"></a>

##  Window

**● Window**: *[Window](_api_window_.window.md)* =  Window

*Inherited from [Neovim](_api_neovim_.neovim.md).[Window](_api_neovim_.neovim.md#window)*

*Defined in [api/Neovim.ts:33](https://github.com/neovim/node-client/blob/97a65c6/src/api/Neovim.ts#L33)*

___
<a id="_channelid"></a>

## `<Private>` _channelId

**● _channelId**: *`number`*

*Defined in [api/client.ts:13](https://github.com/neovim/node-client/blob/97a65c6/src/api/client.ts#L13)*

___
<a id="_isready"></a>

## `<Protected>` _isReady

**● _isReady**: *`Promise`<`boolean`>*

*Inherited from [BaseApi](_api_base_.baseapi.md).[_isReady](_api_base_.baseapi.md#_isready)*

*Defined in [api/Base.ts:29](https://github.com/neovim/node-client/blob/97a65c6/src/api/Base.ts#L29)*

___
<a id="attachedbuffers"></a>

## `<Private>` attachedBuffers

**● attachedBuffers**: *`Map`<`string`, `Map`<`string`, `Function`[]>>* =  new Map()

*Defined in [api/client.ts:14](https://github.com/neovim/node-client/blob/97a65c6/src/api/client.ts#L14)*

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

## `<Protected>` prefix

**● prefix**: *`string`* = "nvim_"

*Inherited from [Neovim](_api_neovim_.neovim.md).[prefix](_api_neovim_.neovim.md#prefix)*

*Overrides [BaseApi](_api_base_.baseapi.md).[prefix](_api_base_.baseapi.md#prefix)*

*Defined in [api/Neovim.ts:31](https://github.com/neovim/node-client/blob/97a65c6/src/api/Neovim.ts#L31)*

___
<a id="requestqueue"></a>

## `<Protected>` requestQueue

**● requestQueue**: *`Array`<`any`>*

*Defined in [api/client.ts:11](https://github.com/neovim/node-client/blob/97a65c6/src/api/client.ts#L11)*

___
<a id="transport"></a>

## `<Protected>` transport

**● transport**: *[Transport](_utils_transport_.transport.md)*

*Inherited from [BaseApi](_api_base_.baseapi.md).[transport](_api_base_.baseapi.md#transport)*

*Defined in [api/Base.ts:28](https://github.com/neovim/node-client/blob/97a65c6/src/api/Base.ts#L28)*

___
<a id="transportattached"></a>

## `<Private>` transportAttached

**● transportAttached**: *`boolean`*

*Defined in [api/client.ts:12](https://github.com/neovim/node-client/blob/97a65c6/src/api/client.ts#L12)*

___
<a id="defaultmaxlisteners"></a>

## `<Static>` defaultMaxListeners

**● defaultMaxListeners**: *`number`*

*Inherited from EventEmitter.defaultMaxListeners*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:712*

___

# Accessors

<a id="apiinfo"></a>

##  apiInfo

getapiInfo(): `Promise`<[`number`, [ApiInfo](../modules/_types_apiinfo_.md#apiinfo)]>

*Inherited from [Neovim](_api_neovim_.neovim.md).[apiInfo](_api_neovim_.neovim.md#apiinfo)*

*Defined in [api/Neovim.ts:36](https://github.com/neovim/node-client/blob/97a65c6/src/api/Neovim.ts#L36)*

**Returns:** `Promise`<[`number`, [ApiInfo](../modules/_types_apiinfo_.md#apiinfo)]>

___
<a id="buffer-1"></a>

##  buffer

getbuffer(): [AsyncBuffer](../interfaces/_api_buffer_.asyncbuffer.md)setbuffer(buffer: *[AsyncBuffer](../interfaces/_api_buffer_.asyncbuffer.md)*): `void`

*Inherited from [Neovim](_api_neovim_.neovim.md).[buffer](_api_neovim_.neovim.md#buffer-1)*

*Defined in [api/Neovim.ts:46](https://github.com/neovim/node-client/blob/97a65c6/src/api/Neovim.ts#L46)*

Get current buffer

**Returns:** [AsyncBuffer](../interfaces/_api_buffer_.asyncbuffer.md)

*Inherited from [Neovim](_api_neovim_.neovim.md).[buffer](_api_neovim_.neovim.md#buffer-1)*

*Defined in [api/Neovim.ts:53](https://github.com/neovim/node-client/blob/97a65c6/src/api/Neovim.ts#L53)*

Set current buffer

**Parameters:**

| Param | Type |
| ------ | ------ |
| buffer | [AsyncBuffer](../interfaces/_api_buffer_.asyncbuffer.md) |

**Returns:** `void`

___
<a id="buffers"></a>

##  buffers

getbuffers(): `Promise`<[Buffer](_api_buffer_.buffer.md)[]>

*Inherited from [Neovim](_api_neovim_.neovim.md).[buffers](_api_neovim_.neovim.md#buffers)*

*Defined in [api/Neovim.ts:41](https://github.com/neovim/node-client/blob/97a65c6/src/api/Neovim.ts#L41)*

Get list of all buffers

**Returns:** `Promise`<[Buffer](_api_buffer_.buffer.md)[]>

___
<a id="channelid"></a>

##  channelId

getchannelId(): `Promise`<`number`>

*Defined in [api/client.ts:47](https://github.com/neovim/node-client/blob/97a65c6/src/api/client.ts#L47)*

**Returns:** `Promise`<`number`>

___
<a id="chans"></a>

##  chans

getchans(): `Promise`<`number`[]>

*Inherited from [Neovim](_api_neovim_.neovim.md).[chans](_api_neovim_.neovim.md#chans)*

*Defined in [api/Neovim.ts:57](https://github.com/neovim/node-client/blob/97a65c6/src/api/Neovim.ts#L57)*

**Returns:** `Promise`<`number`[]>

___
<a id="colormap"></a>

##  colorMap

getcolorMap(): `Promise`<`object`>

*Inherited from [Neovim](_api_neovim_.neovim.md).[colorMap](_api_neovim_.neovim.md#colormap)*

*Defined in [api/Neovim.ts:165](https://github.com/neovim/node-client/blob/97a65c6/src/api/Neovim.ts#L165)*

Gets map of defined colors

**Returns:** `Promise`<`object`>

___
<a id="commands"></a>

##  commands

getcommands(): `Promise`<`Object`>

*Inherited from [Neovim](_api_neovim_.neovim.md).[commands](_api_neovim_.neovim.md#commands)*

*Defined in [api/Neovim.ts:65](https://github.com/neovim/node-client/blob/97a65c6/src/api/Neovim.ts#L65)*

**Returns:** `Promise`<`Object`>

___
<a id="dir"></a>

##  dir

setdir(dir: *`string`*): `void`

*Inherited from [Neovim](_api_neovim_.neovim.md).[dir](_api_neovim_.neovim.md#dir)*

*Defined in [api/Neovim.ts:128](https://github.com/neovim/node-client/blob/97a65c6/src/api/Neovim.ts#L128)*

Set current directory

**Parameters:**

| Param | Type |
| ------ | ------ |
| dir | `string` |

**Returns:** `void`

___
<a id="isapiready"></a>

##  isApiReady

getisApiReady(): `boolean`

*Defined in [api/client.ts:43](https://github.com/neovim/node-client/blob/97a65c6/src/api/client.ts#L43)*

**Returns:** `boolean`

___
<a id="line"></a>

##  line

getline():  `string` &#124; `Promise`<`string`>setline(line: * `string` &#124; `Promise`<`string`>*): `void`

*Inherited from [Neovim](_api_neovim_.neovim.md).[line](_api_neovim_.neovim.md#line)*

*Defined in [api/Neovim.ts:133](https://github.com/neovim/node-client/blob/97a65c6/src/api/Neovim.ts#L133)*

Get current line. Always returns a Promise.

**Returns:**  `string` &#124; `Promise`<`string`>

*Inherited from [Neovim](_api_neovim_.neovim.md).[line](_api_neovim_.neovim.md#line)*

*Defined in [api/Neovim.ts:138](https://github.com/neovim/node-client/blob/97a65c6/src/api/Neovim.ts#L138)*

Set current line

**Parameters:**

| Param | Type |
| ------ | ------ |
| line |  `string` &#124; `Promise`<`string`>|

**Returns:** `void`

___
<a id="mode"></a>

##  mode

getmode(): `Promise`<`object`>

*Inherited from [Neovim](_api_neovim_.neovim.md).[mode](_api_neovim_.neovim.md#mode)*

*Defined in [api/Neovim.ts:160](https://github.com/neovim/node-client/blob/97a65c6/src/api/Neovim.ts#L160)*

Gets current mode

**Returns:** `Promise`<`object`>

___
<a id="runtimepaths"></a>

##  runtimePaths

getruntimePaths(): `Promise`<`string`[]>

*Inherited from [Neovim](_api_neovim_.neovim.md).[runtimePaths](_api_neovim_.neovim.md#runtimepaths)*

*Defined in [api/Neovim.ts:123](https://github.com/neovim/node-client/blob/97a65c6/src/api/Neovim.ts#L123)*

Get list of all runtime paths

**Returns:** `Promise`<`string`[]>

___
<a id="tabpage-1"></a>

##  tabpage

gettabpage(): [AsyncTabpage](../interfaces/_api_tabpage_.asynctabpage.md)settabpage(tabpage: *[AsyncTabpage](../interfaces/_api_tabpage_.asynctabpage.md)*): `void`

*Inherited from [Neovim](_api_neovim_.neovim.md).[tabpage](_api_neovim_.neovim.md#tabpage-1)*

*Defined in [api/Neovim.ts:79](https://github.com/neovim/node-client/blob/97a65c6/src/api/Neovim.ts#L79)*

Get current tabpage

**Returns:** [AsyncTabpage](../interfaces/_api_tabpage_.asynctabpage.md)

*Inherited from [Neovim](_api_neovim_.neovim.md).[tabpage](_api_neovim_.neovim.md#tabpage-1)*

*Defined in [api/Neovim.ts:86](https://github.com/neovim/node-client/blob/97a65c6/src/api/Neovim.ts#L86)*

Set current tabpage

**Parameters:**

| Param | Type |
| ------ | ------ |
| tabpage | [AsyncTabpage](../interfaces/_api_tabpage_.asynctabpage.md) |

**Returns:** `void`

___
<a id="tabpages"></a>

##  tabpages

gettabpages(): `Promise`<[Tabpage](_api_tabpage_.tabpage.md)[]>

*Inherited from [Neovim](_api_neovim_.neovim.md).[tabpages](_api_neovim_.neovim.md#tabpages)*

*Defined in [api/Neovim.ts:74](https://github.com/neovim/node-client/blob/97a65c6/src/api/Neovim.ts#L74)*

Get list of all tabpages

**Returns:** `Promise`<[Tabpage](_api_tabpage_.tabpage.md)[]>

___
<a id="uis"></a>

##  uis

getuis(): `Promise`<`any`[]>

*Inherited from [Neovim](_api_neovim_.neovim.md).[uis](_api_neovim_.neovim.md#uis)*

*Defined in [api/Neovim.ts:341](https://github.com/neovim/node-client/blob/97a65c6/src/api/Neovim.ts#L341)*

**Returns:** `Promise`<`any`[]>

___
<a id="window-1"></a>

##  window

getwindow(): [AsyncWindow](../interfaces/_api_window_.asyncwindow.md)setwindow(win: *[AsyncWindow](../interfaces/_api_window_.asyncwindow.md)*): `void`

*Inherited from [Neovim](_api_neovim_.neovim.md).[window](_api_neovim_.neovim.md#window-1)*

*Defined in [api/Neovim.ts:96](https://github.com/neovim/node-client/blob/97a65c6/src/api/Neovim.ts#L96)*

Get current window

**Returns:** [AsyncWindow](../interfaces/_api_window_.asyncwindow.md)

*Inherited from [Neovim](_api_neovim_.neovim.md).[window](_api_neovim_.neovim.md#window-1)*

*Defined in [api/Neovim.ts:101](https://github.com/neovim/node-client/blob/97a65c6/src/api/Neovim.ts#L101)*

Set current window

**Parameters:**

| Param | Type |
| ------ | ------ |
| win | [AsyncWindow](../interfaces/_api_window_.asyncwindow.md) |

**Returns:** `void`

___
<a id="windows"></a>

##  windows

getwindows(): `Promise`<[Window](_api_window_.window.md)[]>

*Inherited from [Neovim](_api_neovim_.neovim.md).[windows](_api_neovim_.neovim.md#windows)*

*Defined in [api/Neovim.ts:91](https://github.com/neovim/node-client/blob/97a65c6/src/api/Neovim.ts#L91)*

Get list of all windows

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
<a id="attach"></a>

##  attach

▸ **attach**(__namedParameters: *`object`*): `void`

*Defined in [api/client.ts:31](https://github.com/neovim/node-client/blob/97a65c6/src/api/client.ts#L31)*

Attaches msgpack to read/write streams *

**Parameters:**

**__namedParameters: `object`**

| Param | Type |
| ------ | ------ |
| reader | `ReadableStream` |
| writer | `WritableStream` |

**Returns:** `void`

___
<a id="attachbuffer"></a>

##  attachBuffer

▸ **attachBuffer**(buffer: *[Buffer](_api_buffer_.buffer.md)*, eventName: *`string`*, cb: *`Function`*): `Function`

*Defined in [api/client.ts:203](https://github.com/neovim/node-client/blob/97a65c6/src/api/client.ts#L203)*

**Parameters:**

| Param | Type |
| ------ | ------ |
| buffer | [Buffer](_api_buffer_.buffer.md) |
| eventName | `string` |
| cb | `Function` |

**Returns:** `Function`

___
<a id="call"></a>

##  call

▸ **call**(fname: *`string`*, args?: * [VimValue](../modules/_types_vimvalue_.md#vimvalue) &#124; `Array`<[VimValue](../modules/_types_vimvalue_.md#vimvalue)>*): `Promise`<`any`>

*Inherited from [Neovim](_api_neovim_.neovim.md).[call](_api_neovim_.neovim.md#call)*

*Defined in [api/Neovim.ts:236](https://github.com/neovim/node-client/blob/97a65c6/src/api/Neovim.ts#L236)*

Call a vim function

**Parameters:**

| Param | Type | Default value |
| ------ | ------ | ------ |
| fname | `string` | - |
| `Default value` args |  [VimValue](../modules/_types_vimvalue_.md#vimvalue) &#124; `Array`<[VimValue](../modules/_types_vimvalue_.md#vimvalue)>|  [] |

**Returns:** `Promise`<`any`>

___
<a id="callatomic"></a>

##  callAtomic

▸ **callAtomic**(calls: *`Array`<[VimValue](../modules/_types_vimvalue_.md#vimvalue)>*): `Promise`<[`Array`<`any`>, `boolean`]>

*Inherited from [Neovim](_api_neovim_.neovim.md).[callAtomic](_api_neovim_.neovim.md#callatomic)*

*Defined in [api/Neovim.ts:247](https://github.com/neovim/node-client/blob/97a65c6/src/api/Neovim.ts#L247)*

Call Atomic calls

**Parameters:**

| Param | Type |
| ------ | ------ |
| calls | `Array`<[VimValue](../modules/_types_vimvalue_.md#vimvalue)> |

**Returns:** `Promise`<[`Array`<`any`>, `boolean`]>

___
<a id="calldictfunction"></a>

##  callDictFunction

▸ **callDictFunction**(dict: *`object`*, fname: *`string`*, args?: * [VimValue](../modules/_types_vimvalue_.md#vimvalue) &#124; `Array`<[VimValue](../modules/_types_vimvalue_.md#vimvalue)>*): `object`

*Inherited from [Neovim](_api_neovim_.neovim.md).[callDictFunction](_api_neovim_.neovim.md#calldictfunction)*

*Defined in [api/Neovim.ts:222](https://github.com/neovim/node-client/blob/97a65c6/src/api/Neovim.ts#L222)*

**Parameters:**

| Param | Type | Default value |
| ------ | ------ | ------ |
| dict | `object` | - |
| fname | `string` | - |
| `Default value` args |  [VimValue](../modules/_types_vimvalue_.md#vimvalue) &#124; `Array`<[VimValue](../modules/_types_vimvalue_.md#vimvalue)>|  [] |

**Returns:** `object`

___
<a id="callfunction"></a>

##  callFunction

▸ **callFunction**(fname: *`string`*, args?: * [VimValue](../modules/_types_vimvalue_.md#vimvalue) &#124; `Array`<[VimValue](../modules/_types_vimvalue_.md#vimvalue)>*): `Promise`<`any`>

*Inherited from [Neovim](_api_neovim_.neovim.md).[callFunction](_api_neovim_.neovim.md#callfunction)*

*Defined in [api/Neovim.ts:242](https://github.com/neovim/node-client/blob/97a65c6/src/api/Neovim.ts#L242)*

Alias for `call`

**Parameters:**

| Param | Type | Default value |
| ------ | ------ | ------ |
| fname | `string` | - |
| `Default value` args |  [VimValue](../modules/_types_vimvalue_.md#vimvalue) &#124; `Array`<[VimValue](../modules/_types_vimvalue_.md#vimvalue)>|  [] |

**Returns:** `Promise`<`any`>

___
<a id="command"></a>

##  command

▸ **command**(arg: *`string`*): `Promise`<`any`>

*Inherited from [Neovim](_api_neovim_.neovim.md).[command](_api_neovim_.neovim.md#command)*

*Defined in [api/Neovim.ts:252](https://github.com/neovim/node-client/blob/97a65c6/src/api/Neovim.ts#L252)*

Runs a vim command

**Parameters:**

| Param | Type |
| ------ | ------ |
| arg | `string` |

**Returns:** `Promise`<`any`>

___
<a id="commandoutput"></a>

##  commandOutput

▸ **commandOutput**(arg: *`string`*): `Promise`<`string`>

*Inherited from [Neovim](_api_neovim_.neovim.md).[commandOutput](_api_neovim_.neovim.md#commandoutput)*

*Defined in [api/Neovim.ts:257](https://github.com/neovim/node-client/blob/97a65c6/src/api/Neovim.ts#L257)*

Runs a command and returns output (synchronous?)

**Parameters:**

| Param | Type |
| ------ | ------ |
| arg | `string` |

**Returns:** `Promise`<`string`>

___
<a id="deletecurrentline"></a>

##  deleteCurrentLine

▸ **deleteCurrentLine**(): `Promise`<`any`>

*Inherited from [Neovim](_api_neovim_.neovim.md).[deleteCurrentLine](_api_neovim_.neovim.md#deletecurrentline)*

*Defined in [api/Neovim.ts:195](https://github.com/neovim/node-client/blob/97a65c6/src/api/Neovim.ts#L195)*

Delete current line in buffer

**Returns:** `Promise`<`any`>

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
<a id="detachbuffer"></a>

##  detachBuffer

▸ **detachBuffer**(buffer: *[Buffer](_api_buffer_.buffer.md)*, eventName: *`string`*, cb: *`Function`*): `boolean`

*Defined in [api/client.ts:227](https://github.com/neovim/node-client/blob/97a65c6/src/api/client.ts#L227)*

Returns `true` if buffer should be detached

**Parameters:**

| Param | Type |
| ------ | ------ |
| buffer | [Buffer](_api_buffer_.buffer.md) |
| eventName | `string` |
| cb | `Function` |

**Returns:** `boolean`

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
<a id="emitnotification"></a>

##  emitNotification

▸ **emitNotification**(method: *`string`*, args: *`any`[]*): `void`

*Defined in [api/client.ts:75](https://github.com/neovim/node-client/blob/97a65c6/src/api/client.ts#L75)*

**Parameters:**

| Param | Type |
| ------ | ------ |
| method | `string` |
| args | `any`[] |

**Returns:** `void`

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
<a id="errwrite"></a>

##  errWrite

▸ **errWrite**(str: *`string`*): `Promise`<`any`>

*Inherited from [Neovim](_api_neovim_.neovim.md).[errWrite](_api_neovim_.neovim.md#errwrite)*

*Defined in [api/Neovim.ts:331](https://github.com/neovim/node-client/blob/97a65c6/src/api/Neovim.ts#L331)*

Write to error buffer

**Parameters:**

| Param | Type |
| ------ | ------ |
| str | `string` |

**Returns:** `Promise`<`any`>

___
<a id="errwriteline"></a>

##  errWriteLine

▸ **errWriteLine**(str: *`string`*): `Promise`<`any`>

*Inherited from [Neovim](_api_neovim_.neovim.md).[errWriteLine](_api_neovim_.neovim.md#errwriteline)*

*Defined in [api/Neovim.ts:336](https://github.com/neovim/node-client/blob/97a65c6/src/api/Neovim.ts#L336)*

Write to error buffer

**Parameters:**

| Param | Type |
| ------ | ------ |
| str | `string` |

**Returns:** `Promise`<`any`>

___
<a id="eval"></a>

##  eval

▸ **eval**(expr: *`string`*): `Promise`<[VimValue](../modules/_types_vimvalue_.md#vimvalue)>

*Inherited from [Neovim](_api_neovim_.neovim.md).[eval](_api_neovim_.neovim.md#eval)*

*Defined in [api/Neovim.ts:205](https://github.com/neovim/node-client/blob/97a65c6/src/api/Neovim.ts#L205)*

Evaluates a VimL expression (:help expression). Dictionaries and Lists are recursively expanded. On VimL error: Returns a generic error; v:errmsg is not updated.

**Parameters:**

| Param | Type |
| ------ | ------ |
| expr | `string` |

**Returns:** `Promise`<[VimValue](../modules/_types_vimvalue_.md#vimvalue)>

___
<a id="eventnames"></a>

##  eventNames

▸ **eventNames**(): ( `string` &#124; `symbol`)[]

*Inherited from EventEmitter.eventNames*

*Overrides EventEmitter.eventNames*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:725*

**Returns:** ( `string` &#124; `symbol`)[]

___
<a id="executelua"></a>

##  executeLua

▸ **executeLua**(code: *`string`*, args?: *`Array`<[VimValue](../modules/_types_vimvalue_.md#vimvalue)>*): `Promise`<`any`>

*Inherited from [Neovim](_api_neovim_.neovim.md).[executeLua](_api_neovim_.neovim.md#executelua)*

*Defined in [api/Neovim.ts:218](https://github.com/neovim/node-client/blob/97a65c6/src/api/Neovim.ts#L218)*

**Parameters:**

| Param | Type | Default value |
| ------ | ------ | ------ |
| code | `string` | - |
| `Default value` args | `Array`<[VimValue](../modules/_types_vimvalue_.md#vimvalue)> |  [] |

**Returns:** `Promise`<`any`>

___
<a id="feedkeys"></a>

##  feedKeys

▸ **feedKeys**(keys: *`string`*, mode: *`string`*, escapeCsi: *`boolean`*): `Promise`<`any`>

*Inherited from [Neovim](_api_neovim_.neovim.md).[feedKeys](_api_neovim_.neovim.md#feedkeys)*

*Defined in [api/Neovim.ts:267](https://github.com/neovim/node-client/blob/97a65c6/src/api/Neovim.ts#L267)*

feedKeys

**Parameters:**

| Param | Type |
| ------ | ------ |
| keys | `string` |
| mode | `string` |
| escapeCsi | `boolean` |

**Returns:** `Promise`<`any`>

___
<a id="generateapi"></a>

##  generateApi

▸ **generateApi**(): `Promise`< `null` &#124; `boolean`>

*Defined in [api/client.ts:154](https://github.com/neovim/node-client/blob/97a65c6/src/api/client.ts#L154)*

**Returns:** `Promise`< `null` &#124; `boolean`>

___
<a id="getchaninfo"></a>

##  getChanInfo

▸ **getChanInfo**(chan: *`number`*): `Promise`<`any`>

*Inherited from [Neovim](_api_neovim_.neovim.md).[getChanInfo](_api_neovim_.neovim.md#getchaninfo)*

*Defined in [api/Neovim.ts:61](https://github.com/neovim/node-client/blob/97a65c6/src/api/Neovim.ts#L61)*

**Parameters:**

| Param | Type |
| ------ | ------ |
| chan | `number` |

**Returns:** `Promise`<`any`>

___
<a id="getcolorbyname"></a>

##  getColorByName

▸ **getColorByName**(name: *`string`*): `Promise`<`number`>

*Inherited from [Neovim](_api_neovim_.neovim.md).[getColorByName](_api_neovim_.neovim.md#getcolorbyname)*

*Defined in [api/Neovim.ts:170](https://github.com/neovim/node-client/blob/97a65c6/src/api/Neovim.ts#L170)*

Get color by name

**Parameters:**

| Param | Type |
| ------ | ------ |
| name | `string` |

**Returns:** `Promise`<`number`>

___
<a id="getcommands"></a>

##  getCommands

▸ **getCommands**(options?: *`object`*): `Promise`<`Object`>

*Inherited from [Neovim](_api_neovim_.neovim.md).[getCommands](_api_neovim_.neovim.md#getcommands)*

*Defined in [api/Neovim.ts:69](https://github.com/neovim/node-client/blob/97a65c6/src/api/Neovim.ts#L69)*

**Parameters:**

| Param | Type | Default value |
| ------ | ------ | ------ |
| `Default value` options | `object` |  {} |

**Returns:** `Promise`<`Object`>

___
<a id="gethighlight"></a>

##  getHighlight

▸ **getHighlight**(nameOrId: * `string` &#124; `number`*, isRgb?: *`boolean`*):  `Promise`<`any`> &#124; `void`

*Inherited from [Neovim](_api_neovim_.neovim.md).[getHighlight](_api_neovim_.neovim.md#gethighlight)*

*Defined in [api/Neovim.ts:175](https://github.com/neovim/node-client/blob/97a65c6/src/api/Neovim.ts#L175)*

Get highlight by name or id

**Parameters:**

| Param | Type | Default value |
| ------ | ------ | ------ |
| nameOrId |  `string` &#124; `number`| - |
| `Default value` isRgb | `boolean` | true |

**Returns:**  `Promise`<`any`> &#124; `void`

___
<a id="gethighlightbyid"></a>

##  getHighlightById

▸ **getHighlightById**(id: *`number`*, isRgb?: *`boolean`*): `Promise`<`any`>

*Inherited from [Neovim](_api_neovim_.neovim.md).[getHighlightById](_api_neovim_.neovim.md#gethighlightbyid)*

*Defined in [api/Neovim.ts:190](https://github.com/neovim/node-client/blob/97a65c6/src/api/Neovim.ts#L190)*

**Parameters:**

| Param | Type | Default value |
| ------ | ------ | ------ |
| id | `number` | - |
| `Default value` isRgb | `boolean` | true |

**Returns:** `Promise`<`any`>

___
<a id="gethighlightbyname"></a>

##  getHighlightByName

▸ **getHighlightByName**(name: *`string`*, isRgb?: *`boolean`*): `Promise`<`any`>

*Inherited from [Neovim](_api_neovim_.neovim.md).[getHighlightByName](_api_neovim_.neovim.md#gethighlightbyname)*

*Defined in [api/Neovim.ts:186](https://github.com/neovim/node-client/blob/97a65c6/src/api/Neovim.ts#L186)*

**Parameters:**

| Param | Type | Default value |
| ------ | ------ | ------ |
| name | `string` | - |
| `Default value` isRgb | `boolean` | true |

**Returns:** `Promise`<`any`>

___
<a id="getkeymap"></a>

##  getKeymap

▸ **getKeymap**(mode: *`string`*): `Promise`<`Array`<`any`>>

*Inherited from [Neovim](_api_neovim_.neovim.md).[getKeymap](_api_neovim_.neovim.md#getkeymap)*

*Defined in [api/Neovim.ts:155](https://github.com/neovim/node-client/blob/97a65c6/src/api/Neovim.ts#L155)*

Gets keymap

**Parameters:**

| Param | Type |
| ------ | ------ |
| mode | `string` |

**Returns:** `Promise`<`Array`<`any`>>

___
<a id="getline"></a>

##  getLine

▸ **getLine**(): `Promise`<`string`>

*Inherited from [Neovim](_api_neovim_.neovim.md).[getLine](_api_neovim_.neovim.md#getline)*

*Defined in [api/Neovim.ts:145](https://github.com/neovim/node-client/blob/97a65c6/src/api/Neovim.ts#L145)*

**Returns:** `Promise`<`string`>

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

▸ **getOption**(name: *`string`*):  `Promise`<[VimValue](../modules/_types_vimvalue_.md#vimvalue)> &#124; `void`

*Inherited from [BaseApi](_api_base_.baseapi.md).[getOption](_api_base_.baseapi.md#getoption)*

*Defined in [api/Base.ts:127](https://github.com/neovim/node-client/blob/97a65c6/src/api/Base.ts#L127)*

Retrieves a scoped option depending on type of `this`

**Parameters:**

| Param | Type |
| ------ | ------ |
| name | `string` |

**Returns:**  `Promise`<[VimValue](../modules/_types_vimvalue_.md#vimvalue)> &#124; `void`

___
<a id="getproc"></a>

##  getProc

▸ **getProc**(pid: *`number`*): `Promise`<[Proc](../modules/_api_neovim_.md#proc)>

*Inherited from [Neovim](_api_neovim_.neovim.md).[getProc](_api_neovim_.neovim.md#getproc)*

*Defined in [api/Neovim.ts:293](https://github.com/neovim/node-client/blob/97a65c6/src/api/Neovim.ts#L293)*

**Parameters:**

| Param | Type |
| ------ | ------ |
| pid | `number` |

**Returns:** `Promise`<[Proc](../modules/_api_neovim_.md#proc)>

___
<a id="getprocchildren"></a>

##  getProcChildren

▸ **getProcChildren**(pid: *`number`*): `Promise`<[Proc](../modules/_api_neovim_.md#proc)[]>

*Inherited from [Neovim](_api_neovim_.neovim.md).[getProcChildren](_api_neovim_.neovim.md#getprocchildren)*

*Defined in [api/Neovim.ts:297](https://github.com/neovim/node-client/blob/97a65c6/src/api/Neovim.ts#L297)*

**Parameters:**

| Param | Type |
| ------ | ------ |
| pid | `number` |

**Returns:** `Promise`<[Proc](../modules/_api_neovim_.md#proc)[]>

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
<a id="getvvar"></a>

##  getVvar

▸ **getVvar**(name: *`string`*): `Promise`<[VimValue](../modules/_types_vimvalue_.md#vimvalue)>

*Inherited from [Neovim](_api_neovim_.neovim.md).[getVvar](_api_neovim_.neovim.md#getvvar)*

*Defined in [api/Neovim.ts:262](https://github.com/neovim/node-client/blob/97a65c6/src/api/Neovim.ts#L262)*

Gets a v: variable

**Parameters:**

| Param | Type |
| ------ | ------ |
| name | `string` |

**Returns:** `Promise`<[VimValue](../modules/_types_vimvalue_.md#vimvalue)>

___
<a id="getwindow"></a>

##  getWindow

▸ **getWindow**(): [AsyncWindow](../interfaces/_api_window_.asyncwindow.md)

*Inherited from [Neovim](_api_neovim_.neovim.md).[getWindow](_api_neovim_.neovim.md#getwindow)*

*Defined in [api/Neovim.ts:111](https://github.com/neovim/node-client/blob/97a65c6/src/api/Neovim.ts#L111)*

Get current window

**Returns:** [AsyncWindow](../interfaces/_api_window_.asyncwindow.md)

___
<a id="getwindows"></a>

##  getWindows

▸ **getWindows**(): `Promise`<[Window](_api_window_.window.md)[]>

*Inherited from [Neovim](_api_neovim_.neovim.md).[getWindows](_api_neovim_.neovim.md#getwindows)*

*Defined in [api/Neovim.ts:106](https://github.com/neovim/node-client/blob/97a65c6/src/api/Neovim.ts#L106)*

Get list of all windows

**Returns:** `Promise`<[Window](_api_window_.window.md)[]>

___
<a id="handlenotification"></a>

##  handleNotification

▸ **handleNotification**(method: *`string`*, args: *[VimValue](../modules/_types_vimvalue_.md#vimvalue)[]*, ...restArgs: *`any`[]*): `void`

*Defined in [api/client.ts:104](https://github.com/neovim/node-client/blob/97a65c6/src/api/client.ts#L104)*

**Parameters:**

| Param | Type |
| ------ | ------ |
| method | `string` |
| args | [VimValue](../modules/_types_vimvalue_.md#vimvalue)[] |
| `Rest` restArgs | `any`[] |

**Returns:** `void`

___
<a id="handlerequest"></a>

##  handleRequest

▸ **handleRequest**(method: *`string`*, args: *[VimValue](../modules/_types_vimvalue_.md#vimvalue)[]*, resp: *`any`*, ...restArgs: *`any`[]*): `void`

*Defined in [api/client.ts:54](https://github.com/neovim/node-client/blob/97a65c6/src/api/client.ts#L54)*

**Parameters:**

| Param | Type |
| ------ | ------ |
| method | `string` |
| args | [VimValue](../modules/_types_vimvalue_.md#vimvalue)[] |
| resp | `any` |
| `Rest` restArgs | `any`[] |

**Returns:** `void`

___
<a id="input"></a>

##  input

▸ **input**(keys: *`string`*): `Promise`<`number`>

*Inherited from [Neovim](_api_neovim_.neovim.md).[input](_api_neovim_.neovim.md#input)*

*Defined in [api/Neovim.ts:272](https://github.com/neovim/node-client/blob/97a65c6/src/api/Neovim.ts#L272)*

Sends input keys

**Parameters:**

| Param | Type |
| ------ | ------ |
| keys | `string` |

**Returns:** `Promise`<`number`>

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
<a id="lua"></a>

##  lua

▸ **lua**(code: *`string`*, args?: *`Array`<[VimValue](../modules/_types_vimvalue_.md#vimvalue)>*): `Promise`<`any`>

*Inherited from [Neovim](_api_neovim_.neovim.md).[lua](_api_neovim_.neovim.md#lua)*

*Defined in [api/Neovim.ts:212](https://github.com/neovim/node-client/blob/97a65c6/src/api/Neovim.ts#L212)*

Executes lua, it's possible neovim client does not support this

**Parameters:**

| Param | Type | Default value |
| ------ | ------ | ------ |
| code | `string` | - |
| `Default value` args | `Array`<[VimValue](../modules/_types_vimvalue_.md#vimvalue)> |  [] |

**Returns:** `Promise`<`any`>

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
<a id="outwrite"></a>

##  outWrite

▸ **outWrite**(str: *`string`*): `Promise`<`any`>

*Inherited from [Neovim](_api_neovim_.neovim.md).[outWrite](_api_neovim_.neovim.md#outwrite)*

*Defined in [api/Neovim.ts:322](https://github.com/neovim/node-client/blob/97a65c6/src/api/Neovim.ts#L322)*

Write to output buffer

**Parameters:**

| Param | Type |
| ------ | ------ |
| str | `string` |

**Returns:** `Promise`<`any`>

___
<a id="outwriteline"></a>

##  outWriteLine

▸ **outWriteLine**(str: *`string`*): `Promise`<`any`>

*Inherited from [Neovim](_api_neovim_.neovim.md).[outWriteLine](_api_neovim_.neovim.md#outwriteline)*

*Defined in [api/Neovim.ts:326](https://github.com/neovim/node-client/blob/97a65c6/src/api/Neovim.ts#L326)*

**Parameters:**

| Param | Type |
| ------ | ------ |
| str | `string` |

**Returns:** `Promise`<`any`>

___
<a id="parseexpression"></a>

##  parseExpression

▸ **parseExpression**(expr: *`string`*, flags: *`string`*, highlight: *`boolean`*): `Promise`<`any`>

*Inherited from [Neovim](_api_neovim_.neovim.md).[parseExpression](_api_neovim_.neovim.md#parseexpression)*

*Defined in [api/Neovim.ts:281](https://github.com/neovim/node-client/blob/97a65c6/src/api/Neovim.ts#L281)*

Parse a VimL Expression

TODO: return type, see :help

**Parameters:**

| Param | Type |
| ------ | ------ |
| expr | `string` |
| flags | `string` |
| highlight | `boolean` |

**Returns:** `Promise`<`any`>

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
<a id="quit"></a>

##  quit

▸ **quit**(): `void`

*Inherited from [Neovim](_api_neovim_.neovim.md).[quit](_api_neovim_.neovim.md#quit)*

*Defined in [api/Neovim.ts:393](https://github.com/neovim/node-client/blob/97a65c6/src/api/Neovim.ts#L393)*

Quit nvim

**Returns:** `void`

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
<a id="replacetermcodes"></a>

##  replaceTermcodes

▸ **replaceTermcodes**(str: *`string`*, fromPart: *`boolean`*, doIt: *`boolean`*, special: *`boolean`*): `Promise`<`string`>

*Inherited from [Neovim](_api_neovim_.neovim.md).[replaceTermcodes](_api_neovim_.neovim.md#replacetermcodes)*

*Defined in [api/Neovim.ts:302](https://github.com/neovim/node-client/blob/97a65c6/src/api/Neovim.ts#L302)*

Replace term codes

**Parameters:**

| Param | Type |
| ------ | ------ |
| str | `string` |
| fromPart | `boolean` |
| doIt | `boolean` |
| special | `boolean` |

**Returns:** `Promise`<`string`>

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
<a id="requestapi"></a>

##  requestApi

▸ **requestApi**(): `Promise`<`any`[]>

*Defined in [api/client.ts:137](https://github.com/neovim/node-client/blob/97a65c6/src/api/client.ts#L137)*

**Returns:** `Promise`<`any`[]>

___
<a id="setclientinfo"></a>

##  setClientInfo

▸ **setClientInfo**(name: *`string`*, version: *`object`*, type: *`string`*, methods: *`object`*, attributes: *`object`*): `void`

*Inherited from [Neovim](_api_neovim_.neovim.md).[setClientInfo](_api_neovim_.neovim.md#setclientinfo)*

*Defined in [api/Neovim.ts:376](https://github.com/neovim/node-client/blob/97a65c6/src/api/Neovim.ts#L376)*

**Parameters:**

| Param | Type |
| ------ | ------ |
| name | `string` |
| version | `object` |
| type | `string` |
| methods | `object` |
| attributes | `object` |

**Returns:** `void`

___
<a id="setline"></a>

##  setLine

▸ **setLine**(line: *`string`*): `Promise`<`any`>

*Inherited from [Neovim](_api_neovim_.neovim.md).[setLine](_api_neovim_.neovim.md#setline)*

*Defined in [api/Neovim.ts:150](https://github.com/neovim/node-client/blob/97a65c6/src/api/Neovim.ts#L150)*

Set current line

**Parameters:**

| Param | Type |
| ------ | ------ |
| line | `string` |

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

▸ **setOption**(name: *`string`*, value: *[VimValue](../modules/_types_vimvalue_.md#vimvalue)*):  `Promise`<`void`> &#124; `void`

*Inherited from [BaseApi](_api_base_.baseapi.md).[setOption](_api_base_.baseapi.md#setoption)*

*Defined in [api/Base.ts:133](https://github.com/neovim/node-client/blob/97a65c6/src/api/Base.ts#L133)*

Set scoped option

**Parameters:**

| Param | Type |
| ------ | ------ |
| name | `string` |
| value | [VimValue](../modules/_types_vimvalue_.md#vimvalue) |

**Returns:**  `Promise`<`void`> &#124; `void`

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
<a id="setwindow"></a>

##  setWindow

▸ **setWindow**(win: *[Window](_api_window_.window.md)*): `Promise`<`any`>

*Inherited from [Neovim](_api_neovim_.neovim.md).[setWindow](_api_neovim_.neovim.md#setwindow)*

*Defined in [api/Neovim.ts:117](https://github.com/neovim/node-client/blob/97a65c6/src/api/Neovim.ts#L117)*

**Parameters:**

| Param | Type |
| ------ | ------ |
| win | [Window](_api_window_.window.md) |

**Returns:** `Promise`<`any`>

___
<a id="setuptransport"></a>

##  setupTransport

▸ **setupTransport**(): `void`

*Defined in [api/client.ts:120](https://github.com/neovim/node-client/blob/97a65c6/src/api/client.ts#L120)*

**Returns:** `void`

___
<a id="strwidth"></a>

##  strWidth

▸ **strWidth**(str: *`string`*): `Promise`<`number`>

*Inherited from [Neovim](_api_neovim_.neovim.md).[strWidth](_api_neovim_.neovim.md#strwidth)*

*Defined in [api/Neovim.ts:317](https://github.com/neovim/node-client/blob/97a65c6/src/api/Neovim.ts#L317)*

Gets width of string

**Parameters:**

| Param | Type |
| ------ | ------ |
| str | `string` |

**Returns:** `Promise`<`number`>

___
<a id="subscribe"></a>

##  subscribe

▸ **subscribe**(event: *`string`*): `Promise`<`void`>

*Inherited from [Neovim](_api_neovim_.neovim.md).[subscribe](_api_neovim_.neovim.md#subscribe)*

*Defined in [api/Neovim.ts:367](https://github.com/neovim/node-client/blob/97a65c6/src/api/Neovim.ts#L367)*

Subscribe to nvim event broadcasts

**Parameters:**

| Param | Type |
| ------ | ------ |
| event | `string` |

**Returns:** `Promise`<`void`>

___
<a id="uiattach"></a>

##  uiAttach

▸ **uiAttach**(width: *`number`*, height: *`number`*, options: *[UiAttachOptions](../modules/_api_neovim_.md#uiattachoptions)*): `Promise`<`void`>

*Inherited from [Neovim](_api_neovim_.neovim.md).[uiAttach](_api_neovim_.neovim.md#uiattach)*

*Defined in [api/Neovim.ts:345](https://github.com/neovim/node-client/blob/97a65c6/src/api/Neovim.ts#L345)*

**Parameters:**

| Param | Type |
| ------ | ------ |
| width | `number` |
| height | `number` |
| options | [UiAttachOptions](../modules/_api_neovim_.md#uiattachoptions) |

**Returns:** `Promise`<`void`>

___
<a id="uidetach"></a>

##  uiDetach

▸ **uiDetach**(): `Promise`<`void`>

*Inherited from [Neovim](_api_neovim_.neovim.md).[uiDetach](_api_neovim_.neovim.md#uidetach)*

*Defined in [api/Neovim.ts:353](https://github.com/neovim/node-client/blob/97a65c6/src/api/Neovim.ts#L353)*

**Returns:** `Promise`<`void`>

___
<a id="uisetoption"></a>

##  uiSetOption

▸ **uiSetOption**(name: *`string`*, value: *`any`*): `Promise`<`void`>

*Inherited from [Neovim](_api_neovim_.neovim.md).[uiSetOption](_api_neovim_.neovim.md#uisetoption)*

*Defined in [api/Neovim.ts:362](https://github.com/neovim/node-client/blob/97a65c6/src/api/Neovim.ts#L362)*

Set UI Option

**Parameters:**

| Param | Type |
| ------ | ------ |
| name | `string` |
| value | `any` |

**Returns:** `Promise`<`void`>

___
<a id="uitryresize"></a>

##  uiTryResize

▸ **uiTryResize**(width: *`number`*, height: *`number`*): `Promise`<`void`>

*Inherited from [Neovim](_api_neovim_.neovim.md).[uiTryResize](_api_neovim_.neovim.md#uitryresize)*

*Defined in [api/Neovim.ts:357](https://github.com/neovim/node-client/blob/97a65c6/src/api/Neovim.ts#L357)*

**Parameters:**

| Param | Type |
| ------ | ------ |
| width | `number` |
| height | `number` |

**Returns:** `Promise`<`void`>

___
<a id="unsubscribe"></a>

##  unsubscribe

▸ **unsubscribe**(event: *`string`*): `Promise`<`void`>

*Inherited from [Neovim](_api_neovim_.neovim.md).[unsubscribe](_api_neovim_.neovim.md#unsubscribe)*

*Defined in [api/Neovim.ts:372](https://github.com/neovim/node-client/blob/97a65c6/src/api/Neovim.ts#L372)*

Unsubscribe to nvim event broadcasts

**Parameters:**

| Param | Type |
| ------ | ------ |
| event | `string` |

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

