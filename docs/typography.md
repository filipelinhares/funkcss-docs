# Typography

### Index
- [`text-alignment`](#text-alignment)
- [`text-transform`](#text-transform)
- [`text-decoration`](#text-decoration)
- [`font-style`](#font-style)
- [`white-space`](#white-space)
- [`word-wrap`](#word-wrap)
- [`word-break`](#word-break)
- [`text-overflow`](#text-overflow)

### Text alignment
| Classname    | Property   |
|:-------------|:-----------|
| `.ta-c` | `text-align: center;` |
| `.ta-l` | `text-align: left;` |
| `.ta-r` | `text-align: right;` |

### Text transform
| Classname    | Property   |
|:-------------|:-----------|
| `.tt-n` | `text-transform: none;` |
| `.tt-u` | `text-transform: uppercase;` |
| `.tt-l` | `text-transform: lowercase;` |
| `.tt-c` | `text-transform: capitalize;` |

### Font style
| Classname    | Property   |
|:-------------|:-----------|
| `.fs-i` | `font-style: italic;` |
| `.fs-o` | `font-style: oblique;` |

### Text decoration
| Classname    | Property   |
|:-------------|:-----------|
| `.td-n` | `text-decoration: none;` |
| `.td-o` | `text-decoration: overline;` |
| `.td-lt` | `text-decoration: line-through;` |
| `.td-u` | `text-decoration: underline;` |

### Word wrap
| Classname    | Property   |
|:-------------|:-----------|
| `.wow-n` | `word-wrap: normal;` |
| `.wow-bw` | `word-wrap: break-word;` |

### White space
| Classname    | Property   |
|:-------------|:-----------|
| `.whs-nw` | `white-space: nowrap;` |
| `.whs-p` | `white-space: pre;` |
| `.whs-n` | `white-space: normal;` |

### Word break
| Classname    | Property   |
|:-------------|:-----------|
| `.wob-n` | ` word-break: normal;` |
| `.wob-ba` | `word-break: break-all;` |
| `.wob-k` | `word-break: keep-all;` |

### Text overflow
| Classname    | Property   |
|:-------------|:-----------|
| `.tov-e` | `text-overflow: ellipsis;` |

## Example
```html
<p class="ta-r"><code>I'm right</code></p>
<p class="ta-c"><code>I'm centered</code></p>
<p class="ta-l"><code>I'm left</code></p>
<p>
  <span class="tt-u"><code>uppercase</code></span>
  <span class="tt-l"><code>LOWERCASE</code></span>
  <span class="tt-c"><code>capitalized</code></span>
</p>
<p>
  <span class="fw-300"><code>uppercase</code></span>
  <span class="fw-600"><code>LOWERCASE</code></span>
  <span class="fw-700"><code>capitalized</code></span>
</p>
<p>
  <span class="fs-i"><code>Italic</code></span>
  <span class="fs-o"><code>Oblique</code></span>
</p>
<p>
  <span class="td-o"><code>Overline</code></span>
  <span class="td-lt"><code>Line through</code></span>
  <span class="td-u"><code>Underline</code></span>
</p>
<p class="c-black bg-yellow tov-e whs-nw ov-h">I'm a too loooooooooong text</p>
```

```html
<p class="w-10 fg-white bg-yellow wob-k">
  loremipsum
</p>
<p class="w-10 fg-white bg-yellow wob-ba">
  Loremsdass ipsum dolor sit amet.
</p>
```

```html
<p class="w-10 fg-white bg-red">
  loremipsum
</p>
<p class="w-10 fg-white bg-yellow wow-bw">
  loremipsum
</p>
```
