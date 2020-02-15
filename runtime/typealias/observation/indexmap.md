# &#10025; Summary

An array of indices, where the index of an element represents the index to map FROM, and the numeric value of the element itself represents the index to map TO
The deletedItems property contains the items (in case of an array) or keys (in case of map or set) that have been deleted.

| Modifier(s)                            | Type                     |
|----------------------------------------|--------------------------|
| export | IndexMap |

# &#10025; Initializer

```ts
number[] & {
  deletedItems: number[];
  isIndexMap: true;
}
```