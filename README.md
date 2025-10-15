# 📚 Frontend Mentor Challenge - Art Gallery Website

A responsive page for [Art Gallery Website on Frontend Mentor](https://www.frontendmentor.io/challenges/art-gallery-website-yVdrZlxyA). This 2-page art gallery project contains some particularly interesting layouts.

!(resources/assets/screenshot.png)

# 🔗 Links

+ **Solution URL:** [github.com/itsadnwn/art-gallery-website](https://github.com/itsadnwn/art-gallery-website/)
+ **Live Site URL:** [itsadnwn-art-gallery-website.vercel.app](https://itsadnwn-art-gallery-website.vercel.app/)

# 🛠️ Technologies Used

This project was built with:
+ HTML5
+ CSS3
+ Flexbox
+ CSS Grid
+ Media Queries for responsive design

# 🎯 What I learned & Practiced

### ⭐ CSS Grid
I worked more with CSS Grid layouts to structure my page sections. Used `grid-template-columns` and `grid-template-rows` to create responsive layouts that adapt across different screen sizes.
I also used `grid-template-areas` to organize the layouts, which made it easier to understand the layout structure at a glance.

### ⭐ Flexbox
I continued practicing Flexbox for component-level layouts, especially for buttons and navigation elements. I used `flex-direction`, `align-items`, `justify-content` and `gap` to control spacing and alignment.

### ⭐ Positioning Elements
I practiced using `position: relative` and `position: absolute` to rearrange and layer elements on the page. This was helpful for overlapping elements and creating complex layouts where the elements need to break out of the normal document flow.

### ⭐ CSS Mask Properties
I discovered a new technique for changing SVG colors without using inline SVG or filters. The mask properties let me use external SVG files as masks and control their color through `background-color`.

**Key Properties:**
+ `mask-image`: Sets the SVG file as a mask
+ `mask-size`: Controls how the mask scales
+ `mask-repeat`: Prevents the mask from repeating
+ `mask-position`: Centers or positions the mask

This approach is cleaner than using CSS filters and allows for precise color control. Perfect for icon systems where colors are needed to be changed on hover or for different themes.

### ⭐ Mix Blend Mode
I learned how to use `mix-blend-mode` to create text that automatically inverts its color based on the background. I used `mix-blend-mode: difference` to make the hero's header appear white on dark background, and black on light background.
This was very useful for creating that split-color effect where text spans across different colored sections without needing separate elements or complex position.

### ⭐ Other Key Learning Points
+ Found out that `outline` doesn't work on elements with mask properties, and I had to apply the outline to a parent wrapper element instead
+ Discovered that `display: block;` on images prevents unwanted white space below them

# ✨ Key Features

+ **Fully Responsive Design:** Optimized layout that adapts to different screen sizes
+ **Modern CSS Techniques:** Built using CSS Grid and Flexbox for robust layout control

# 📁 File Structure

+ **index.html**: Main HTML markup and content structure
+ **location.html**: HTML markup and content structure for Location page
+ **styles.css**: CSS styling with responsive design and interactive effects
+ **resources**: Images and other assets

# 🔧 Development Notes

+ Built with semantic HTML5 for accessibility
+ CSS organized with custom properties and maintainability 
+ Mobile-first approach ensures optimal performance on all devices
+ Tested across multiple browsers and device sizes
