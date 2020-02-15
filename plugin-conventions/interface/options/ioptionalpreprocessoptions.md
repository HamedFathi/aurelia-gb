| Modifier(s)                            | Extends                                    |
|----------------------------------------|--------------------------------------------|
| export | - |

# &#10025; Property(ies)

&nbsp;&nbsp; **&#10148; defaultShadowOptions**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | { mode: "open" &#124; "closed"; } &#124; undefined |

&nbsp;&nbsp; **&#10148; stringModuleWrap**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

More details in ./preprocess-html-template.ts

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | ((id: string) =&gt; string) &#124; undefined |

&nbsp;&nbsp; **&#10148; cssExtensions**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

.css, .scss, .sass, .less, .styl

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | string[] &#124; undefined |

&nbsp;&nbsp; **&#10148; jsExtensions**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

.js, .jsx, .ts, .tsx, .coffee

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | string[] &#124; undefined |

&nbsp;&nbsp; **&#10148; templateExtensions**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

.html, .md, .pug, .haml, .jade, .slim, .slm

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | string[] &#124; undefined |

&nbsp;&nbsp; **&#10148; useProcessedFilePairFilename**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

When foo.js is paired by foo.md,
when foo.md is paried by foo.scss,
most bundlers require import original filename foo.md and foo.scss
instead of foo.html and foo.css.
But some bundlers (dumber) require import processed filename foo.html
and foo.css.

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | boolean &#124; undefined |

&nbsp;&nbsp; **&#10148; useCSSModule**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

Whenn CSSModule is in use, stringModuleWrap is ignored.

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | boolean &#124; undefined |