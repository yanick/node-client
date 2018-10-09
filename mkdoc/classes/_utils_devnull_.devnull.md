

# Hierarchy

 `Duplex`

**↳ DevNull**

# Implements

* `ReadableStream`
* `Writable`

# Constructors

<a id="constructor"></a>

##  constructor

⊕ **new DevNull**(opts?: *`DuplexOptions`*): [DevNull](_utils_devnull_.devnull.md)

*Inherited from Duplex.__constructor*

*Overrides Readable.__constructor*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:3928*

**Parameters:**

| Param | Type |
| ------ | ------ |
| `Optional` opts | `DuplexOptions` |

**Returns:** [DevNull](_utils_devnull_.devnull.md)

___

# Properties

<a id="readable"></a>

##  readable

**● readable**: *`boolean`*

*Inherited from Readable.readable*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:3761*

___
<a id="writable"></a>

##  writable

**● writable**: *`boolean`*

*Inherited from Duplex.writable*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:3928*

___
<a id="defaultmaxlisteners"></a>

## `<Static>` defaultMaxListeners

**● defaultMaxListeners**: *`number`*

*Inherited from EventEmitter.defaultMaxListeners*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:712*

___

# Methods

<a id="_read"></a>

##  _read

▸ **_read**(): `void`

*Overrides Readable._read*

*Defined in [utils/devnull.ts:4](https://github.com/neovim/node-client/blob/97a65c6/src/utils/devnull.ts#L4)*

**Returns:** `void`

___
<a id="_write"></a>

##  _write

▸ **_write**(chunk: *`any`*, enc: *`any`*, cb: *`Function`*): `void`

*Overrides Duplex._write*

*Defined in [utils/devnull.ts:5](https://github.com/neovim/node-client/blob/97a65c6/src/utils/devnull.ts#L5)*

**Parameters:**

| Param | Type |
| ------ | ------ |
| chunk | `any` |
| enc | `any` |
| cb | `Function` |

**Returns:** `void`

___
<a id="addlistener"></a>

##  addListener

▸ **addListener**(event: *`string`*, listener: *`Function`*): `this`

▸ **addListener**(event: *"close"*, listener: *`function`*): `this`

▸ **addListener**(event: *"data"*, listener: *`function`*): `this`

▸ **addListener**(event: *"end"*, listener: *`function`*): `this`

▸ **addListener**(event: *"readable"*, listener: *`function`*): `this`

▸ **addListener**(event: *"error"*, listener: *`function`*): `this`

*Inherited from Readable.addListener*

*Overrides EventEmitter.addListener*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:3784*

Event emitter The defined events on documents including:

1.  close
2.  data
3.  end
4.  readable
5.  error

**Parameters:**

| Param | Type |
| ------ | ------ |
| event | `string` |
| listener | `Function` |

**Returns:** `this`

*Inherited from Readable.addListener*

*Overrides EventEmitter.addListener*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:3785*

**Parameters:**

| Param | Type |
| ------ | ------ |
| event | "close" |
| listener | `function` |

**Returns:** `this`

*Inherited from Readable.addListener*

*Overrides EventEmitter.addListener*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:3786*

**Parameters:**

| Param | Type |
| ------ | ------ |
| event | "data" |
| listener | `function` |

**Returns:** `this`

*Inherited from Readable.addListener*

*Overrides EventEmitter.addListener*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:3787*

**Parameters:**

| Param | Type |
| ------ | ------ |
| event | "end" |
| listener | `function` |

**Returns:** `this`

*Inherited from Readable.addListener*

*Overrides EventEmitter.addListener*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:3788*

**Parameters:**

| Param | Type |
| ------ | ------ |
| event | "readable" |
| listener | `function` |

**Returns:** `this`

*Inherited from Readable.addListener*

*Overrides EventEmitter.addListener*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:3789*

**Parameters:**

| Param | Type |
| ------ | ------ |
| event | "error" |
| listener | `function` |

**Returns:** `this`

___
<a id="emit"></a>

##  emit

▸ **emit**(event: * `string` &#124; `symbol`*, ...args: *`any`[]*): `boolean`

▸ **emit**(event: *"close"*): `boolean`

▸ **emit**(event: *"data"*, chunk: * `Buffer` &#124; `string`*): `boolean`

▸ **emit**(event: *"end"*): `boolean`

▸ **emit**(event: *"readable"*): `boolean`

▸ **emit**(event: *"error"*, err: *`Error`*): `boolean`

*Inherited from Readable.emit*

*Overrides EventEmitter.emit*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:3791*

**Parameters:**

| Param | Type |
| ------ | ------ |
| event |  `string` &#124; `symbol`|
| `Rest` args | `any`[] |

**Returns:** `boolean`

*Inherited from Readable.emit*

*Overrides EventEmitter.emit*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:3792*

**Parameters:**

| Param | Type |
| ------ | ------ |
| event | "close" |

**Returns:** `boolean`

*Inherited from Readable.emit*

*Overrides EventEmitter.emit*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:3793*

**Parameters:**

| Param | Type |
| ------ | ------ |
| event | "data" |
| chunk |  `Buffer` &#124; `string`|

**Returns:** `boolean`

*Inherited from Readable.emit*

*Overrides EventEmitter.emit*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:3794*

**Parameters:**

| Param | Type |
| ------ | ------ |
| event | "end" |

**Returns:** `boolean`

*Inherited from Readable.emit*

*Overrides EventEmitter.emit*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:3795*

**Parameters:**

| Param | Type |
| ------ | ------ |
| event | "readable" |

**Returns:** `boolean`

*Inherited from Readable.emit*

*Overrides EventEmitter.emit*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:3796*

**Parameters:**

| Param | Type |
| ------ | ------ |
| event | "error" |
| err | `Error` |

**Returns:** `boolean`

___
<a id="end"></a>

##  end

▸ **end**(cb?: *`Function`*): `void`

▸ **end**(chunk: *`any`*, cb?: *`Function`*): `void`

▸ **end**(chunk: *`any`*, encoding?: *`string`*, cb?: *`Function`*): `void`

*Inherited from Duplex.end*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:3934*

**Parameters:**

| Param | Type |
| ------ | ------ |
| `Optional` cb | `Function` |

**Returns:** `void`

*Inherited from Duplex.end*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:3935*

**Parameters:**

| Param | Type |
| ------ | ------ |
| chunk | `any` |
| `Optional` cb | `Function` |

**Returns:** `void`

*Inherited from Duplex.end*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:3936*

**Parameters:**

| Param | Type |
| ------ | ------ |
| chunk | `any` |
| `Optional` encoding | `string` |
| `Optional` cb | `Function` |

**Returns:** `void`

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
<a id="ispaused"></a>

##  isPaused

▸ **isPaused**(): `boolean`

*Inherited from Readable.isPaused*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:3768*

**Returns:** `boolean`

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
<a id="on"></a>

##  on

▸ **on**(event: *`string`*, listener: *`Function`*): `this`

▸ **on**(event: *"close"*, listener: *`function`*): `this`

▸ **on**(event: *"data"*, listener: *`function`*): `this`

▸ **on**(event: *"end"*, listener: *`function`*): `this`

▸ **on**(event: *"readable"*, listener: *`function`*): `this`

▸ **on**(event: *"error"*, listener: *`function`*): `this`

*Inherited from Readable.on*

*Overrides EventEmitter.on*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:3798*

**Parameters:**

| Param | Type |
| ------ | ------ |
| event | `string` |
| listener | `Function` |

**Returns:** `this`

*Inherited from Readable.on*

*Overrides EventEmitter.on*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:3799*

**Parameters:**

| Param | Type |
| ------ | ------ |
| event | "close" |
| listener | `function` |

**Returns:** `this`

*Inherited from Readable.on*

*Overrides EventEmitter.on*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:3800*

**Parameters:**

| Param | Type |
| ------ | ------ |
| event | "data" |
| listener | `function` |

**Returns:** `this`

*Inherited from Readable.on*

*Overrides EventEmitter.on*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:3801*

**Parameters:**

| Param | Type |
| ------ | ------ |
| event | "end" |
| listener | `function` |

**Returns:** `this`

*Inherited from Readable.on*

*Overrides EventEmitter.on*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:3802*

**Parameters:**

| Param | Type |
| ------ | ------ |
| event | "readable" |
| listener | `function` |

**Returns:** `this`

*Inherited from Readable.on*

*Overrides EventEmitter.on*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:3803*

**Parameters:**

| Param | Type |
| ------ | ------ |
| event | "error" |
| listener | `function` |

**Returns:** `this`

___
<a id="once"></a>

##  once

▸ **once**(event: *`string`*, listener: *`Function`*): `this`

▸ **once**(event: *"close"*, listener: *`function`*): `this`

▸ **once**(event: *"data"*, listener: *`function`*): `this`

▸ **once**(event: *"end"*, listener: *`function`*): `this`

▸ **once**(event: *"readable"*, listener: *`function`*): `this`

▸ **once**(event: *"error"*, listener: *`function`*): `this`

*Inherited from Readable.once*

*Overrides EventEmitter.once*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:3805*

**Parameters:**

| Param | Type |
| ------ | ------ |
| event | `string` |
| listener | `Function` |

**Returns:** `this`

*Inherited from Readable.once*

*Overrides EventEmitter.once*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:3806*

**Parameters:**

| Param | Type |
| ------ | ------ |
| event | "close" |
| listener | `function` |

**Returns:** `this`

*Inherited from Readable.once*

*Overrides EventEmitter.once*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:3807*

**Parameters:**

| Param | Type |
| ------ | ------ |
| event | "data" |
| listener | `function` |

**Returns:** `this`

*Inherited from Readable.once*

*Overrides EventEmitter.once*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:3808*

**Parameters:**

| Param | Type |
| ------ | ------ |
| event | "end" |
| listener | `function` |

**Returns:** `this`

*Inherited from Readable.once*

*Overrides EventEmitter.once*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:3809*

**Parameters:**

| Param | Type |
| ------ | ------ |
| event | "readable" |
| listener | `function` |

**Returns:** `this`

*Inherited from Readable.once*

*Overrides EventEmitter.once*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:3810*

**Parameters:**

| Param | Type |
| ------ | ------ |
| event | "error" |
| listener | `function` |

**Returns:** `this`

___
<a id="pause"></a>

##  pause

▸ **pause**(): `this`

*Inherited from Readable.pause*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:3766*

**Returns:** `this`

___
<a id="pipe"></a>

##  pipe

▸ **pipe**<`T`>(destination: *`T`*, options?: *`object`*): `T`

*Inherited from Readable.pipe*

*Overrides internal.pipe*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:3769*

**Type parameters:**

#### T :  `WritableStream`
**Parameters:**

**destination: `T`**

**`Optional` options: `object`**

| Param | Type |
| ------ | ------ |
| `Optional` end | `boolean` |

**Returns:** `T`

___
<a id="prependlistener"></a>

##  prependListener

▸ **prependListener**(event: *`string`*, listener: *`Function`*): `this`

▸ **prependListener**(event: *"close"*, listener: *`function`*): `this`

▸ **prependListener**(event: *"data"*, listener: *`function`*): `this`

▸ **prependListener**(event: *"end"*, listener: *`function`*): `this`

▸ **prependListener**(event: *"readable"*, listener: *`function`*): `this`

▸ **prependListener**(event: *"error"*, listener: *`function`*): `this`

*Inherited from Readable.prependListener*

*Overrides EventEmitter.prependListener*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:3812*

**Parameters:**

| Param | Type |
| ------ | ------ |
| event | `string` |
| listener | `Function` |

**Returns:** `this`

*Inherited from Readable.prependListener*

*Overrides EventEmitter.prependListener*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:3813*

**Parameters:**

| Param | Type |
| ------ | ------ |
| event | "close" |
| listener | `function` |

**Returns:** `this`

*Inherited from Readable.prependListener*

*Overrides EventEmitter.prependListener*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:3814*

**Parameters:**

| Param | Type |
| ------ | ------ |
| event | "data" |
| listener | `function` |

**Returns:** `this`

*Inherited from Readable.prependListener*

*Overrides EventEmitter.prependListener*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:3815*

**Parameters:**

| Param | Type |
| ------ | ------ |
| event | "end" |
| listener | `function` |

**Returns:** `this`

*Inherited from Readable.prependListener*

*Overrides EventEmitter.prependListener*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:3816*

**Parameters:**

| Param | Type |
| ------ | ------ |
| event | "readable" |
| listener | `function` |

**Returns:** `this`

*Inherited from Readable.prependListener*

*Overrides EventEmitter.prependListener*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:3817*

**Parameters:**

| Param | Type |
| ------ | ------ |
| event | "error" |
| listener | `function` |

**Returns:** `this`

___
<a id="prependoncelistener"></a>

##  prependOnceListener

▸ **prependOnceListener**(event: *`string`*, listener: *`Function`*): `this`

▸ **prependOnceListener**(event: *"close"*, listener: *`function`*): `this`

▸ **prependOnceListener**(event: *"data"*, listener: *`function`*): `this`

▸ **prependOnceListener**(event: *"end"*, listener: *`function`*): `this`

▸ **prependOnceListener**(event: *"readable"*, listener: *`function`*): `this`

▸ **prependOnceListener**(event: *"error"*, listener: *`function`*): `this`

*Inherited from Readable.prependOnceListener*

*Overrides EventEmitter.prependOnceListener*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:3819*

**Parameters:**

| Param | Type |
| ------ | ------ |
| event | `string` |
| listener | `Function` |

**Returns:** `this`

*Inherited from Readable.prependOnceListener*

*Overrides EventEmitter.prependOnceListener*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:3820*

**Parameters:**

| Param | Type |
| ------ | ------ |
| event | "close" |
| listener | `function` |

**Returns:** `this`

*Inherited from Readable.prependOnceListener*

*Overrides EventEmitter.prependOnceListener*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:3821*

**Parameters:**

| Param | Type |
| ------ | ------ |
| event | "data" |
| listener | `function` |

**Returns:** `this`

*Inherited from Readable.prependOnceListener*

*Overrides EventEmitter.prependOnceListener*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:3822*

**Parameters:**

| Param | Type |
| ------ | ------ |
| event | "end" |
| listener | `function` |

**Returns:** `this`

*Inherited from Readable.prependOnceListener*

*Overrides EventEmitter.prependOnceListener*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:3823*

**Parameters:**

| Param | Type |
| ------ | ------ |
| event | "readable" |
| listener | `function` |

**Returns:** `this`

*Inherited from Readable.prependOnceListener*

*Overrides EventEmitter.prependOnceListener*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:3824*

**Parameters:**

| Param | Type |
| ------ | ------ |
| event | "error" |
| listener | `function` |

**Returns:** `this`

___
<a id="push"></a>

##  push

▸ **push**(chunk: *`any`*, encoding?: *`string`*): `boolean`

*Inherited from Readable.push*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:3773*

**Parameters:**

| Param | Type |
| ------ | ------ |
| chunk | `any` |
| `Optional` encoding | `string` |

**Returns:** `boolean`

___
<a id="read"></a>

##  read

▸ **read**(size?: *`number`*): `any`

*Inherited from Readable.read*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:3764*

**Parameters:**

| Param | Type |
| ------ | ------ |
| `Optional` size | `number` |

**Returns:** `any`

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

▸ **removeListener**(event: *`string`*, listener: *`Function`*): `this`

▸ **removeListener**(event: *"close"*, listener: *`function`*): `this`

▸ **removeListener**(event: *"data"*, listener: *`function`*): `this`

▸ **removeListener**(event: *"end"*, listener: *`function`*): `this`

▸ **removeListener**(event: *"readable"*, listener: *`function`*): `this`

▸ **removeListener**(event: *"error"*, listener: *`function`*): `this`

*Inherited from Readable.removeListener*

*Overrides EventEmitter.removeListener*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:3826*

**Parameters:**

| Param | Type |
| ------ | ------ |
| event | `string` |
| listener | `Function` |

**Returns:** `this`

*Inherited from Readable.removeListener*

*Overrides EventEmitter.removeListener*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:3827*

**Parameters:**

| Param | Type |
| ------ | ------ |
| event | "close" |
| listener | `function` |

**Returns:** `this`

*Inherited from Readable.removeListener*

*Overrides EventEmitter.removeListener*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:3828*

**Parameters:**

| Param | Type |
| ------ | ------ |
| event | "data" |
| listener | `function` |

**Returns:** `this`

*Inherited from Readable.removeListener*

*Overrides EventEmitter.removeListener*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:3829*

**Parameters:**

| Param | Type |
| ------ | ------ |
| event | "end" |
| listener | `function` |

**Returns:** `this`

*Inherited from Readable.removeListener*

*Overrides EventEmitter.removeListener*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:3830*

**Parameters:**

| Param | Type |
| ------ | ------ |
| event | "readable" |
| listener | `function` |

**Returns:** `this`

*Inherited from Readable.removeListener*

*Overrides EventEmitter.removeListener*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:3831*

**Parameters:**

| Param | Type |
| ------ | ------ |
| event | "error" |
| listener | `function` |

**Returns:** `this`

___
<a id="resume"></a>

##  resume

▸ **resume**(): `this`

*Inherited from Readable.resume*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:3767*

**Returns:** `this`

___
<a id="setdefaultencoding"></a>

##  setDefaultEncoding

▸ **setDefaultEncoding**(encoding: *`string`*): `this`

*Inherited from Duplex.setDefaultEncoding*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:3933*

**Parameters:**

| Param | Type |
| ------ | ------ |
| encoding | `string` |

**Returns:** `this`

___
<a id="setencoding"></a>

##  setEncoding

▸ **setEncoding**(encoding: *`string`*): `this`

*Inherited from Readable.setEncoding*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:3765*

**Parameters:**

| Param | Type |
| ------ | ------ |
| encoding | `string` |

**Returns:** `this`

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
<a id="unpipe"></a>

##  unpipe

▸ **unpipe**<`T`>(destination?: *`T`*): `this`

*Inherited from Readable.unpipe*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:3770*

**Type parameters:**

#### T :  `WritableStream`
**Parameters:**

| Param | Type |
| ------ | ------ |
| `Optional` destination | `T` |

**Returns:** `this`

___
<a id="unshift"></a>

##  unshift

▸ **unshift**(chunk: *`any`*): `void`

*Inherited from Readable.unshift*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:3771*

**Parameters:**

| Param | Type |
| ------ | ------ |
| chunk | `any` |

**Returns:** `void`

___
<a id="wrap"></a>

##  wrap

▸ **wrap**(oldStream: *`ReadableStream`*): `Readable`

*Inherited from Readable.wrap*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:3772*

**Parameters:**

| Param | Type |
| ------ | ------ |
| oldStream | `ReadableStream` |

**Returns:** `Readable`

___
<a id="write"></a>

##  write

▸ **write**(chunk: *`any`*, cb?: *`Function`*): `boolean`

▸ **write**(chunk: *`any`*, encoding?: *`string`*, cb?: *`Function`*): `boolean`

*Inherited from Duplex.write*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:3931*

**Parameters:**

| Param | Type |
| ------ | ------ |
| chunk | `any` |
| `Optional` cb | `Function` |

**Returns:** `boolean`

*Inherited from Duplex.write*

*Defined in /home/yanick/work/javascript/node-client/node_modules/@types/node/index.d.ts:3932*

**Parameters:**

| Param | Type |
| ------ | ------ |
| chunk | `any` |
| `Optional` encoding | `string` |
| `Optional` cb | `Function` |

**Returns:** `boolean`

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

