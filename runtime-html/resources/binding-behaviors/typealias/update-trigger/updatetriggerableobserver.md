| Modifier(s)                            | Type                     |
|----------------------------------------|--------------------------|
| export | UpdateTriggerableObserver |

# &#10025; Initializer

```ts
(
  (ValueAttributeObserver & Required<ValueAttributeObserver>) |
    (CheckedObserver & Required<CheckedObserver>) |
      (SelectValueObserver & Required<SelectValueObserver>)
        ) & {
          originalHandler?: IEventSubscriber;
        }
```