# Card

Just put something in it.

## Demos

```demo
basic.vue
size.vue
cover.vue
hoverable.vue
slots.vue
border.vue
segment.vue
closable.vue
no-title.vue
loading.vue
custom-style.vue
embedded.vue
```

## Card

### Card Props

| Name | Type | Default | Description | Version |
| --- | --- | --- | --- | --- |
| action | `() => VNodeChild` | `undefined` | Operating area content, must be a render function. | 2.38.2 |
| bordered | `boolean` | `true` | Whether to show the card border. |  |
| closable | `boolean` | `false` | Is it allowed to close. |  |
| content | `string \| (() => VNodeChild)` | `undefined` | Card content, can be a render function. | 2.38.2 |
| content-class | `string` | `undefined` | The class of the card content area. | 2.36.0 |
| content-style | `Object \| string` | `undefined` | The style of the card content area. |  |
| cover | `() => VNodeChild` | `undefined` | Cover content, must be a render function. | 2.38.2 |
| embedded | `boolean` | `false` | Use a darker background color to show the embedding effect (only for bright themes) |  |
| footer | `() => VNodeChild` | `undefined` | Footer content, must be a render function. | 2.38.2 |
| footer-class | `string` | `undefined` | The class of the bottom area of the card. | 2.36.0 |
| footer-style | `Object \| string` | `undefined` | The style of the bottom area of the card. |  |
| header-class | `string` | `undefined` | The class of the card head area. | 2.36.0 |
| header-style | `Object \| string` | `undefined` | The style of the card head area. |  |
| header-extra | `() => VNodeChild` | `undefined` | Header extra content, must be a render function. | 2.38.2 |
| header-extra-class | `string` | `undefined` | The class of the card head extra area. | 2.36.0 |
| header-extra-style | `Object \| string` | `undefined` | The style of the card head extra area. | 2.25.0 |
| hoverable | `boolean` | `false` | Whether to show shadow when hovering on the card. |  |
| segmented | `boolean \| { [part in 'content' \| 'footer' \| 'action']?: boolean \| 'soft' }` | `false` | Segment divider settings of the card. |  |
| size | `'small' \| 'medium' \| 'large' \| 'huge'` | `'medium'` | Card size. |  |
| tag | `string` | `'div'` | What tag need the card be rendered as. | 2.34.3 |
| title | `string \| (() => VNodeChild)` | `undefined` | Card title. | Render function since 2.38.2 |
| on-close | `() => void` | `undefined` | Callback function triggered upon closing the card. |  |

### Card Slots

| Name         | Parameters | Description             |
| ------------ | ---------- | ----------------------- |
| cover        | `()`       | Cover content.          |
| header       | `()`       | Header content.         |
| header-extra | `()`       | Header extra content.   |
| default      | `()`       | Card content.           |
| footer       | `()`       | Footer content.         |
| action       | `()`       | Operating area content. |
