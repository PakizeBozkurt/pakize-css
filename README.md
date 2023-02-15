# Pakize Bozkurt
# HTML and CSS challenge

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

In this example, the container class defines the grid and sets the number of columns and rows, and the grid-gap property sets the space between grid cells. The other classes (item1, item2, etc.) define the placement of elements within the grid by specifying the starting and ending columns and rows for each item.

CSS Grid to create a responsive layout for a website:

.container {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  grid-gap: 20px;
}

header {
  grid-column: 1 / -1;
}

nav {
  grid-column: 1 / 2;
  grid-row: 2 / 3;
}

main {
  grid-column: 2 / -1;
  grid-row: 1 / 2;
}

aside {
  grid-column: 2 / 3;
  grid-row: 2 / 3;
}

footer {
  grid-column: 1 / -1;
  grid-row: 3 / 4;
}

In this example, the container class creates a grid with columns that have a minimum width of 300px and can grow to fill the available space. The header, nav, main, aside, and footer classes define the placement of elements within the grid and create a three-row, three-column layout with a header, navigation, main content, aside, and footer section.

The layout adjusts automatically as the screen size changes, so that on larger screens, the layout is divided into three columns, and on smaller screens, it stacks vertically to fit the available space.

