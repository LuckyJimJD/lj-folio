# lj-folio

## A [Jekyll](https://jekyllrb.com/) theme for academic course sites. 

[![demo](https://img.shields.io/badge/theme-demo-brightgreen.svg)](https://LuckyJimJD.github.io/lj-folio/)
[![license](https://img.shields.io/github/license/mashape/apistatus.svg?maxAge=2592000)](https://github.com/LuckyJimJD/CourseSiteTheme/blob/master/LICENSE)

This theme is based on [alshedivat/al-folio](https://github.com/alshedivat/al-folio). It is designed for use as a simple course website, with pages for a syllabus, course materials, and links to external resources. 

## Installation 

1. Fork theme from `https://github.com/LuckyJimJD/CourseSiteTheme` to `github.com:<your-username>/<your-repo-name>`. 

2. Clone to local system. 

3. Edit _config.yml: 

    ```
    url: http://username.github.io # change "username" to your github username
    baseurl:  /repository/ # change "repository" to github repository name 
    ```

4. Edit other content:

- The 'assets/img' folder has images used on the 'Teaching' page. 
  - File names should ollow the pattern 'RepoName.png' or 'RepoName.jpg' (replacing 'RepoName' with the name of the repository for the site you want to link to and using the appropriate extension for the image format). 
  - You can also put other images in that folder if you wish. 
- The '_data' folder has YAML files with information to populate the 'About', 'Scholarship' & 'Teaching' pages. 

6. Commit changes in git and then push to [GitHub Pages]((https://pages.github.com/).


### Modifying Theme Elements 

Fonts, font sizes, colors, spacing, etc. are set using variables (`$variable_name`) in the `_sass/variables.scss` file. 

For Google webfonts, replace the code in `_includes/head.html` with the appropriate code for your fonts. 

Available colors are defined in the same file, e.g.:`$red: #FF3636 !default;`. For additional colors, add a new definition string following the same pattern: `$color_name: #xxxxxx !default;` (where `xxxxxx`=color hex code). 

## License

The theme is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
