# Store

Tags used to keep values and data across invocations. `{perset}` and `{perget}` are analogs from v8.

```
{store.set;mykey;"This is a string"}
{store.get;mykey}  // "This is a string"
{store.delete;mykey}
```

## `{store.set;key;value}`

Adds an item to the store. `value` can be an object, array, string, number, etc. `key` will be coerced to a string.

## `{store.get;key}`

Gets an item from the store.

## `{store.delete;key}`

Deletes an item from the store.
