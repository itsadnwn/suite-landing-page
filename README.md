# 📚 Frontend Mentor Challenge - Suite Landing Page

<p>A responsive page for <a href="https://www.frontendmentor.io/challenges/suite-landing-page-tj_eaU-Ra" target="_blank">[Suite Landing Page on Frontend Mentor]</a>.</p>

<figure>
  <img src="/resources/images/screenshot.png">
</figure>

# 🔗 Links

<ul>
  <li><strong>Solution URL:</strong> <a href="https://github.com/itsadnwn/suite-landing-page/" target="_blank">github.com/itsadnwn/suite-landing-page</a></li>
  <li><strong>Live Site URL:</strong> <a href="https://itsadnwn-suite-landing-page.vercel.app/" target="_blank">itsadnwn-suite-landing-page.vercel.app</a></li>
</ul>

# 🛠️ Technologies Used

<p>This project was built with:</p>
<ul>
  <li>HTML5</li>
  <li>CSS3</li>
  <li>Flexbox</li>
  <li>Media Queries for responsive design</li>
</ul>

# 🎯 What I learned & Practiced

<div>
  <h3>⭐ Logical Properties</h3>
  <p>Instead of always using <code>width</code> and <code>height</code>, I tried experimenting with logical properties. I've learned that this matters because if I'm building something that might be translated to Arabic or Japanese, using logical properties would mean I wouldn't need to rewrite all my CSS as the browser figures it out automatically.</p>
  <p>This project isn't one that might be translated to Arabic or Japanese, but I figured it's a good time to start getting used to logical properties. I'd just started learning about them so there are only a few that are logical properties. But here are some main ones I read up and should remember:</p>
  <ul>
    <li><code>inline-size</code>: usually means width, but adapts to writing direction</li>
    <li><code>block-size</code>: usually means height</li>
    <li><code>margin-inline-start</code>: left margin in English, but right margin in Arabic</li>
    <li><code>margin-block-start</code>: top margin</li>
  </ul>
</div>

<div>
  <h3>⭐ Negative Margins + Z-Index for Overlapping</h3>
  <p>I made elements overlap without using by using negative margins, then control which one shows on top with <code>z-index</code>. It helped with overlapping layouts without complex positioning, but I understand that negative margins can break layouts if I'm not careful (which, in this case, it did break while I was doing it) so I would appreciate any help and feedback on better solutions!</p>

# ✨ Key Features

<ul>
  <li><strong>Fully Responsive Design:</strong> Optimized layout that adapts to different screen sizes</li>
  <li><strong>Modern CSS Techniques:</strong> Built using CSS Flexbox for robust layout control</li>
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