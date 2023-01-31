# pakize bozkurt
html and css challenge

CSS Grid is a two-dimensional layout system for the web that allows developers to create grid-based layouts using rows and columns. It allows you to arrange elements into rows and columns, and then control the size, position, and spacing of those elements.

You can use CSS Grid to create complex, responsive designs that adapt to different screen sizes and device types, without having to rely on JavaScript or other tools.

.container {
  display: grid;
  grid-template-columns: 1fr 1fr;
  grid-template-rows: auto auto;
  grid-gap: 20px;
}

.item1 {
  grid-column: 1 / 2;
  grid-row: 1 / 2;
}

.item2 {
  grid-column: 2 / 3;
  grid-row: 1 / 2;
}

.item3 {
  grid-column: 1 / 2;
  grid-row: 2 / 3;
}

.item4 {
  grid-column: 2 / 3;
  grid-row: 2 / 3;
}
