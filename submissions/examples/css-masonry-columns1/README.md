
## Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Opera

## Customization

### Changing Column Count

Edit the media queries in `style.css`:

```css
.masonry {
  column-count: 1; /* Default */
}

@media (min-width: 640px) {
  .masonry { column-count: 2; }
}

@media (min-width: 1024px) {
  .masonry { column-count: 3; } /* Change this value */
}