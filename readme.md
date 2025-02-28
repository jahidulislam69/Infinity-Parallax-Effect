# Infinite Scroll Effect with Parallax Animation

This project implements an infinite scroll effect using HTML, CSS, and JavaScript. It dynamically creates project sections and applies a smooth parallax animation to images as the user scrolls.

## Features
- Infinite scrolling with dynamically generated sections
- Parallax effect on images for a smooth animation
- Custom scroll handling with inertia-like movement
- Responsive design adjustments

## Technologies Used
- **HTML**: Structure of the webpage
- **CSS**: Styling and animations
- **JavaScript**: Scroll event handling, parallax effect, and dynamic content creation

## File Structure
```
project-folder/
│-- index.html
│-- styles.css
│-- script.js
│-- README.md
```

## How It Works
1. **Dynamic Project Sections**: JavaScript generates multiple project sections dynamically.
2. **Smooth Scrolling Effect**: The script listens for wheel or touch events to animate scrolling.
3. **Parallax Effect**: Images inside project sections move at different speeds to create depth.
4. **Event Handling**: Handles resize events to adjust elements dynamically.

## Installation & Usage
1. Clone or download the repository.
2. Open `index.html` in a browser.
3. Scroll using a mouse wheel or touch gestures to see the effect.

## Code Overview
### 1. HTML
Defines the structure for project sections:
```html
<div class="projects-container"></div>
```

### 2. CSS
Handles styling and parallax effects:
```css
.project {
  position: relative;
  overflow: hidden;
}
```

### 3. JavaScript
- Creates projects dynamically.
- Implements smooth scrolling.
- Adds a parallax effect to images.
```js
const createParallaxImage = (imageElement) => {
  let bounds = imageElement.getBoundingClientRect();
};
```

## Future Improvements
- Add smooth inertia scrolling for a more natural effect.
- Optimize performance for mobile devices.
- Enhance animations with GSAP or other libraries.

## Author
**Jahidul Islam Shouvo**

## License
This project is open-source and available under the MIT License.

