# Poetry Portfolio

A minimalist, custom-coded web portfolio designed to showcase a collection of poetry. 

🌐 **Live Website:** [Paste your live github.io link here]

## About This Project
This is a static, single-page website built entirely with plain HTML, CSS, and vanilla JavaScript. It is hosted for free using GitHub Pages. The design features a full-screen parallax hero image, elegant typography, and smooth scroll-triggered fade-in animations to create a premium, distraction-free reading experience.

## How to Add a New Poem
To add new poetry to the site, open the `index.html` file, click the edit (pencil) icon, and paste the following block inside the `<div class="fancy-content">` section:

```html
<div class="poem-container hidden">
  <h2 class="poem-title">Poem Title Here</h2>
  <p class="poem-body">
    Line one goes here,<br>
    Line two goes here,<br>
    Line three goes here.
  </p>
</div>
