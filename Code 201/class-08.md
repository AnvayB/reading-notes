# HTML Chapter 15: Layout
- `position:static` – normal flow of text
- `position:relative` – moves an element in relation to where it would have been normal flow
- `position:absolute` – the box is taken out of normal flow and no longer affects the position of other elements on the page
  - act like it is not there
- `position:fixed` – positions the element in relation to the browser window --> text stays inn the same place on the page (like a constant banner)
- `z-index` – control which element shows on top; stacking content
  - `z-index` of 10 > `z-index` of 5
- `float` – allows you to take an element in normal flow and palce it as far to the left or right of the containing element as possible
- `clear` – allows you to say that no element (within the same containing element) should touch the left or right hand sides of a box
  - left/right/both/none
- `<div>` elements are used as containing elements to group sections of a page together
- browsers display pages in normal flow unless relative/absolute/fixed positioning has been specified
- the `float` property moves content to the left or right of the page and can be used to create multi-column layouts
  - floated items require a defined width
- designers keep pages within 960-1000 px wide, and indicate what the site is about within the top 600 px
  - this demonstrates its relevance without the user having to scroll
- grids help create professional and flexible designs
- CSS frameworks provide rules for common tasks
- you can include multiple CSS files in one page
