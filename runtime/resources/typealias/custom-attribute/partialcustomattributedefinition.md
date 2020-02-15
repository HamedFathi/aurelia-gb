| Modifier(s)                            | Type                     |
|----------------------------------------|--------------------------|
| export | PartialResourceDefinition&lt;{ readonly default[BindingMode](/runtime/enum/flags/bindingmode.md)?: BindingMode &#124; undefined; readonly isTemplateController?: boolean &#124; undefined; readonly bindables?: readonly string[] &#124; Record&lt;string, PartialBindableDefinition&gt; &#124; undefined; readonly strategy?: [BindingStrategy](/runtime/enum/flags/bindingstrategy.md) &#124; undefined; readonly hooks?: [HooksDefinition](/runtime/class/definitions/hooksdefinition.md) &#124; undefined; readonly noMultiBindings?: boolean &#124; undefined; }&gt; |

# &#10025; Initializer

```ts
PartialResourceDefinition<{
  readonly defaultBindingMode?: BindingMode;
  readonly isTemplateController?: boolean;
  readonly bindables?: Record<string, PartialBindableDefinition> | readonly string[];
    readonly strategy?: BindingStrategy;
    readonly hooks?: HooksDefinition;
    
    /**

* A config that can be used by template compliler to change attr value parsing mode
* `true` to always parse as a single value, mostly will be string in URL scenario
* Example:
* ```html
* <div goto="http://bla.bla.com">
  *```
* With `noMultiBinding: true`, user does not need to escape the `:` with `\`
* or use binding command to escape it.
*
* With `noMultiBinding: false (default)`, the above will be parsed as it's binding
* to a property name `http`, with value equal to literal string `//bla.bla.com`
*/
readonly noMultiBindings?: boolean;
}>
```