# Objects

### Index
- [`display`](#display)
- [`background-size`](#background-size)
- [`background-repeat`](#background-repeat)
- [`background-position`](#background-position)
- [`object-fit`](#object-fit)
- [`resize`](#resize)
- [Examples](#examples)

### Background size
| Classname    | Property   |
|:-------------|:-----------|
| `.bgs-cv` | `background-size: cover;` |
| `.bgs-ct` | `background-size: contain;` |
| `.bgs-full` | `background-size: 100% 100%;` |

### Background repeat
| Classname    | Property   |
|:-------------|:-----------|
| `.bgr-n` | `background-repeat: no-repeat;` |
| `.bgr-x` | `background-repeat: repeat-x;` |
| `.bgr-y` | `background-repeat: repeat-y;` |

### Background position
| Classname    | Property   |
|:-------------|:-----------|
| `.bgpY-c` | `background-position-y: center;` |
| `.bgpY-t` | `background-position-y: top;` |
| `.bgpY-r` | `background-position-y: right;` |
| `.bgpY-b` | `background-position-y: bottom;` |
| `.bgpY-l` | `background-position-y: left;` |
| `.bgpX-c` | `background-position-x: center;` |
| `.bgpX-t` | `background-position-x: top;` |
| `.bgpX-r` | `background-position-x: right;` |
| `.bgpX-b` | `background-position-x: bottom;` |
| `.bgpX-l` | `background-position-x: left;` |

### Object fit
| Classname    | Property   |
|:-------------|:-----------|
| `.of-ct` | `object-fit: contain;` |
| `.of-cv` | `object-fit: cover;` |
| `.of-f` | `object-fit: fill;` |
| `.of-n` | `object-fit: none;` |
| `.of-sd` | `object-fit: scale-down;` |

### Resize
| Classname    | Property   |
|:-------------|:-----------|
| `.rsz-v` | `resize: vertical;` |
| `.rsz-h` | `resize: horizontal;` |

## Example
```html
<div class="container">
  <div class="h-300 bgs-cv" style="background-image: url('https://placeimg.com/1024/860/any');"></div>
</div>
```

```html
<div class="container">
  <div class="h-300 bgr-y" style="background-image: url('https://placeimg.com/50/50/any');"></div>
</div>
```

```html
<div class="container">
  <div class="h-300 bgp-b bgr-n" style="background-image: url('https://placeimg.com/200/200/any');"></div>
</div>
```

**Object fit**
```html
<img class="of-cv" width="200" height="200" width="200" src="..." alt="...">
<img class="of-ct" width="200" height="200" width="200" src="..." alt="...">
<img class="of-f" width="200" height="200" width="200" src="..." alt="...">
```

**Resize**
```html
<textarea class="rsz-h"></textarea>
<textarea class="rsz-v"></textarea>
```
