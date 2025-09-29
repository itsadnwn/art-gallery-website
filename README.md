# 📚 Frontend Mentor Challenge - Bento Grid

<p>A responsive page for <a href="https://www.frontendmentor.io/challenges/art-gallery-website-yVdrZlxyA" target="_blank">[Art Gallery Website on Frontend Mentor]</a>. This 2-page art gallery project contains some particularly interesting layouts.</p>

<figure>
  <img src="/resources/assets/screenshot.png">
</figure>

# 🔗 Links

<ul>
  <li><strong>Solution URL:</strong> <a href="https://github.com/itsadnwn/art-gallery-website/" target="_blank">github.com/itsadnwn/art-gallery-website</a></li>
  <li><strong>Live Site URL:</strong> <a href="https://itsadnwn-art-gallery-website.vercel.app/" target="_blank">itsadnwn-art-gallery-website.vercel.app</a></li>
</ul>

# 🛠️ Technologies Used

<p>This project was built with:</p>
<ul>
  <li>HTML5</li>
  <li>CSS3</li>
  <li>Flexbox</li>
  <li>CSS Grid</li>
  <li>Media Queries for responsive design</li>
</ul>

# 🎯 What I learned & Practiced

<div>
  <h3>⭐ CSS Grid</h3>
  <p>I worked more with CSS Grid layouts to structure my page sections. Used <code>grid-template-columns</code> and <code>grid-template-rows</code> to create responsive layouts that adapt across different screen sizes.</p>
  <p>I also used <code>grid-template-areas</code> to organize the layouts, which made it easier to understand the layout structure at a glance</p>
</div>

<div>
  <h3>⭐ Flexbox</h3>
  <p>I continued practicing Flexbox for component-level layouts, especially for buttons and navigation elements. I used <code>flex-direction</code>, <code>align-items</code>, <code>justify-content</code> and <code>gap</code> to control spacing and alignment.</p>
</div>

<div>
  <h3>⭐ CSS Mask Properties</h3>
  <p>I discovered a new technique for changing SVG colors without using inline SVG or filters. The mask properties let me use external SVG files as masks and control their color through <code>background-color</code>.</p>
  <p><strong>Key Properties:</strong></p>
  <ul>
    <li><code>mask-image</code>: Sets the SVG file as a mask</li>
    <li><code>mask-size</code>: Controls how the mask scales</li>
    <li><code>mask-repeat</code>: Prevents the mask from repeating</li>
    <li><code>mask-position</code>: Centers or positions the mask</li>
  </ul>
  <p>This approach is cleaner than using CSS filters and allows for precise color control. Perfect for icon systems where colors are needed to be changed on hover or for different themes.</p>
</div>

<div>
  <h3>⭐ Other Key Learning Points</h3>
  <ul>
    <li>Found out that <code>outline</code> doesn't work on elements with mask properties, and I had to apply the outline to a parent wrapper element instead</li>
    <li>Discovered that <code>display: block;</code> on images prevents unwanted white space below them</li>
  </ul>
</div>

# ✨ Key Features

<ul>
  <li><strong>Fully Responsive Design:</strong> Optimized layout that adapts to different screen sizes</li>
  <li><strong>Modern CSS Techniques:</strong> Built using CSS Grid and Flexbox for robust layout control</li>
</ul>

# 📁 File Structure

<ul>
  <li><strong>index.html</strong>: Main HTML markup and content structure</li>
  <li><strong>styles.css</strong>: CSS styling with responsive design and interactive effects</li>
  <li><strong>resources</strong>: Images and other assets</li>
</ul>

# 🔧 Development Notes

<ul>
  <li>Built with semantic HTML5 for accessibility</li>
  <li>CSS organized with custom properties for maintainability</li>
  <li>Mobile-first approach ensures optimal performance on all devices</li>
  <li>Tested across multiple browsers and device sizes</li>
</ul>