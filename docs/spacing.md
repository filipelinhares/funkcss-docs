# Spacing

### Margin
| Classname    | Property   |
|:-------------|:-----------|
| `.m-` | `margin: sizes;` |
| `.mT-` | `margin-top: sizes;` |
| `.mR-` | `margin-right: sizes;` |
| `.mB-` | `margin-bottom: sizes;` |
| `.mL-` | `margin-left: sizes;` |
| `.mX-` | `margin-left: sizes; margin-right: sizes;` |
| `.mY-` | `marign-top: sizes; margin-bottom: sizes;` |

### Negative margin
Negative margin is useful when you're using gutter in a grid.

| Classname    | Property   |
|:-------------|:-----------|
| `.mX-[1-4]n` | `margin-left: -var(--gap-[1-4]); margin-right: -var(--gap-[1-4]);` |

### Padding
| Classname    | Property   |
|:-------------|:-----------|
| `.p-` | `padding: sizes; ` |
| `.pT-` | `padding-top: sizes; ` |
| `.pR-` | `padding-right: sizes; ` |
| `.pB-` | `padding-bottom: sizes; ` |
| `.pL-` | `padding-left: sizes; ` |
| `.pX-` | `padding-left: sizes; padding-right: sizes;` |
| `.pY-` | `padding-top: sizes; padding-bottom: sizes;` |


### Sizes
Padding and margin helpers follow these size patterns:

| Classname    | Property   |
|:-------------|:-----------|
| `.m-a` | `margin: auto;` |
| `.m-[1-4]` | `margin: var(--gap-[1-4]);` |
| `.m-[0-30]` | by `5` margin: `0~30` by `5`; |
| `.m-[40-100]` | by `10` margin: `40~100` by `10`; |
| `.p-a` | `padding: auto;` |
| `.p-[1-4]` | `padding: var(--gap-[1-4]);` |
| `.p-[0-30]` | by `5` padding: `0~30` by `5`; |
| `.p-[40-100]` | by `10` padding: `40~100` by `10`; |

## Examples
```html
<div class="pY-2 bd bd-silver">
  <div class="w-50 pY-2 bg-black mX-a"></div>
</div>
```

```html
<div class="p-2 c-white bg-black mL-80"><code>.mL-80</code></div>
```
