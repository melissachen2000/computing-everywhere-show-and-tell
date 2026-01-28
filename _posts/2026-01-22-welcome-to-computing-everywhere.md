---
title: "Welcome to Computing Everywhere!"
date: 2026-01-22
categories:
  - blog
tags:
  - Jekyll
  - update
---

Welcome to the Show and Tell workshop at Computing Everywhere 2026! We're so excited you are here

This template uses the [minimal mistakes](https://mmistakes.github.io/minimal-mistakes/) theme. It is a well-maintained theme with a lot of customization options. [Here](https://mmistakes.github.io/minimal-mistakes/docs/quick-start-guide/) is the full set of documentation for the theme. We've also pulled out some specific pages that you might find useful.
- [Examples of different layouts that you can try](https://mmistakes.github.io/minimal-mistakes/year-archive/)
  - If you find an example that you like, find the file with the corresponding name [here](https://github.com/mmistakes/minimal-mistakes/tree/gh-pages-3.1.6/_posts). Then, copy the contents of that file, then modify it.
  - We included templates for some post types that we think might be useful. Check them out in the `_posts` folder or make your own!

### Navigating these files:
- To change what links are included in the site's navbar, edit `_data/navigation.yml`
- To change the title, bio, footer, etc., edit `_config.yml`. 
  - You can also change the color theme of this site! Check out the options [here](https://github.com/mmistakes/minimal-mistakes/tree/master?tab=readme-ov-file#skins-color-variations). If you like one of these themes, change the line `minimal_mistakes_skin: default` (e.g., to `minimal_mistakes_skin: neon`)
- To make new posts (e.g., documentation showcasing a project), create a new file in `_posts`
  - The filename of this post needs to be `YYYY-MM-DD-name-of-your-post.md` and must include "frontmatter", like what you see on this page between the `---`s
- To make new pages (e.g., the about page, or something that organizes multiple projects into a layout), create a new file in `_pages`
  - There are some template pages in there, but you can add more text to those pages below the second `---` on each `.md` page


### Note:
- To be able to see the changes you are making to your site, run `bundle install`, then after that is done, `bundle exec jekyll serve`
  - When it first starts, there will be a lot of warnings. Don't worry about them, most have to do with changes to a package that helps to handle the CSS. (Most jekyll themes have this issue right now, but we chose minimal mistakes since it's likely that they'll fix this later on, before the warnings become errors).
  - It will automatically regenerate your page as you make edits to any of the files that end in `.md`
  - If you make changes to `_config.yml`, you will need to stop this process by pressing `control + c` while in the terminal, then running `bundle exec jekyll serve` again.
- If you have questions, please ask!!! 

### Tips:
- Don't like editing your files in VSCode? That's okay! Write and format your work in Google Docs. Go to Tools > Preferences > Enable Markdown. Then, select the content you want to copy over, use the "copy markdown" option (you can see it when you right click), and paste it into the corresponding markdown file in VSCode. 

### Guides:
- [Git cheat sheet](https://git-scm.com/cheat-sheet)
  - Most likely, you will only need to know: `git add`, `git commit -m "<YOUR MESSAGE HERE>"` and `git push` to save your changes and publish your site
  - We encourage you to make sure that your commit messages are descriptive! This helps you keep track of what changes you have made.
  - You can also use the VSCode Git interface. Some instructions can be found [here](https://code.visualstudio.com/docs/sourcecontrol/overview). 
- [Markdown cheat sheet](https://www.markdownguide.org/cheat-sheet/)
