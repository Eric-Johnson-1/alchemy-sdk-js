[alchemy-sdk](../README.md) / [Exports](../modules.md) / SimulateExecutionResponse

# Interface: SimulateExecutionResponse

Response object for the [TransactNamespace.simulateExecution](../classes/TransactNamespace.md#simulateexecution) method.

## Table of contents

### Properties

- [calls](SimulateExecutionResponse.md#calls)
- [logs](SimulateExecutionResponse.md#logs)

## Properties

### calls

• **calls**: [`SimulationCallTrace`](SimulationCallTrace.md)[]

An array of traces generated during simulation that represent the execution
of the transaction along with the decoded calls if available.

#### Defined in

[src/types/types.ts:1068](https://github.com/alchemyplatform/alchemy-sdk-js/blob/873c9882/src/types/types.ts#L1068)

___

### logs

• **logs**: [`SimulationDebugLog`](SimulationDebugLog.md)[]

An array of logs emitted during simulation along with the decoded logs if
available.

#### Defined in

[src/types/types.ts:1074](https://github.com/alchemyplatform/alchemy-sdk-js/blob/873c9882/src/types/types.ts#L1074)
