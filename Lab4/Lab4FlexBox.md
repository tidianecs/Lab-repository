# Lab 4 Flexbox

## Exercise 1: Basic Flex Container

Create a flex container with three colored boxes arranged horizontally.

**Requirements:**
- Create a container with class `flex-container`
- Add three divs inside with class `box`
- Each box should have a different background color (red, blue, green)
- Boxes should be arranged in a row
- Each box should have padding of 20px and some text inside
 Write the CSS to make it a flex container with items in a row.

## Exercise 2: Center Everything

Create a flex container that centers a single item both horizontally and vertically.

**Requirements:**
- Container should be 400px tall and full width
- Use flexbox to center the item perfectly in the middle
- The item should contain text "I'm Centered!"

**Hint:** You'll need both `justify-content` and `align-items`.

## Exercise 3: Navigation Bar

Build a  navigation bar using flexbox.

**Requirements:**
- Create a navbar with a logo on the left and menu items on the right
- Logo should be on the left side
- Menu items (Home, About, Services, Contact) should be on the right side
- All items should be vertically centered
- Menu items should have equal spacing between them

**HTML Structure:**
```html
<nav class="navbar">
  <div class="logo">MyLogo</div>
  <ul class="menu">
    <li>Home</li>
    <li>About</li>
    <li>Services</li>
    <li>Contact</li>
  </ul>
</nav>
```

## Exercise 4: Card Layout

Create a card layout that wraps to new lines.

**Requirements:**
- Create a container with 6 cards
- Each card should have a minimum width of 200px
- Cards should wrap to new lines when space runs out
- There should be 15px gap between cards
- Cards should grow to fill available space
- Each card should have: a title, description, and button
