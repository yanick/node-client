

# Hierarchy

↳  [Window](../classes/_api_window_.window.md)

 `Promise`<[Window](../classes/_api_window_.window.md)>

**↳ AsyncWindow**

# Constructors

<a id="constructor"></a>

##  constructor

⊕ **new AsyncWindow**(__namedParameters: *`object`*): [AsyncWindow](_api_window_.asyncwindow.md)

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

**Returns:** [AsyncWindow](_api_window_.asyncwindow.md)

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

**● prefix**: *`string`* =  Metadata[ExtType.Window].prefix

*Inherited from [Window](../classes/_api_window_.window.md).[prefix](../classes/_api_window_.window.md#prefix)*

*Overrides [BaseApi](../classes/_api_base_.baseapi.md).[prefix](../classes/_api_base_.baseapi.md#prefix)*

*Defined in [api/Window.ts:10](https://github.com/neovim/node-client/blob/97a65c6/src/api/Window.ts#L10)*

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

<a id="buffer"></a>

##  buffer

getbuffer(): [AsyncBuffer](_api_buffer_.asyncbuffer.md)

*Inherited from [Window](../classes/_api_window_.window.md).[buffer](../classes/_api_window_.window.md#buffer)*

*Defined in [api/Window.ts:20](https://github.com/neovim/node-client/blob/97a65c6/src/api/Window.ts#L20)*

Get current buffer of window

**Returns:** [AsyncBuffer](_api_buffer_.asyncbuffer.md)

___
<a id="col"></a>

##  col

getcol(): `Promise`<`number`>

*Inherited from [Window](../classes/_api_window_.window.md).[col](../classes/_api_window_.window.md#col)*

*Defined in [api/Window.ts:76](https://github.com/neovim/node-client/blob/97a65c6/src/api/Window.ts#L76)*

0-indexed, on-screen window position(col) in display cells.

**Returns:** `Promise`<`number`>

___
<a id="cursor"></a>

##  cursor

getcursor():  [`number`, `number`] &#124; `Promise`<[`number`, `number`]>setcursor(pos: * [`number`, `number`] &#124; `Promise`<[`number`, `number`]>*): `void`

*Inherited from [Window](../classes/_api_window_.window.md).[cursor](../classes/_api_window_.window.md#cursor)*

*Defined in [api/Window.ts:34](https://github.com/neovim/node-client/blob/97a65c6/src/api/Window.ts#L34)*

Get cursor position

**Returns:**  [`number`, `number`] &#124; `Promise`<[`number`, `number`]>

*Inherited from [Window](../classes/_api_window_.window.md).[cursor](../classes/_api_window_.window.md#cursor)*

*Defined in [api/Window.ts:39](https://github.com/neovim/node-client/blob/97a65c6/src/api/Window.ts#L39)*

Set cursor position

**Parameters:**

| Param | Type |
| ------ | ------ |
| pos |  [`number`, `number`] &#124; `Promise`<[`number`, `number`]>|

**Returns:** `void`

___
<a id="height"></a>

##  height

getheight():  `number` &#124; `Promise`<`number`>setheight(height: * `number` &#124; `Promise`<`number`>*): `void`

*Inherited from [Window](../classes/_api_window_.window.md).[height](../classes/_api_window_.window.md#height)*

*Defined in [api/Window.ts:44](https://github.com/neovim/node-client/blob/97a65c6/src/api/Window.ts#L44)*

Get window height by number of rows

**Returns:**  `number` &#124; `Promise`<`number`>

*Inherited from [Window](../classes/_api_window_.window.md).[height](../classes/_api_window_.window.md#height)*

*Defined in [api/Window.ts:49](https://github.com/neovim/node-client/blob/97a65c6/src/api/Window.ts#L49)*

Set window height by number of rows

**Parameters:**

| Param | Type |
| ------ | ------ |
| height |  `number` &#124; `Promise`<`number`>|

**Returns:** `void`

___
<a id="id"></a>

##  id

getid(): `number`

*Inherited from [Window](../classes/_api_window_.window.md).[id](../classes/_api_window_.window.md#id)*

*Defined in [api/Window.ts:15](https://github.com/neovim/node-client/blob/97a65c6/src/api/Window.ts#L15)*

The windowid that not change within a Vim session

**Returns:** `number`

___
<a id="number"></a>

##  number

getnumber(): `Promise`<`number`>

*Inherited from [Window](../classes/_api_window_.window.md).[number](../classes/_api_window_.window.md#number)*

*Defined in [api/Window.ts:88](https://github.com/neovim/node-client/blob/97a65c6/src/api/Window.ts#L88)*

Get window number

**Returns:** `Promise`<`number`>

___
<a id="position"></a>

##  position

getposition(): `Promise`<[`number`, `number`]>

*Inherited from [Window](../classes/_api_window_.window.md).[position](../classes/_api_window_.window.md#position)*

*Defined in [api/Window.ts:64](https://github.com/neovim/node-client/blob/97a65c6/src/api/Window.ts#L64)*

Get window position

**Returns:** `Promise`<[`number`, `number`]>

___
<a id="row"></a>

##  row

getrow(): `Promise`<`number`>

*Inherited from [Window](../classes/_api_window_.window.md).[row](../classes/_api_window_.window.md#row)*

*Defined in [api/Window.ts:69](https://github.com/neovim/node-client/blob/97a65c6/src/api/Window.ts#L69)*

0-indexed, on-screen window position(row) in display cells.

**Returns:** `Promise`<`number`>

___
<a id="tabpage"></a>

##  tabpage

gettabpage(): [AsyncTabpage](_api_tabpage_.asynctabpage.md)

*Inherited from [Window](../classes/_api_window_.window.md).[tabpage](../classes/_api_window_.window.md#tabpage)*

*Defined in [api/Window.ts:27](https://github.com/neovim/node-client/blob/97a65c6/src/api/Window.ts#L27)*

Get the Tabpage that contains the window

**Returns:** [AsyncTabpage](_api_tabpage_.asynctabpage.md)

___
<a id="valid"></a>

##  valid

getvalid(): `Promise`<`boolean`>

*Inherited from [Window](../classes/_api_window_.window.md).[valid](../classes/_api_window_.window.md#valid)*

*Defined in [api/Window.ts:83](https://github.com/neovim/node-client/blob/97a65c6/src/api/Window.ts#L83)*

Is window valid

**Returns:** `Promise`<`boolean`>

___
<a id="width"></a>

##  width

getwidth():  `number` &#124; `Promise`<`number`>setwidth(width: * `number` &#124; `Promise`<`number`>*): `void`

*Inherited from [Window](../classes/_api_window_.window.md).[width](../classes/_api_window_.window.md#width)*

*Defined in [api/Window.ts:54](https://github.com/neovim/node-client/blob/97a65c6/src/api/Window.ts#L54)*

Get window width by number of columns

**Returns:**  `number` &#124; `Promise`<`number`>

*Inherited from [Window](../classes/_api_window_.window.md).[width](../classes/_api_window_.window.md#width)*

*Defined in [api/Window.ts:59](https://github.com/neovim/node-client/blob/97a65c6/src/api/Window.ts#L59)*

Set window width by number of columns

**Parameters:**

| Param | Type |
| ------ | ------ |
| width |  `number` &#124; `Promise`<`number`>|

**Returns:** `void`

___

# Methods

<a id="__computed"></a>

##  __computed

▸ **__computed**(name: *`string`*, args?: *`any`[]*): `Promise`<`any`>

*Inherited from [BaseApi](../classes/_api_base_.baseapi.md).[__computed](../classes/_api_base_.baseapi.md#__computed)*

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

*Inherited from [BaseApi](../classes/_api_base_.baseapi.md).[_getArgsByPrefix](../classes/_api_base_.baseapi.md#_getargsbyprefix)*

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
<a id="catch"></a>

##  catch

▸ **catch**<`TResult`>(onrejected?: * `function` &#124; `undefined` &#124; `null`*): `Promise`< [Window](../classes/_api_window_.window.md) &#124; `TResult`>

*Inherited from Promise.catch*

*Defined in /home/yanick/work/javascript/node-client/node_modules/.registry.npmjs.org/typescript/3.0.3/node_modules/typescript/lib/lib.es5.d.ts:1343*

Attaches a callback for only the rejection of the Promise.

**Type parameters:**

#### TResult 
**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| `Optional` onrejected |  `function` &#124; `undefined` &#124; `null`|  The callback to execute when the Promise is rejected. |

**Returns:** `Promise`< [Window](../classes/_api_window_.window.md) &#124; `TResult`>
A Promise for the completion of the callback.

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

*Inherited from [BaseApi](../classes/_api_base_.baseapi.md).[request](../classes/_api_base_.baseapi.md#request)*

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

