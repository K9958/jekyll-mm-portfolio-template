# Readme
This repository (`jekyll-mm-portfolio-template`) is a very-fast-to-setup portfolio template using *Jekyll*, very customizable *Minimal Mistakes theme for Jekyll*, and *GitHub Pages*. You can see the link below to see what it looks like.

Template as Pages: [https://k9958.github.io/jekyll-mm-portfolio-template/](https://k9958.github.io/jekyll-mm-portfolio-template/)

# How to use this repository

#### 1. Fork this repository under your GitHub namespace and with repository name:

```
YOUR_GITHUB_USERNAME.github.io
```

### 2. Edit `_config.yml` file to edit your details. At least edit the following:

* Edit site `title` at line 19.
* Edit site `name` at line 22.
* Edit site `description` at line 23.
* Edit `author:` info from line 105 onwards to change the template info to your info
* Either change your image path inside the `author:` code block or change the `portrait.jpg` image to your image
* Edit Social Links from Line 115 onwards. Lines with uncommented URL will show in your profile

### 3. Edit the main page

* To edit the main page, edit `index.markdown` file in the root folder of this repository.

### 4. Add your projects to your portfolio

* Add a markdown (`.md`) file to `_posts` folder with name format: `YYYY-MM-DD-CONTENT_NAME.md` You can change the template files in the folder or just delete them.

By default, newest projects will show first.

### 5. Publish your website!

* Go to repository **Settings** -> **Pages** -> **Build and deployment**. 
* Select option `Deploy from a branch`
* As branch, select `main` and folder as `/(root)`
* Now your site will build for a minute and show up at your `USERNAME.github.io`

### About customizing the site

This site is based on Minimal Mistakes Jekyll theme and Jekyll for building the site. They have their own customization tips on their own sites, be sure to check them out: 

* [Minimal Mistakes Pages](https://mmistakes.github.io/minimal-mistakes/) and [GitHub Repository](https://github.com/mmistakes/minimal-mistakes)
  * Check out Minimal Mistakes [Configuration Guide](https://mmistakes.github.io/minimal-mistakes/docs/configuration/)
  * Check also Minimal Mistakes [Sample Posts](https://mmistakes.github.io/minimal-mistakes/year-archive/) to give an idea what can be customized and how. The customized page source code/markdown files are in the MM repository.
* [Jekyll Documentation](https://jekyllrb.com/docs/pages/)
