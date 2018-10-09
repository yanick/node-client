

# Hierarchy

**IModule**

# Constructors

<a id="constructor"></a>

##  constructor

⊕ **new IModule**(name: *`string`*): `any`

*Defined in [host/factory.ts:14](https://github.com/neovim/node-client/blob/97a65c6/src/host/factory.ts#L14)*

**Parameters:**

| Param | Type |
| ------ | ------ |
| name | `string` |

**Returns:** `any`

___

# Properties

<a id="_cache"></a>

##  _cache

**● _cache**: *`object`*

*Defined in [host/factory.ts:18](https://github.com/neovim/node-client/blob/97a65c6/src/host/factory.ts#L18)*

#### Type declaration

[file: `string`]: `any`

___
<a id="_compile"></a>

##  _compile

**● _compile**: *`function`*

*Defined in [host/factory.ts:19](https://github.com/neovim/node-client/blob/97a65c6/src/host/factory.ts#L19)*

#### Type declaration
▸(): `void`

**Returns:** `void`

___
<a id="_extensions"></a>

##  _extensions

**● _extensions**: *`__type`*

*Defined in [host/factory.ts:17](https://github.com/neovim/node-client/blob/97a65c6/src/host/factory.ts#L17)*

___
<a id="_nodemodulepaths"></a>

##  _nodeModulePaths

**● _nodeModulePaths**: *`function`*

*Defined in [host/factory.ts:22](https://github.com/neovim/node-client/blob/97a65c6/src/host/factory.ts#L22)*

#### Type declaration
▸(filename: *`string`*): `string`[]

**Parameters:**

| Param | Type |
| ------ | ------ |
| filename | `string` |

**Returns:** `string`[]

___
<a id="_resolvefilename"></a>

##  _resolveFilename

**● _resolveFilename**: *`function`*

*Defined in [host/factory.ts:16](https://github.com/neovim/node-client/blob/97a65c6/src/host/factory.ts#L16)*

#### Type declaration
▸(file: *`string`*, context: *`any`*): `string`

**Parameters:**

| Param | Type |
| ------ | ------ |
| file | `string` |
| context | `any` |

**Returns:** `string`

___
<a id="require"></a>

##  require

**● require**: *`function`*

*Defined in [host/factory.ts:21](https://github.com/neovim/node-client/blob/97a65c6/src/host/factory.ts#L21)*

#### Type declaration
▸(file: *`string`*): `NodeModule`

**Parameters:**

| Param | Type |
| ------ | ------ |
| file | `string` |

**Returns:** `NodeModule`

___
<a id="wrap"></a>

##  wrap

**● wrap**: *`function`*

*Defined in [host/factory.ts:20](https://github.com/neovim/node-client/blob/97a65c6/src/host/factory.ts#L20)*

#### Type declaration
▸(content: *`string`*): `string`

**Parameters:**

| Param | Type |
| ------ | ------ |
| content | `string` |

**Returns:** `string`

___

