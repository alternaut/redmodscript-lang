# REDmodScript

VSCode syntax highlighting for [REDmod](https://www.cyberpunk.net/en/modding-support) `'.script'` files.

Hastily cobbled together from scratch; partially with ❤️. 

Makes browsing CDPR's source scripts *subjectively* more pleasant. Beyond that, use `redscript`.

> ⚠️ This project is **solely intended** to be used with the related `*.script` files from CDPR's [REDmod](https://www.cyberpunk.net/en/modding-support) modding tool! For syntax highlighting pertaining to the community-created [redscript](https://github.com/jac3km4/redscript) scripting language (`*.reds` files), please refer to [Redscript Syntax Highlighting](https://marketplace.visualstudio.com/items?itemName=jackhumbert.redscript-syntax-highlighting) on the Marketplace.


## Notable Coverage

Support for:
- **attributes** for `class/struct` members
  ![attributes preview](resources/attributes.png)

- **runtime defaults** for `class/struct` members
  ![runtime-defaults preview](resources/runtime-defaults.png)

- **type-**`cast overloads`
  ![type-cast-overloads preview](resources/type-cast-overloads.png)

- **operator** `overloads`
  ![operator-overload preview](resources/op-overloads.png)

- `NULL`*-type*; `m_*` member variable and *known-*`enum` member distinctions
  ![various coverage preview](resources/various_01.png)

- distinction between `CName`, `TweakDBID`, `ResRef` literals and generic `String`-literals
  ![literals preview](resources/literals.png)
  *(`CName` literal is single-quoted):*
  ![cname event preview](resources/events.png)

## Installation

Install directly from VSCode's Extension Manager or via the [Marketplace](https://marketplace.visualstudio.com/items?itemName=alternaut-dev.redmodscript-lang) page.

## Known Issues

**None.** However, it should be noted that this extension was only tested against VSCode's `Dark+ (default theme)`.

