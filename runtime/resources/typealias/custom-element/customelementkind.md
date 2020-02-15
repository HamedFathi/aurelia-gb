| Modifier(s)                            | Type                     |
|----------------------------------------|--------------------------|
| export | CustomElementKind |

# &#10025; Initializer

```ts
IResourceKind<CustomElementType, CustomElementDefinition> & {
  
  /**

* Returns the closest controller that is associated with either this node (if it is a custom element) or the first
* parent node (including containerless) that is a custom element.
*
* As long as the provided node was directly or indirectly created by Aurelia, this method is guaranteed to return a controller.
*
* @param node - The node relative to which to get the closest controller.
* @param searchParents - Also search the parent nodes (including containerless).
* @returns The closest controller relative to the provided node.
  */
  for<T extends INode = INode, C extends ICustomElementViewModel<T> = ICustomElementViewModel<T>>(node: T, searchParents: true): ICustomElementController<T, C>;
    
    /**

* Returns the controller that is associated with this node, if it is a custom element with the provided name.
*
* @param node - The node to retrieve the controller for, if it is a custom element with the provided name.
* @returns The controller associated with the provided node, if it is a custom element with the provided name, or otherwise `undefined`.
    */
    for<T extends INode = INode, C extends ICustomElementViewModel<T> = ICustomElementViewModel<T>>(node: T, name: string): ICustomElementController<T, C> | undefined;
      
      /**

* Returns the closest controller that is associated with either this node (if it is a custom element) or the first
* parent node (including containerless) that is a custom element with the provided name.
*
* @param node - The node relative to which to get the closest controller of a custom element with the provided name.
* @param searchParents - Also search the parent nodes (including containerless).
* @returns The closest controller of a custom element with the provided name, relative to the provided node, if one can be found, or otherwise `undefined`.
      */
      for<T extends INode = INode, C extends ICustomElementViewModel<T> = ICustomElementViewModel<T>>(node: T, name: string, searchParents: true): ICustomElementController<T, C> | undefined;
        
        /**

* Returns the controller that is associated with this node, if it is a custom element.
*
* @param node - The node to retrieve the controller for, if it is a custom element.
* @returns The controller associated with the provided node, if it is a custom element, or otherwise `undefined`.
        */
        for<T extends INode = INode, C extends ICustomElementViewModel<T> = ICustomElementViewModel<T>>(node: T): ICustomElementController<T, C> | undefined;
          isType<T>(value: T): value is (T extends Constructable ? CustomElementType<T> : never);
            define<T extends Constructable>(name: string, Type: T): CustomElementType<T>;
              define<T extends Constructable>(def: PartialCustomElementDefinition, Type: T): CustomElementType<T>;
                define<T extends Constructable = Constructable>(def: PartialCustomElementDefinition, Type?: null): CustomElementType<T>;
                  define<T extends Constructable>(nameOrDef: string | PartialCustomElementDefinition, Type: T): CustomElementType<T>;
                    getDefinition<T extends Constructable>(Type: T): CustomElementDefinition<T>;
                      annotate<K extends keyof PartialCustomElementDefinition>(Type: Constructable, prop: K, value: PartialCustomElementDefinition[K]): void;
                        getAnnotation<K extends keyof PartialCustomElementDefinition>(Type: Constructable, prop: K): PartialCustomElementDefinition[K];
                          generateName(): string;
                          createInjectable<T extends Key = Key>(): InjectableToken<T>;
                            generateType<P extends {} = {}>(
                              name: string,
                              proto?: P,
                            ): CustomElementType<Constructable<P>>;
                              }
```