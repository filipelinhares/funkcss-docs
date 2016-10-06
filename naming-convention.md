# Naming convention
Funkcss has a recommended naming convention. Following these conventions you can easily extend it with your own helpers.

### Class names composition

`.[breakpoint-][property][DIRECTION][-value | -length][:pseudo-class]`

Examples:
```html
<!-- text-align: center -->
<h1 class="ta-c">My title</h1>

<!-- color: red on hover -->
<button class="c-red:h">Cancel</button>

<!-- margin-top: 20px in a medium breakpoint -->
<footer class="md-mT-20"></footer>
```
#### `[breakpoint]`
Here you add the breakpoints. By default, funk has the funkcss-responsive module that applies these breakpoints to the helpers.

If you want to extend funk, here are some examples how you can add a breakpoint to your class name.

```css
@media (min-width: 40em) {
  .\40-ta-c {
    text-align: center;
  }
}

@custom-media --breakpoint-sm (min-width: 40em);

@media (--breakpoint-sm) {
  .sm-ta-c {
    text-align: center;
  }
}
```

#### `[property] and [-value]`

Emmet is a text editor plugin that helps you to write CSS faster.

It gives you css properties and values shortcuts as following:

**Emmet**  
`ai:c => align-items: center;`

**funkcss**  
`.ai-c => align-items: center;`

#### `[?DIRECTIONS]`

To keep consistency in the class names we set the direction of the propertie with a class suffix.

Keep it capitalized, and in the end you can use the direction cleared and highlighted.

| Suffix        | Description   |
| ------------- |:-------------:|
| .T |	Top |
| .L |	Left |
| .R |	Right |
| .B |	Bottom |
| .TL |	Top and left |
| .TR |	Top and right |
| .BL |	Bottom and left |
| .BR |	Bottom and right |
| .Y |	Y axis - Vertical |
| .X |	X axis - Horizontal |

_Examples:_
```css
.pT-20 { padding-top: 20px; }
.mB-10 { margin-bottom: 10px; }
.tootipL { /* tooltip code */ }
```

#### `[-length]`

Describe the length value of a property. You can use a numeric or a literal value:

```css
.w-100p { padding-top: 100%; }
.fz-larger { font-size: 1.5rem; }
```

You can use a scale like funkcss does.

#### `[?:pseudo-class]`

If you want to add pseudo classes to your helpers, just add a suffix identifier

```css
.bd-red\:f:focus { border-color: red; }
.cur-p\:h:hover { cursor: pointer; }
```
