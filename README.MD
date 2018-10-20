# UX Drops
## A curated list of design resources
#### Built tools: Pug, SCSS, JS, and Jekyll


## How To Run

Type the command `bundle exec jekyll serve` or simply `jekyll serve`.


## Sass Tip

If you include a `_` in front of a filename (ex. `_navBar.sass`), Jekyll will not compile that file in your `_site` folder. As you can see normalize.css has an underscore before its filename, since it is not needed in the build, as it is already imported in the main sass file. I recommend prepending an underscore to all of your sass includes - but of course not your main sass file.

## Jekyll Plugins Used

- [**Jekyll-Pug by Doug Beney**](https://github.com/DougBeney/jekyll-pug) - This is what allows us to process Pug within Jekyll. Please read the [Github page](https://github.com/DougBeney/jekyll-pug) to understand all the ins-and-outs of this plugin.
- [**Jekyll-Livereload by Robert DeRose**](https://github.com/RobertDeRose/jekyll-livereload) - Allows browser livereload when running a jekyll server.