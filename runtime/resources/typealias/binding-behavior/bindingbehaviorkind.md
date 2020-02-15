| Modifier(s)                            | Type                     |
|----------------------------------------|--------------------------|
| export | BindingBehaviorKind |

# &#10025; Initializer

```ts
IResourceKind<BindingBehaviorType, BindingBehaviorDefinition> & {
  isType<T>(value: T): value is (T extends Constructable ? BindingBehaviorType<T> : never);
    define<T extends Constructable>(name: string, Type: T): BindingBehaviorType<T>;
      define<T extends Constructable>(def: PartialBindingBehaviorDefinition, Type: T): BindingBehaviorType<T>;
        define<T extends Constructable>(nameOrDef: string | PartialBindingBehaviorDefinition, Type: T): BindingBehaviorType<T>;
          getDefinition<T extends Constructable>(Type: T): BindingBehaviorDefinition<T>;
            annotate<K extends keyof PartialBindingBehaviorDefinition>(Type: Constructable, prop: K, value: PartialBindingBehaviorDefinition[K]): void;
              getAnnotation<K extends keyof PartialBindingBehaviorDefinition>(Type: Constructable, prop: K): PartialBindingBehaviorDefinition[K];
                }
```