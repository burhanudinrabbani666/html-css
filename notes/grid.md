# Grid

```css
.container--1 {
  /* STARTER */
  font-family: sans-serif;
  background-color: #ddd;
  font-size: 40px;
  margin: 40px;

  /* CSS GRID */
  display: grid;
  grid-template-columns: 200px 200px 100px 100px;
  grid-template-rows: 300px 200px;
  gap: 10px;
  column-gap: 10px;
  row-gap: 60px;
}
```

## What is CSS Grid

- Css grid s a set CSS properties for building 2-dimensional layouts
- The main ides behind CSS Grid is that we devide a container element into rows and columns that can be filled with its child elements
- in two dimensional contexts, CSS grid allows us to write less nested html and easier to rid css
- css grid is not meant to replace flexbox! instead they work perfectly together. Need a 1D Layout? Use Flexbox. Nedd a 2D layout? Use grid.

### Using fr and repeat

```css
/* How Many columns: 4, what Size columns: 1fr */
grid-template-columns: repeat(4, 1fr);

/* How Many rows: 4, what Size rows: 1fr */
grid-template-rows: repeat(2, 1fr);
```

### algining the content

```css
/* Aliging tracks inside containers distribute empty space */

justify-content: center;
align-content: center;
```
