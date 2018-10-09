

# Type aliases

<a id="ilogger"></a>

##  ILogger

**Ƭ ILogger**: *`LoggerInstance`*

*Defined in [utils/logger.ts:25](https://github.com/neovim/node-client/blob/97a65c6/src/utils/logger.ts#L25)*

___

# Variables

<a id="level"></a>

## `<Const>` level

**● level**: *`string`* =  process.env.NVIM_NODE_LOG_LEVEL || 'debug'

*Defined in [utils/logger.ts:4](https://github.com/neovim/node-client/blob/97a65c6/src/utils/logger.ts#L4)*

___
<a id="logger"></a>

## `<Const>` logger

**● logger**: *`LoggerInstance`* =  new winston.Logger({
  level,
  transports,
})

*Defined in [utils/logger.ts:20](https://github.com/neovim/node-client/blob/97a65c6/src/utils/logger.ts#L20)*

___
<a id="transports"></a>

## `<Const>` transports

**● transports**: *`any`[]* =  []

*Defined in [utils/logger.ts:3](https://github.com/neovim/node-client/blob/97a65c6/src/utils/logger.ts#L3)*

___

