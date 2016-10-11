# Flex

### Index
- [`display`](#display)
- [`flex-wrap`](#flex-wrap)
- [`flex-direction`](#flex-direction)
- [`align-items`](#align-items)
- [`align-self`](#align-self)
- [`justify-content`](#justify-content)
- [`flex-items`](#flex-items)
- [Examples](#examples)

#### Display
| Classname    | Property   |
|:-------------|:-----------|
| `.d-f` | `display: flex;` |
| `.d-if` | `display: inline-flex;` |

#### Flex wrap
| Classname    | Property   |
|:-------------|:-----------|
| `.fxw-w` | `flex-wrap: wrap;` |
| `.fxw-wr` | `flex-wrap: wrap-reverse;` |
| `.fxw-nw` | `flex-wrap: nowrap;` |

#### Flex direction
| Classname    | Property   |
|:-------------|:-----------|
|`.fxd-c` | `flex-direction: column;` |
|`.fxd-cr` | `flex-direction: column-reverse;` |
|`.fxd-r` | `flex-direction: row;` |
|`.fxd-rr` | `flex-direction: row-reverse;` |

#### Align items
| Classname    | Property   |
|:-------------|:-----------|
| `.ai-c` | `align-items: center;` |
| `.ai-fs` | `align-items: flex-start;` |
| `.ai-fe` | `align-items: flex-end;` |
| `.ai-s` | `align-items: stretch;` |
| `.ai-b` | `align-items: baseline;` |

#### Align self
| Classname    | Property   |
|:-------------|:-----------|
| `.as-c` | `align-self: center;` |
| `.as-fs` | `align-self: flex-start;` |
| `.as-fe` | `align-self: flex-end;` |
| `.as-s` | `align-self: stretch;` |
| `.as-b` | `align-self: baseline;` |

#### Justify content
| Classname    | Property   |
|:-------------|:-----------|
| `.jc-c` | `justify-content: center;` |
| `.jc-fe` | `justify-content: flex-end;` |
| `.jc-fs` | `justify-content: flex-start;` |
| `.jc-sb` | `justify-content: space-between;` |
| `.jc-sa` | `justify-content: space-around;` |

### Flex items
| Classname    | Property   |
|:-------------|:-----------|
| `.fx-n` | `flex: none;` |
| `.fx-1` | `flex: 1;` |
| `.fxb-auto` | `flex-basis: auto;` |
| `.fxg-1` | `flex-grow: 1;` |
| `.fxs-1` | `flex-shrink: 1;` |
| `.ord-[1-10]` | `order: 1~10;` |

## Example
**Media object**
```html
<div class="d-f ai-s">
  <img class="mR-1" src="https://placeimg.com/100/100/any" width="100" height="100" alt="...">
  <p class="fx-1">...</p>
</div>
```
```
