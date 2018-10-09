

# Index

### Enumerations

* [ExtType](../enums/_api_types_.exttype.md)

### Interfaces

* [ExtTypeConstructor](../interfaces/_api_types_.exttypeconstructor.md)

### Type aliases

* [MetadataType](_api_types_.md#metadatatype)

### Variables

* [Metadata](_api_types_.md#metadata)

---

# Type aliases

<a id="metadatatype"></a>

##  MetadataType

**Ƭ MetadataType**: *`object`*

*Defined in [api/types.ts:14](https://github.com/neovim/node-client/blob/97a65c6/src/api/types.ts#L14)*

#### Type declaration

 constructor: [ExtTypeConstructor](../interfaces/_api_types_.exttypeconstructor.md)< [Buffer](../classes/_api_buffer_.buffer.md) &#124; [Tabpage](../classes/_api_tabpage_.tabpage.md) &#124; [Window](../classes/_api_window_.window.md)>

 name: `string`

 prefix: `string`

___

# Variables

<a id="metadata"></a>

## `<Const>` Metadata

**● Metadata**: *[MetadataType](_api_types_.md#metadatatype)[]* =  [
  {
    constructor: Buffer,
    name: 'Buffer',
    prefix: 'nvim_buf_',
  },
  {
    constructor: Window,
    name: 'Window',
    prefix: 'nvim_win_',
  },
  {
    constructor: Tabpage,
    name: 'Tabpage',
    prefix: 'nvim_tabpage_',
  },
]

*Defined in [api/types.ts:20](https://github.com/neovim/node-client/blob/97a65c6/src/api/types.ts#L20)*

___

