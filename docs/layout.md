# Layout

### Index
- [`display`](#display)
- [`float`](#float)
- [`overflow`](#overflow)
- [`position`](#position)
- [`top-right-bottom-left`](#top-right-bottom-left)
- [`z-index`](#z-index)
- [`flex-items`](#flex-items)
- [Examples](#examples)

### Display
| Classname    | Property   |
|:-------------|:-----------|
| `.d-n` | `display: none;` |
| `.d-b` | `display: block;` |
| `.d-ib` | `isplay: inline-block;` |
| `.d-i` | `display: inline;` |
| `.d-tb` | `display: table;` |
| `.d-tbc` | `display: table-cell;` |

### Float
| Classname    | Property   |
|:-------------|:-----------|
|`.fl-n` | `float: none;` |
|`.fl-l` | `float: left;` |
|`.fl-r` | `float: right;` |

### Vertical align
| Classname    | Property   |
|:-------------|:-----------|
|`.va-m` | `vertical-align: middle;` |
|`.va-t` | `vertical-align: top;` |
|`.va-b` | `vertical-align: bottom;` |

### Overflow
| Classname    | Property   |
|:-------------|:-----------|
| `.ov-h` | `overflow: block;` |
| `.ov-a` | `overflow: auto;` |
| `.ov-s` | `overflow: scroll;` |
| `.ovX-h` | `overflow-x: hidden;` |
| `.ovX-s` | `overflow-x: scroll;` |
| `.ovX-a` | `overflow-x: auto;` |
| `.ovY-h` | `overflow-y: hidden;` |
| `.ovY-s` | `overflow-y: scroll;` |
| `.ovY-a` | `overflow-y: auto;` |

### Position
| Classname    | Property   |
|:-------------|:-----------|
| `.pos-s` | `position: static;` |
| `.pos-st` | `position: sticky;` |
| `.pos-r` | `position: relative;` |
| `.pos-a` | `position: absolute;` |
| `.pos-f` | `position: fixed;` |

### Top, right, bottom and left
| Classname    | Property   |
|:-------------|:-----------|
| `.t-[1-4]` |  top: `var(--gap-[1-4]);` |
| `.t-[0-30]` | by 5  top: 0~30 by 5; |
| `.t-[40-100]` | by 10 top: 40~100 by 10; |
| `.r-[1-4]` |  right: `var(--gap-[1-4]);` |
| `.r-[0-30]` | by 5  right: 0~30 by 5; |
| `.r-[40-100]` | by 10 right: 40~100 by 10; |
| `.b-[1-4]` |  bottom: `var(--gap-[1-4]);` |
| `.b-[0-30]` | by 5  bottom: 0~30 by 5; |
| `.b-[40-100]` | by 10 bottom: 40~100 by 10; |
| `.l-[1-4]` |  left: `var(--gap-[1-4]);` |
| `.l-[0-30]` | by 5  left: 0~30 by 5; |
| `.l-[40-100]` | by 10 left: 40~100 by 10; |

### z-index
| Classname    | Property   |
|:-------------|:-----------|
| `.z-[0-9]` | `z-index`: `0` ~ `9000` by `1000`; |

## Example
```html
<ul>
  <li class="d-ib">List</li>
  <li class="d-ib">Inline</li>
  <li class="d-ib">Here</li>
</ul>
```

```html
<div class="w-20 bg-black ov-s">...</div>
```

```html
<div class="pos-r">
  <div class="pos-a t-10 r-10"></div>
</div>
```

```html
<div class="pos-f w-100 t-0 l-0 bg-black">Fixed example</div>
```
