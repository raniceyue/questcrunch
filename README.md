# Contributing

This portfolio uses the ruby static site generator, Jekyll. 
The theme being used is [minimal mistakes](https://mmistakes.github.io/minimal-mistakes/docs/quick-start-guide/).

Please ensure you have fulfilled the following prerequisites: 
- Ensure you have Git installed on your computer
- [Install the latest stable version of Ruby](https://www.ruby-lang.org/en/documentation/installation/)
- [Install Jekyll](https://jekyllrb.com/docs/installation/) and the prerequisites specified on their installation page

To begin working on the portfolio... 
1. Fork and clone this repository into your computer
2. Ensure that you are on the branch `gh-pages`
3. Navigate to the root folder of this repository on your computer
4. Enter the command `bundle` in your terminal to fetch and update gems

Now you can begin editing the contents of the website! To see a live hot-reloaded preview of the site, enter the following command in your terminal, 
and leave your terminal running.
```
jekyll serve --livereload
```
Now a preview of the website can be viewed on `localhost:4000/questcrunch`

Once you have finished making changes to the website, commit and push to your clone of the repository, and make a pull-request. 

## For Your Info
- `index.md` contains the home page of
- All images used on the site are stored in `/assets/images`
- To create a page on the site, create a `.md` file in `_pages`
- To edit the navigation links on the navigation bar, go to `_data/navigation.yml`
- For more info, please read the Jekyll documentation and the documentation for the theme (provided in the references below)

## Featuring this portfolio on your Github domain
After forking the repository, 
1. Go to the forked repository's settings and go to the *Github Pages* section
2. Select source branch of the page to be `gh-pages` at root
3. Save settings and the portfolio is now viewable on your domain at `<YOUR_GITHUB_USERNAME>.github.io/questcrunch`!

### References
- [Jekyll Documentation]()
- [Minimal Mistakes Theme Documentation](https://mmistakes.github.io/minimal-mistakes/docs/quick-start-guide/)

