| Modifier(s)                            | Return Type                    | Generator                        | Overload                         | Implementation                        |
|----------------------------------------|--------------------------------|:--------------------------------:|:--------------------------------:|:-------------------------------------:|
| export | ModifyCodeResult | ✘ | ✘  | ✔ |

# &#10025; Summary

stringModuleWrap is to deal with pure css text module import in shadowDOM mode.
For webpack:
import d0 from '!!raw-loader!./foo.css';
For dumber/requirejs:
import d0 from 'text!./foo.css';
We cannot use
import d0 from './foo.css';
because most bundler by default will inject that css into HTML head.

&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; unit**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| - | [IFileUnit](/plugin-conventions/interface/options/ifileunit.md) | ✘  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; options**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| - | [IPreprocessOptions](/plugin-conventions/interface/options/ipreprocessoptions.md) | ✘  | ✘ | ✘ |