# Borders

### Index
- [`border`](#general-border)
- [`border-style`](#border-style)
- [`border-width`](#border-width)
- [`border-radius`](#border-radius)
- [Examples](#examples)

#### Border
| Classname    | Property   |
|:-------------|:-----------|
| `.bd` | `border: 1px solid #ccc;` |
| `.bdT` | `border-top: 1px solid #ccc;` |
| `.bdR` | `border-right: 1px solid #ccc;` |
| `.bdB` | `border-bottom: 1px solid #ccc;` |
| `.bdL` | `border-left: 1px solid #ccc;` |

#### Border style
| Classname    | Property   |
|:-------------|:-----------|
| `.bds-s` | `border-style: solid;` |
| `.bds-dt` | `border-style: dotted;` |
| `.bds-ds` | `border-style: dashed;` |
| `.bds-db` | `border-style: double;` |
| `.bds-g` | `border-style: groove;` |
| `.bds-r` | `border-style: ridge;` |
| `.bds-i` | `border-style: inset;` |
| `.bds-o` | `border-style: outset;` |
| `.bds-n` | `border-style: none;` |

#### Border width
| Classname    | Property   |
|:-------------|:-----------|
| `.bdw-[1-5]` | `border-width: 1~5;` |
| `.bdwT-[1-5]` | `border-top-width: 1~5 solid #ccc;` |
| `.bdwR-[1-5]` | `border-right-width: 1~5 solid #ccc;` |
| `.bdwB-[1-5]` | `border-bottom-width: 1~5 solid #ccc;` |
| `.bdwL-[1-5]` | `border-left-width: 1~5 solid #ccc;` |

#### Border radius
| Classname    | Property   |
|:-------------|:-----------|
|`.bdrs-[1-4]` | `border-radius: 1~4;` |
|`.bdrsT-[1-4]` | `border-top-radius: 1~4` |
|`.bdrsR-[1-4]` | `border-right-radius: 1~4` |
|`.bdrsB-[1-4]` | `border-bottom-radius: 1~4` |
|`.bdrsL-[1-4]` | `border-left-radius: 1~4` |
|`.bdrs-50` | `border-radius: 50%;` |

### Examples
```html
<div class="bd p-2">.bd</div>
```

```html
<div class="bg-black bdrsT-5 p-1 c-white mB-10"><code>.bdrsT-5</code></div>
<div class="bg-black bdrsB-5 p-1 c-white mB-10"><code>.bdrsB-5</code></div>
<div class="bg-black bdrsL-5 p-1 c-white mB-10"><code>.bdrsL-5</code></div>
<div class="bg-black bdrsR-5 p-1 c-white"><code>.bdrsR-5</code></div>
```

```html
<div class="bd bd-red bds-d p-2">.bd</div>
```
