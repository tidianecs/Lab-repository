# Lab 5 CSS Media Queries



### Exercise 1: Basic Responsive Typography
**Objective:** Create responsive font sizes for different screen sizes.

**Requirements:**
- Default font size: 16px for body text
- Tablets (768px and below): 14px
- Mobile (480px and below): 12px
- Apply to a paragraph with class `.responsive-text`

**Starter Code:**
```html
<p class="responsive-text">
  This text should change size based on screen width.
</p>
```

### Exercise 2: Hide/Show Elements
**Objective:** Control element visibility across different devices.

**Requirements:**
- Create a navigation menu with class `.desktop-nav`
- Create a mobile menu button with class `.mobile-menu-btn`
- Desktop (above 768px): Show desktop nav, hide mobile button
- Mobile (768px and below): Hide desktop nav, show mobile button

**Starter Code:**
```html
<nav class="desktop-nav">
  <a href="#">Home</a>
  <a href="#">About</a>
  <a href="#">Contact</a>
</nav>
<button class="mobile-menu-btn">☰ Menu</button>
```

### Exercise 3: Color Scheme Changes
**Objective:** Change background and text colors based on screen size.

**Requirements:**
- Create a box with class `.color-box`
- Desktop: Blue background (#3498db), white text
- Tablet (768px and below): Green background (#2ecc71), white text
- Mobile (480px and below): Orange background (#e67e22), white text

**Starter Code:**
```html
<div class="color-box">
  <p>Watch my colors change!</p>
</div>
```


### Exercise 4: Responsive Grid Layout
**Objective:** Create a responsive card grid that adapts to screen size.

**Requirements:**
- Default (Desktop): 4 cards per row
- Tablet (768px and below): 2 cards per row
- Mobile (480px and below): 1 card per row
- Use CSS Grid
- Add 20px gap between cards

**Starter Code:**
```html
<div class="card-grid">
  <div class="card">Card 1</div>
  <div class="card">Card 2</div>
  <div class="card">Card 3</div>
  <div class="card">Card 4</div>
  <div class="card">Card 5</div>
  <div class="card">Card 6</div>
  <div class="card">Card 7</div>
  <div class="card">Card 8</div>
</div>
```

### Exercise 6: Orientation-Based Layout
**Objective:** Create different layouts for portrait and landscape orientations.

**Requirements:**
- Create a container with two sections
- Portrait: Sections stack vertically
- Landscape: Sections side-by-side (50% width each)
- Use orientation media queries

**Starter Code:**
```html
<div class="orientation-container">
  <section class="section-1">Section 1</section>
  <section class="section-2">Section 2</section>
</div>
```
