# &#10025; Summary

TargetedInstructionType enum values become the property names for the associated renderers when they are injected
into the `Renderer`.
Additional instruction types can be added as long as they are 2 characters long and do not clash with existing ones.
By convention, the instruction types for a particular runtime start with the same first letter, and the second letter
starts counting from letter `a`. The standard runtime instruction types all start with the letter `r`.

| Const                        |
|------------------------------|
| ✔ |

# &#10025; Member(s)

| Name                                      | Value         |
|-------------------------------------------|---------------|
| hydrateElement | ra |
| hydrateAttribute | rb |
| hydrateTemplateController | rc |
| hydrateLetElement | rd |
| setProperty | re |
| interpolation | rf |
| propertyBinding | rg |
| callBinding | rh |
| letBinding | ri |
| refBinding | rj |
| iteratorBinding | rk |