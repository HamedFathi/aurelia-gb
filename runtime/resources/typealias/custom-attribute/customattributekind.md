| Modifier(s)                            | Type                     |
|----------------------------------------|--------------------------|
| export | CustomAttributeKind |

# &#10025; Initializer

```ts
IResourceKind<CustomAttributeType, CustomAttributeDefinition> & {
  for<T extends INode = INode, C extends ICustomAttributeViewModel<T> = ICustomAttributeViewModel<T>>(node: T, name: string): ICustomAttributeController<T, C> | undefined;
    isType<T>(value: T): value is (T extends Constructable ? CustomAttributeType<T> : never);
      define<T extends Constructable>(name: string, Type: T): CustomAttributeType<T>;
        define<T extends Constructable>(def: PartialCustomAttributeDefinition, Type: T): CustomAttributeType<T>;
          define<T extends Constructable>(nameOrDef: string | PartialCustomAttributeDefinition, Type: T): CustomAttributeType<T>;
            getDefinition<T extends Constructable>(Type: T): CustomAttributeDefinition<T>;
              annotate<K extends keyof PartialCustomAttributeDefinition>(Type: Constructable, prop: K, value: PartialCustomAttributeDefinition[K]): void;
                getAnnotation<K extends keyof PartialCustomAttributeDefinition>(Type: Constructable, prop: K): PartialCustomAttributeDefinition[K];
                  }
```