# Lists

- `<ol></ol>`: used to create ordered lists
- `<li></li>`: wrap these around each item in a list
- `<ul></ul>`: used to create unordered lists
- You can create a sub list by inserting `<li></li>` inside of a list that already exists

# Boxes

- To set your own dimensions for a box use *height* and *width* properties
- Specify the size of a box using pixels(px), percentages(100%), or ems(0.5em)
- When using %, the size is relative to the size of the browser window or the box it is inside of
- When you use ems, the size of the box is based on the size of text within it

## Limiting Width ##

- *min-width*: used to specify the smallest size a box can be displayed when the browser window is narrow
- *max-width*: used to specify the maximum width a box can stretch to when the browser window is wide

## Limiting Height ##

- *min-height* & *max-height*: used to limit the height and width of a box on a page

## Overflowing Content ##

- The overflow property tells the browser what to do if the content contained within a box is larger than the box itself
- The overflow property can have these values: *hidden* or *scroll*
- *hidden*: simply hides any extra content
- *scroll*: adds a scrollbar to the box so that users can scroll to see missing content
