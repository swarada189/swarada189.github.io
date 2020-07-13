## Welcome to my first website!

### How this works
I have built this website using GitHub pages and jekyll(blog-aware static site generator)

GitHub pages provides free domain name and web-hosting service but you need to use username as domain name which is fair as it is free of cost anyway :)

Jekyll is the engine behind GitHub Pages, which you can use to host sites right from your GitHub repositories. It takes your content, renders Markdown and Liquid templates, and spits out a complete, static HTML pages ready to be served by web server. 

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Steps to build
1. Setup your local dev environment
   https://jekyllrb.com/docs/

2. Create a repo with name as your username

3. Create a new site with 'Minima' theme in the working folder
```
jekyll new .

#OR Create a new site in the working folder where other files (like a readme.md file) might exist

jekyll new . --force
```
4. Test your site with the Live Reload option
```
bundle exec jekyll serve --livereload
```
The above command runs the site locally; click on server address mentioned on CLI to view the site and changes appear as you save the files without having to re-run it.

5. Convert gem-based theme into a regular theme
   The default gem-based theme is basically a pointer to a theme. So at every render, jekyll uses this pointer to fetch the theme. However it has a downside of breaking your website if a theme update comes up. Hence I saved the theme locally so that jekyll overrides default pointer to use this regular theme.


Install the theme gem: $ gem install jekyll-theme-cayman-blog

Run $ gem env gemdir to know where the gem was installed

Open the folder shown in the output

Open the folder gems

Open the theme folder (e.g. jekyll-theme-cayman-blog-0.0.5)

Copy all the files into your newly created or existing blog folder

Leave empty theme your site's _config.yml:
### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Swarada Adavadkar
## Data Science Specialist
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/swarada189/swarada189.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
