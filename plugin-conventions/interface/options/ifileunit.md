| Modifier(s)                            | Extends                                    |
|----------------------------------------|--------------------------------------------|
| export | - |

# &#10025; Property(ies)

&nbsp;&nbsp; **&#10148; path**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

The path is used in sourceMap.

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | string |

&nbsp;&nbsp; **&#10148; base**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

The base path that file path is related to. Used for checking existence of the pair html.
We separated file path and base because file path will be written into source map.

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | string &#124; undefined |

&nbsp;&nbsp; **&#10148; contents**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | string |

&nbsp;&nbsp; **&#10148; filePair**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

For foo.js or foo.ts, this is foo.html or foo.md or foo.haml or foo.pug
For foo.html (or other templates), this is foo.css or foo.scss or foo.sass or foo.less or foo.styl

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | string &#124; undefined |