# my-website

This is my first website hosted on GitHub Pages. ✨

Check it out at: https://ghuser01.github.io/my-website/

Theme and layout using modified jekyll-theme-cayman.
https://pages-themes.github.io/cayman/

Deployed with github-pages gem not GitHub Actions.

default.html has imported cayman layout edited to add the following:
- portfolio grid
- navigation buttons: class="back-to-top"; class="top-nav"
- some cayman liquid content commented out ({% comment %} // {% endcomment %})

style.scss contains overrides to cayman style
- if in _sass/_variables.scss, edits come before style import
- most override located after import

index.md is home page by default
- currently in markdown, consider changing to html
- starts with YAML configuration
- contains html content for page

services.html is second page (linked to on home page)
- starts with YAML configuration
