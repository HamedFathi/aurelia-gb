| Modifier(s)                            | Type                     |
|----------------------------------------|--------------------------|
| export | ValueConverterKind |

# &#10025; Initializer

```ts
IResourceKind<ValueConverterType, ValueConverterDefinition> & {
  isType<T>(value: T): value is (T extends Constructable ? ValueConverterType<T> : never);
    define<T extends Constructable>(name: string, Type: T): ValueConverterType<T>;
      define<T extends Constructable>(def: PartialValueConverterDefinition, Type: T): ValueConverterType<T>;
        define<T extends Constructable>(nameOrDef: string | PartialValueConverterDefinition, Type: T): ValueConverterType<T>;
          getDefinition<T extends Constructable>(Type: T): ValueConverterDefinition<T>;
            annotate<K extends keyof PartialValueConverterDefinition>(Type: Constructable, prop: K, value: PartialValueConverterDefinition[K]): void;
              getAnnotation<K extends keyof PartialValueConverterDefinition>(Type: Constructable, prop: K): PartialValueConverterDefinition[K];
                }
```