| Modifier(s)                            | Return Type                    | Generator                        | Overload                         | Implementation                        |
|----------------------------------------|--------------------------------|:--------------------------------:|:--------------------------------:|:-------------------------------------:|
| export | T extends "object" &#124; "script" &#124; "template" &#124; "a" &#124; "abbr" &#124; "address" &#124; "applet" &#124; "area" &#124; "article" &#124; "aside" &#124; "audio" &#124; "b" &#124; "base" &#124; "basefont" &#124; "bdi" &#124; "bdo" &#124; "blockquote" &#124; "body" &#124; "br" &#124; "button" &#124; "canvas" &#124; "caption" &#124; "cite" &#124; "code" &#124; "col" &#124; "colgroup" &#124; "data" &#124; "datalist" &#124; "dd" &#124; "del" &#124; "details" &#124; "dfn" &#124; "dialog" &#124; "dir" &#124; "div" &#124; "dl" &#124; "dt" &#124; "em" &#124; "embed" &#124; "fieldset" &#124; "figcaption" &#124; "figure" &#124; "font" &#124; "footer" &#124; "form" &#124; "frame" &#124; "frameset" &#124; "h1" &#124; "h2" &#124; "h3" &#124; "h4" &#124; "h5" &#124; "h6" &#124; "head" &#124; "header" &#124; "hgroup" &#124; "hr" &#124; "html" &#124; "i" &#124; "iframe" &#124; "img" &#124; "input" &#124; "ins" &#124; "kbd" &#124; "label" &#124; "legend" &#124; "li" &#124; "link" &#124; "main" &#124; "map" &#124; "mark" &#124; "marquee" &#124; "menu" &#124; "meta" &#124; "meter" &#124; "nav" &#124; "noscript" &#124; "ol" &#124; "optgroup" &#124; "option" &#124; "output" &#124; "p" &#124; "param" &#124; "picture" &#124; "pre" &#124; "progress" &#124; "q" &#124; "rp" &#124; "rt" &#124; "ruby" &#124; "s" &#124; "samp" &#124; "section" &#124; "select" &#124; "slot" &#124; "small" &#124; "source" &#124; "span" &#124; "strong" &#124; "style" &#124; "sub" &#124; "summary" &#124; "sup" &#124; "table" &#124; "tbody" &#124; "td" &#124; "textarea" &#124; "tfoot" &#124; "th" &#124; "thead" &#124; "time" &#124; "title" &#124; "tr" &#124; "track" &#124; "u" &#124; "ul" &#124; "var" &#124; "video" &#124; "wbr" ? HTMLElementTagNameMap[T] : HTMLElement | ✘ | ✘  | ✔ |

# &#10025; Type Parameter(s)

| Type | Constraint |
| ---- | ---------- |
| T    | string     |

| Type      | Constraint |
| --------- | ---------- |
| TChildren | H[]        |

&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; name**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| - | T | ✘  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; attrs**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| - | Record&lt;string, string &#124; number &#124; boolean &#124; string[] &#124; null &#124; undefined&gt; &#124; null | ✔  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Initializer**

```ts
null
```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; children**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| - | TChildren | ✔  | ✔ | ✘ |