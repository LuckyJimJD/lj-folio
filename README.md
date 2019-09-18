# CourseTheme

## A [Jekyll](https://jekyllrb.com/) theme for academic course sites. 

[![demo](https://img.shields.io/badge/theme-demo-brightgreen.svg)](https://LuckyJimJD.github.io/CourseSiteTheme/)
[![license](https://img.shields.io/github/license/mashape/apistatus.svg?maxAge=2592000)](https://github.com/LuckyJimJD/CourseSiteTheme/blob/master/LICENSE)

This theme is based on [alshedivat/al-folio](https://github.com/alshedivat/al-folio). It is designed for use as a simple course website, with pages for a syllabus, course materials, and links to external resources. 

## Installation 

1. Fork theme from `https://github.com/LuckyJimJD/CourseSiteTheme` to `github.com:<your-username>/<your-repo-name>`. 
2. Clone to local system. 
3. Install Ruby gems, build site, and start local server: 

    ```
    $ bundle install

    $ bundle exec jekyll serve
    ```

4. Edit _config.yml: 

    ```
    url: http://username.github.io # change "username" to your github username
    baseurl:  /repository/ # change "repository" to github repository name 
    ```

5. Edit other content and customize as desired (see below). If local server is running, changes will appear after refreshing page in browser. 

6. Commit changes in git and then push to [GitHub Pages]((https://pages.github.com/), or deploy using script: 

    ```
    $ ./bin/deploy [--user]
    ```

By default, the script uses the `master` branch for the source code and deploys the webpage to `gh-pages`.
The optional flag `--user` tells it to deploy to `master` and use `source` for the source code instead.
Using `master` for deployment is a convention for [user and organization pages](https://help.github.com/articles/user-organization-and-project-pages/).


### Modifying Theme Elements 

Fonts, font sizes, colors, spacing, etc. are set using variables (`$variable_name`) in the `_sass/variables.scss` file. 

For Google webfonts, replace the code in `_includes/head.html` with the appropriate code for your fonts. 

Available colors are defined in the same file, e.g.:`$red: #FF3636 !default;`. For additional colors, add a new definition string following the same pattern: `$color_name: #xxxxxx !default;` (where `xxxxxx`=color hex code). 

## License

The theme is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
