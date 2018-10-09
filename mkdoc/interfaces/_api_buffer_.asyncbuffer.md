

# Hierarchy

↳  [Buffer](../classes/_api_buffer_.buffer.md)

 `Promise`<[Buffer](../classes/_api_buffer_.buffer.md)>

**↳ AsyncBuffer**

# Constructors

<a id="constructor"></a>

##  constructor

⊕ **new AsyncBuffer**(__namedParameters: *`object`*): [AsyncBuffer](_api_buffer_.asyncbuffer.md)

*Inherited from [BaseApi](../classes/_api_base_.baseapi.md).[constructor](../classes/_api_base_.baseapi.md#constructor)*

*Defined in [api/Base.ts:33](https://github.com/neovim/node-client/blob/97a65c6/src/api/Base.ts#L33)*

**Parameters:**

**__namedParameters: `object`**

| Param | Type |
| ------ | ------ |
| client | `any` |
| data | `Buffer` |
| logger | `LoggerInstance` |
| metadata | `any` |
| transport | [Transport](../classes/_utils_transport_.transport.md) |

**Returns:** [AsyncBuffer](_api_buffer_.asyncbuffer.md)

___

# Properties

<a id="promise"></a>

##  Promise

**● Promise**: *`PromiseConstructor`*

*Defined in /home/yanick/work/javascript/node-client/node_modules/.registry.npmjs.org/typescript/3.0.3/node_modules/typescript/lib/lib.es2015.promise.d.ts:216*

___
<a id="___tostringtag"></a>

##  __@toStringTag

**● __@toStringTag**: *"Promise"*

*Inherited from Promise.[Symbol.toStringTag]*

*Defined in /home/yanick/work/javascript/node-client/node_modules/.registry.npmjs.org/typescript/3.0.3/node_modules/typescript/lib/lib.es2015.symbol.wellknown.d.ts:169*

___
<a id="_isready"></a>

## `<Protected>` _isReady

**● _isReady**: *`Promise`<`boolean`>*

*Inherited from [BaseApi](../classes/_api_base_.baseapi.md).[_isReady](../classes/_api_base_.baseapi.md#_isready)*

*Defined in [api/Base.ts:29](https://github.com/neovim/node-client/blob/97a65c6/src/api/Base.ts#L29)*

___
<a id="client"></a>

## `<Protected>` client

**● client**: *`any`*

*Inherited from [BaseApi](../classes/_api_base_.baseapi.md).[client](../classes/_api_base_.baseapi.md#client)*

*Defined in [api/Base.ts:33](https://github.com/neovim/node-client/blob/97a65c6/src/api/Base.ts#L33)*

___
<a id="data"></a>

##  data

**● data**: * `Buffer` &#124; `Number`
*

*Inherited from [BaseApi](../classes/_api_base_.baseapi.md).[data](../classes/_api_base_.baseapi.md#data)*

*Defined in [api/Base.ts:32](https://github.com/neovim/node-client/blob/97a65c6/src/api/Base.ts#L32)*

___
<a id="logger"></a>

##  logger

**● logger**: *[ILogger](../modules/_utils_logger_.md#ilogger)*

*Inherited from [BaseApi](../classes/_api_base_.baseapi.md).[logger](../classes/_api_base_.baseapi.md#logger)*

*Defined in [api/Base.ts:31](https://github.com/neovim/node-client/blob/97a65c6/src/api/Base.ts#L31)*

___
<a id="prefix"></a>

##  prefix

**● prefix**: *`string`* =  Metadata[ExtType.Buffer].prefix

*Inherited from [Buffer](../classes/_api_buffer_.buffer.md).[prefix](../classes/_api_buffer_.buffer.md#prefix)*

*Overrides [BaseApi](../classes/_api_base_.baseapi.md).[prefix](../classes/_api_base_.baseapi.md#prefix)*

*Defined in [api/Buffer.ts:26](https://github.com/neovim/node-client/blob/97a65c6/src/api/Buffer.ts#L26)*

___
<a id="transport"></a>

## `<Protected>` transport

**● transport**: *[Transport](../classes/_utils_transport_.transport.md)*

*Inherited from [BaseApi](../classes/_api_base_.baseapi.md).[transport](../classes/_api_base_.baseapi.md#transport)*

*Defined in [api/Base.ts:28](https://github.com/neovim/node-client/blob/97a65c6/src/api/Base.ts#L28)*

___
<a id="defaultmaxlisteners"></a>

## `<Static>` defaultMaxListeners

**● defaultMaxListeners**: *`number`*

*Inherited from EventEmitter.defaultMaxListeners*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:712*

___

# Accessors

<a id="changedtick"></a>

##  changedtick

getchangedtick(): `Promise`<`number`>

*Inherited from [Buffer](../classes/_api_buffer_.buffer.md).[changedtick](../classes/_api_buffer_.buffer.md#changedtick)*

*Defined in [api/Buffer.ts:64](https://github.com/neovim/node-client/blob/97a65c6/src/api/Buffer.ts#L64)*

Gets a changed tick of a buffer

**Returns:** `Promise`<`number`>

___
<a id="commands"></a>

##  commands

getcommands(): `Promise`<`Object`>

*Inherited from [Buffer](../classes/_api_buffer_.buffer.md).[commands](../classes/_api_buffer_.buffer.md#commands)*

*Defined in [api/Buffer.ts:68](https://github.com/neovim/node-client/blob/97a65c6/src/api/Buffer.ts#L68)*

**Returns:** `Promise`<`Object`>

___
<a id="id"></a>

##  id

getid(): `number`

*Inherited from [Buffer](../classes/_api_buffer_.buffer.md).[id](../classes/_api_buffer_.buffer.md#id)*

*Defined in [api/Buffer.ts:47](https://github.com/neovim/node-client/blob/97a65c6/src/api/Buffer.ts#L47)*

Get the bufnr of Buffer

**Returns:** `number`

___
<a id="length"></a>

##  length

getlength(): `Promise`<`number`>

*Inherited from [Buffer](../classes/_api_buffer_.buffer.md).[length](../classes/_api_buffer_.buffer.md#length)*

*Defined in [api/Buffer.ts:52](https://github.com/neovim/node-client/blob/97a65c6/src/api/Buffer.ts#L52)*

Total number of lines in buffer

**Returns:** `Promise`<`number`>

___
<a id="lines"></a>

##  lines

getlines(): `Promise`<`Array`<`string`>>

*Inherited from [Buffer](../classes/_api_buffer_.buffer.md).[lines](../classes/_api_buffer_.buffer.md#lines)*

*Defined in [api/Buffer.ts:59](https://github.com/neovim/node-client/blob/97a65c6/src/api/Buffer.ts#L59)*

Get all lines in buffer

**Returns:** `Promise`<`Array`<`string`>>

___
<a id="name"></a>

##  name

getname():  `string` &#124; `Promise`<`string`>setname(value: * `string` &#124; `Promise`<`string`>*): `void`

*Inherited from [Buffer](../classes/_api_buffer_.buffer.md).[name](../classes/_api_buffer_.buffer.md#name)*

*Defined in [api/Buffer.ts:148](https://github.com/neovim/node-client/blob/97a65c6/src/api/Buffer.ts#L148)*

Get buffer name

**Returns:**  `string` &#124; `Promise`<`string`>

*Inherited from [Buffer](../classes/_api_buffer_.buffer.md).[name](../classes/_api_buffer_.buffer.md#name)*

*Defined in [api/Buffer.ts:153](https://github.com/neovim/node-client/blob/97a65c6/src/api/Buffer.ts#L153)*

Set current buffer name

**Parameters:**

| Param | Type |
| ------ | ------ |
| value |  `string` &#124; `Promise`<`string`>|

**Returns:** `void`

___
<a id="valid"></a>

##  valid

getvalid(): `Promise`<`boolean`>

*Inherited from [Buffer](../classes/_api_buffer_.buffer.md).[valid](../classes/_api_buffer_.buffer.md#valid)*

*Defined in [api/Buffer.ts:158](https://github.com/neovim/node-client/blob/97a65c6/src/api/Buffer.ts#L158)*

Is current buffer valid

**Returns:** `Promise`<`boolean`>

___

# Methods

<a id="__computed"></a>

##  __computed

▸ **__computed**(sendBuffer?: *`boolean`*, options?: *`__type`*): `Promise`<`any`>

▸ **__computed**(): `Promise`<`any`>

*Inherited from [Buffer](../classes/_api_buffer_.buffer.md).[__computed](../classes/_api_buffer_.buffer.md#__computed)*

*Overrides [BaseApi](../classes/_api_base_.baseapi.md).[__computed](../classes/_api_base_.baseapi.md#__computed)*

*Defined in [api/Buffer.ts:36](https://github.com/neovim/node-client/blob/97a65c6/src/api/Buffer.ts#L36)*

Attach to buffer to listen to buffer events Detach from buffer to stop listening to buffer events

**Parameters:**

| Param | Type | Default value | Description |
| ------ | ------ | ------ | ------ |
| `Default value` sendBuffer | `boolean` | false |  Set to true if the initial notification should contain the whole buffer. If so, the first notification will be a \`nvim\_buf\_lines\_event\`. Otherwise, the first notification will be a \`nvim\_buf\_changedtick\_event\` |
| `Default value` options | `__type` |  {} |

**Returns:** `Promise`<`any`>

*Inherited from [Buffer](../classes/_api_buffer_.buffer.md).[__computed](../classes/_api_buffer_.buffer.md#__computed)*

*Overrides [BaseApi](../classes/_api_base_.baseapi.md).[__computed](../classes/_api_base_.baseapi.md#__computed)*

*Defined in [api/Buffer.ts:42](https://github.com/neovim/node-client/blob/97a65c6/src/api/Buffer.ts#L42)*

Attach to buffer to listen to buffer events Detach from buffer to stop listening to buffer events

**Returns:** `Promise`<`any`>

___
<a id="_getargsbyprefix"></a>

##  _getArgsByPrefix

▸ **_getArgsByPrefix**(...args: *`any`[]*): `this`[]

*Inherited from [BaseApi](../classes/_api_base_.baseapi.md).[_getArgsByPrefix](../classes/_api_base_.baseapi.md#_getargsbyprefix)*

*Defined in [api/Base.ts:89](https://github.com/neovim/node-client/blob/97a65c6/src/api/Base.ts#L89)*

**Parameters:**

| Param | Type |
| ------ | ------ |
| `Rest` args | `any`[] |

**Returns:** `this`[]

___
<a id="addhighlight"></a>

##  addHighlight

▸ **addHighlight**(__namedParameters: *`object`*): `Promise`<`number`>

*Inherited from [Buffer](../classes/_api_buffer_.buffer.md).[addHighlight](../classes/_api_buffer_.buffer.md#addhighlight)*

*Defined in [api/Buffer.ts:200](https://github.com/neovim/node-client/blob/97a65c6/src/api/Buffer.ts#L200)*

Adds a highlight to buffer.

This can be used for plugins which dynamically generate highlights to a buffer (like a semantic highlighter or linter). The function adds a single highlight to a buffer. Unlike matchaddpos() highlights follow changes to line numbering (as lines are inserted/removed above the highlighted line), like signs and marks do.

"src\_id" is useful for batch deletion/updating of a set of highlights. When called with src\_id = 0, an unique source id is generated and returned. Succesive calls can pass in it as "src\_id" to add new highlights to the same source group. All highlights in the same group can then be cleared with nvim\_buf\_clear\_highlight. If the highlight never will be manually deleted pass in -1 for "src_id".

If "hl\_group" is the empty string no highlight is added, but a new src\_id is still returned. This is useful for an external plugin to synchrounously request an unique src_id at initialization, and later asynchronously add and clear highlights in response to buffer changes.

**Parameters:**

**__namedParameters: `object`**

| Param | Type |
| ------ | ------ |
| _end | `number` |
| _hlGroup | `string` |
| _srcId | `number` |
| _start | `number` |
| line | `number` |

**Returns:** `Promise`<`number`>

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
<a id="append"></a>

##  append

▸ **append**(lines: * `Array`<`string`> &#124; `string`*): `Promise`<`any`>

*Inherited from [Buffer](../classes/_api_buffer_.buffer.md).[append](../classes/_api_buffer_.buffer.md#append)*

*Defined in [api/Buffer.ts:139](https://github.com/neovim/node-client/blob/97a65c6/src/api/Buffer.ts#L139)*

Append a string or list of lines to end of buffer

**Parameters:**

| Param | Type |
| ------ | ------ |
| lines |  `Array`<`string`> &#124; `string`|

**Returns:** `Promise`<`any`>

___
<a id="catch"></a>

##  catch

▸ **catch**<`TResult`>(onrejected?: * `function` &#124; `undefined` &#124; `null`*): `Promise`< [Buffer](../classes/_api_buffer_.buffer.md) &#124; `TResult`>

*Inherited from Promise.catch*

*Defined in /home/yanick/work/javascript/node-client/node_modules/.registry.npmjs.org/typescript/3.0.3/node_modules/typescript/lib/lib.es5.d.ts:1343*

Attaches a callback for only the rejection of the Promise.

**Type parameters:**

#### TResult 
**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| `Optional` onrejected |  `function` &#124; `undefined` &#124; `null`|  The callback to execute when the Promise is rejected. |

**Returns:** `Promise`< [Buffer](../classes/_api_buffer_.buffer.md) &#124; `TResult`>
A Promise for the completion of the callback.

___
<a id="clearhighlight"></a>

##  clearHighlight

▸ **clearHighlight**(args?: *[BufferClearHighlight](_api_buffer_.bufferclearhighlight.md)*): `Promise`<`any`>

*Inherited from [Buffer](../classes/_api_buffer_.buffer.md).[clearHighlight](../classes/_api_buffer_.buffer.md#clearhighlight)*

*Defined in [api/Buffer.ts:226](https://github.com/neovim/node-client/blob/97a65c6/src/api/Buffer.ts#L226)*

Clears highlights from a given source group and a range of lines

To clear a source group in the entire buffer, pass in 1 and -1 to lineStart and lineEnd respectively.

**Parameters:**

| Param | Type | Default value |
| ------ | ------ | ------ |
| `Default value` args | [BufferClearHighlight](_api_buffer_.bufferclearhighlight.md) |  {} |

**Returns:** `Promise`<`any`>

___
<a id="deletevar"></a>

##  deleteVar

▸ **deleteVar**(name: *`string`*): `Promise`<`void`>

*Inherited from [BaseApi](../classes/_api_base_.baseapi.md).[deleteVar](../classes/_api_base_.baseapi.md#deletevar)*

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

▸ **equals**(other: *[BaseApi](../classes/_api_base_.baseapi.md)*): `boolean`

*Inherited from [BaseApi](../classes/_api_base_.baseapi.md).[equals](../classes/_api_base_.baseapi.md#equals)*

*Defined in [api/Base.ts:58](https://github.com/neovim/node-client/blob/97a65c6/src/api/Base.ts#L58)*

**Parameters:**

| Param | Type |
| ------ | ------ |
| other | [BaseApi](../classes/_api_base_.baseapi.md) |

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
<a id="getcommands"></a>

##  getCommands

▸ **getCommands**(options?: *`object`*): `Promise`<`Object`>

*Inherited from [Buffer](../classes/_api_buffer_.buffer.md).[getCommands](../classes/_api_buffer_.buffer.md#getcommands)*

*Defined in [api/Buffer.ts:72](https://github.com/neovim/node-client/blob/97a65c6/src/api/Buffer.ts#L72)*

**Parameters:**

| Param | Type | Default value |
| ------ | ------ | ------ |
| `Default value` options | `object` |  {} |

**Returns:** `Promise`<`Object`>

___
<a id="getkeymap"></a>

##  getKeymap

▸ **getKeymap**(mode: *`string`*): `Promise`<`Array`<`any`>>

*Inherited from [Buffer](../classes/_api_buffer_.buffer.md).[getKeymap](../classes/_api_buffer_.buffer.md#getkeymap)*

*Defined in [api/Buffer.ts:173](https://github.com/neovim/node-client/blob/97a65c6/src/api/Buffer.ts#L173)*

Gets keymap

**Parameters:**

| Param | Type |
| ------ | ------ |
| mode | `string` |

**Returns:** `Promise`<`Array`<`any`>>

___
<a id="getlines"></a>

##  getLines

▸ **getLines**(__namedParameters?: *`object`*): `Promise`<`Array`<`string`>>

*Inherited from [Buffer](../classes/_api_buffer_.buffer.md).[getLines](../classes/_api_buffer_.buffer.md#getlines)*

*Defined in [api/Buffer.ts:77](https://github.com/neovim/node-client/blob/97a65c6/src/api/Buffer.ts#L77)*

Get specific lines of buffer

**Parameters:**

**`Default value` __namedParameters: `object`**

| Param | Type |
| ------ | ------ |
| end | `number` |
| start | `number` |
| strictIndexing | `boolean` |

**Returns:** `Promise`<`Array`<`string`>>

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

*Inherited from [BaseApi](../classes/_api_base_.baseapi.md).[getOption](../classes/_api_base_.baseapi.md#getoption)*

*Defined in [api/Base.ts:127](https://github.com/neovim/node-client/blob/97a65c6/src/api/Base.ts#L127)*

Retrieves a scoped option depending on type of `this`

**Parameters:**

| Param | Type |
| ------ | ------ |
| name | `string` |

**Returns:**  `Promise`<[VimValue](../modules/_types_vimvalue_.md#vimvalue)> &#124; `void`

___
<a id="getvar"></a>

##  getVar

▸ **getVar**(name: *`string`*): `Promise`<[VimValue](../modules/_types_vimvalue_.md#vimvalue)>

*Inherited from [BaseApi](../classes/_api_base_.baseapi.md).[getVar](../classes/_api_base_.baseapi.md#getvar)*

*Defined in [api/Base.ts:100](https://github.com/neovim/node-client/blob/97a65c6/src/api/Base.ts#L100)*

Retrieves a scoped variable depending on type (using `this.prefix`)

**Parameters:**

| Param | Type |
| ------ | ------ |
| name | `string` |

**Returns:** `Promise`<[VimValue](../modules/_types_vimvalue_.md#vimvalue)>

___
<a id="insert"></a>

##  insert

▸ **insert**(lines: * `Array`<`string`> &#124; `string`*, start: *`number`*): `Promise`<`any`>

*Inherited from [Buffer](../classes/_api_buffer_.buffer.md).[insert](../classes/_api_buffer_.buffer.md#insert)*

*Defined in [api/Buffer.ts:115](https://github.com/neovim/node-client/blob/97a65c6/src/api/Buffer.ts#L115)*

Insert lines at `start` index

**Parameters:**

| Param | Type |
| ------ | ------ |
| lines |  `Array`<`string`> &#124; `string`|
| start | `number` |

**Returns:** `Promise`<`any`>

___
<a id="listen"></a>

##  listen

▸ **listen**(eventName: *`string`*, cb: *`Function`*): `Function`

*Inherited from [Buffer](../classes/_api_buffer_.buffer.md).[listen](../classes/_api_buffer_.buffer.md#listen)*

*Defined in [api/Buffer.ts:246](https://github.com/neovim/node-client/blob/97a65c6/src/api/Buffer.ts#L246)*

Listens to buffer for events

**Parameters:**

| Param | Type |
| ------ | ------ |
| eventName | `string` |
| cb | `Function` |

**Returns:** `Function`

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
<a id="mark"></a>

##  mark

▸ **mark**(name: *`string`*): `Promise`<[`number`, `number`]>

*Inherited from [Buffer](../classes/_api_buffer_.buffer.md).[mark](../classes/_api_buffer_.buffer.md#mark)*

*Defined in [api/Buffer.ts:163](https://github.com/neovim/node-client/blob/97a65c6/src/api/Buffer.ts#L163)*

Get mark position given mark name

**Parameters:**

| Param | Type |
| ------ | ------ |
| name | `string` |

**Returns:** `Promise`<[`number`, `number`]>

___
<a id="notify"></a>

##  notify

▸ **notify**(name: *`string`*, args: *`any`[]*): `void`

*Inherited from [BaseApi](../classes/_api_base_.baseapi.md).[notify](../classes/_api_base_.baseapi.md#notify)*

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
<a id="remove"></a>

##  remove

▸ **remove**(start: *`number`*, end: *`number`*, strictIndexing: *`boolean`*): `Promise`<`any`>

*Inherited from [Buffer](../classes/_api_buffer_.buffer.md).[remove](../classes/_api_buffer_.buffer.md#remove)*

*Defined in [api/Buffer.ts:134](https://github.com/neovim/node-client/blob/97a65c6/src/api/Buffer.ts#L134)*

Remove lines at index

**Parameters:**

| Param | Type |
| ------ | ------ |
| start | `number` |
| end | `number` |
| strictIndexing | `boolean` |

**Returns:** `Promise`<`any`>

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
<a id="replace"></a>

##  replace

▸ **replace**(_lines: * `Array`<`string`> &#124; `string`*, start: *`number`*): `Promise`<`any`>

*Inherited from [Buffer](../classes/_api_buffer_.buffer.md).[replace](../classes/_api_buffer_.buffer.md#replace)*

*Defined in [api/Buffer.ts:124](https://github.com/neovim/node-client/blob/97a65c6/src/api/Buffer.ts#L124)*

Replace lines starting at `start` index

**Parameters:**

| Param | Type |
| ------ | ------ |
| _lines |  `Array`<`string`> &#124; `string`|
| start | `number` |

**Returns:** `Promise`<`any`>

___
<a id="request"></a>

##  request

▸ **request**(name: *`string`*, args?: *`any`[]*): `Promise`<`any`>

*Inherited from [BaseApi](../classes/_api_base_.baseapi.md).[request](../classes/_api_base_.baseapi.md#request)*

*Defined in [api/Base.ts:79](https://github.com/neovim/node-client/blob/97a65c6/src/api/Base.ts#L79)*

**Parameters:**

| Param | Type | Default value |
| ------ | ------ | ------ |
| name | `string` | - |
| `Default value` args | `any`[] |  [] |

**Returns:** `Promise`<`any`>

___
<a id="setlines"></a>

##  setLines

▸ **setLines**(_lines: * `string` &#124; `string`[]*, __namedParameters?: *`object`*): `Promise`<`any`>

*Inherited from [Buffer](../classes/_api_buffer_.buffer.md).[setLines](../classes/_api_buffer_.buffer.md#setlines)*

*Defined in [api/Buffer.ts:91](https://github.com/neovim/node-client/blob/97a65c6/src/api/Buffer.ts#L91)*

Set lines of buffer given indeces

**Parameters:**

**_lines:  `string` &#124; `string`[]
**

**`Default value` __namedParameters: `object`**

| Param | Type |
| ------ | ------ |
| _end | `number` |
| _start | `number` |
| strictIndexing | `boolean` |

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

*Inherited from [BaseApi](../classes/_api_base_.baseapi.md).[setOption](../classes/_api_base_.baseapi.md#setoption)*

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

▸ **setTransport**(transport: *[Transport](../classes/_utils_transport_.transport.md)*): `void`

*Inherited from [BaseApi](../classes/_api_base_.baseapi.md).[setTransport](../classes/_api_base_.baseapi.md#settransport)*

*Defined in [api/Base.ts:54](https://github.com/neovim/node-client/blob/97a65c6/src/api/Base.ts#L54)*

**Parameters:**

| Param | Type |
| ------ | ------ |
| transport | [Transport](../classes/_utils_transport_.transport.md) |

**Returns:** `void`

___
<a id="setvar"></a>

##  setVar

▸ **setVar**(name: *`string`*, value: *[VimValue](../modules/_types_vimvalue_.md#vimvalue)*): `Promise`<`void`>

*Inherited from [BaseApi](../classes/_api_base_.baseapi.md).[setVar](../classes/_api_base_.baseapi.md#setvar)*

*Defined in [api/Base.ts:115](https://github.com/neovim/node-client/blob/97a65c6/src/api/Base.ts#L115)*

Set a scoped variable

**Parameters:**

| Param | Type |
| ------ | ------ |
| name | `string` |
| value | [VimValue](../modules/_types_vimvalue_.md#vimvalue) |

**Returns:** `Promise`<`void`>

___
<a id="then"></a>

##  then

▸ **then**<`TResult1`,`TResult2`>(onfulfilled?: * `function` &#124; `undefined` &#124; `null`*, onrejected?: * `function` &#124; `undefined` &#124; `null`*): `Promise`< `TResult1` &#124; `TResult2`>

*Inherited from Promise.then*

*Defined in /home/yanick/work/javascript/node-client/node_modules/.registry.npmjs.org/typescript/3.0.3/node_modules/typescript/lib/lib.es5.d.ts:1336*

Attaches callbacks for the resolution and/or rejection of the Promise.

**Type parameters:**

#### TResult1 
#### TResult2 
**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| `Optional` onfulfilled |  `function` &#124; `undefined` &#124; `null`|  The callback to execute when the Promise is resolved. |
| `Optional` onrejected |  `function` &#124; `undefined` &#124; `null`|  The callback to execute when the Promise is rejected. |

**Returns:** `Promise`< `TResult1` &#124; `TResult2`>
A Promise for the completion of which ever callback is executed.

___
<a id="unlisten"></a>

##  unlisten

▸ **unlisten**(eventName: *`string`*, cb: *`Function`*): `void`

*Inherited from [Buffer](../classes/_api_buffer_.buffer.md).[unlisten](../classes/_api_buffer_.buffer.md#unlisten)*

*Defined in [api/Buffer.ts:258](https://github.com/neovim/node-client/blob/97a65c6/src/api/Buffer.ts#L258)*

**Parameters:**

| Param | Type |
| ------ | ------ |
| eventName | `string` |
| cb | `Function` |

**Returns:** `void`

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

