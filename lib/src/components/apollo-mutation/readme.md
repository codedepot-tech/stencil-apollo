# apollo-mutation



<!-- Auto Generated Below -->


## Properties

| Property    | Attribute   | Description | Type                                                                               | Default     |
| ----------- | ----------- | ----------- | ---------------------------------------------------------------------------------- | ----------- |
| `client`    | --          |             | `ApolloClient<any>`                                                                | `undefined` |
| `mutation`  | --          |             | `DocumentNode`                                                                     | `undefined` |
| `options`   | --          |             | `MutationOptions<any, Record<string, any>, Record<string, any>, ApolloCache<any>>` | `undefined` |
| `renderer`  | --          |             | `(mutationFn: MutationFn<{}, Record<string, any>>) => Element \| Element[]`        | `undefined` |
| `variables` | `variables` |             | `any`                                                                              | `undefined` |


## Events

| Event   | Description | Type                                                                                                                                                                       |
| ------- | ----------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `ready` |             | `CustomEvent<(options: Partial<MutationOptions<any, any, Record<string, any>, ApolloCache<any>>>) => Promise<FetchResult<any, Record<string, any>, Record<string, any>>>>` |


## Dependencies

### Depends on

- context-consumer

### Graph
```mermaid
graph TD;
  apollo-mutation --> context-consumer
  style apollo-mutation fill:#f9f,stroke:#333,stroke-width:4px
```

----------------------------------------------

*Built with [StencilJS](https://stenciljs.com/)*
