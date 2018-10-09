

# Type aliases

<a id="apiinfo"></a>

##  ApiInfo

**Ƭ ApiInfo**: *`object`*

*Defined in [types/ApiInfo.ts:18](https://github.com/neovim/node-client/blob/97a65c6/src/types/ApiInfo.ts#L18)*

#### Type declaration

 error_types: `object`

 functions: [FunctionInfo](_types_apiinfo_.md#functioninfo)[]

 types: `object`

 ui_events: [UiEventInfo](_types_apiinfo_.md#uieventinfo)[]

 ui_options: `string`[]

 version: `object`

 api_compatible: `number`

 api_level: `number`

 api_prerelease: `number`

 major: `number`

 minor: `number`

 patch: `number`

___
<a id="functioninfo"></a>

##  FunctionInfo

**Ƭ FunctionInfo**: *`object`*

*Defined in [types/ApiInfo.ts:4](https://github.com/neovim/node-client/blob/97a65c6/src/types/ApiInfo.ts#L4)*

#### Type declaration

 method: `boolean`

 name: `string`

 parameters: [Parameters](_types_apiinfo_.md#parameters-1)[]

 return_type: `string`

 since: `number`

___
<a id="parameters-1"></a>

##  Parameters

**Ƭ Parameters**: *[`string`, `string`]*

*Defined in [types/ApiInfo.ts:2](https://github.com/neovim/node-client/blob/97a65c6/src/types/ApiInfo.ts#L2)*

___
<a id="uieventinfo"></a>

##  UiEventInfo

**Ƭ UiEventInfo**: *`object`*

*Defined in [types/ApiInfo.ts:12](https://github.com/neovim/node-client/blob/97a65c6/src/types/ApiInfo.ts#L12)*

#### Type declaration

 name: `string`

 parameters: [Parameters](_types_apiinfo_.md#parameters-1)[]

 since: `number`

___

