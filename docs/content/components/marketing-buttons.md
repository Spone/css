---
title: Marketing buttons
path: components/marketing-buttons
status: New
source: 'https://github.com/primer/css/tree/main/src/marketing/buttons'
bundle: marketing-buttons
---

Marketing buttons come in different colors and sizes, and are also available in a blue outlined version.

## Colors, outlined and transparent

Marketing buttons can be solid blue, outlined blue, solid green, or transparent.

The solid blue and solid green buttons have more visual emphasis than the blue outlined button, therefore they should be used sparingly and only for call to actions that need emphasis.

```html live
<button class="btn-mktg mr-3" type="button">Learn more</button>
<button class="btn-mktg btn-primary-mktg mr-3" type="button">Sign up</button>
<button class="btn-mktg btn-outline-mktg mr-3" type="button">Learn more</button>
<div class="mt-3 p-3" style="background-color: var(--color-scale-gray-9);">
  <button class="btn-mktg btn-transparent" type="button">Learn more</button>
</div>
```

## Sizes

Available in two sizes, marketing buttons have a default size and a large size.

```html live
<button class="btn-mktg mr-2" type="button">Learn more</button>
<button class="btn-mktg btn-primary-mktg mr-2" type="button">Sign up</button>
<button class="btn-mktg btn-outline-mktg mr-2" type="button">Learn more</button>
<hr>
<button class="btn-mktg btn-large-mktg mr-2" type="button">Learn more</button>
<button class="btn-mktg btn-primary-mktg btn-large-mktg mr-2" type="button">Sign up</button>
<button class="btn-mktg btn-outline-mktg btn-large-mktg mr-2" type="button">Learn more</button>
```
