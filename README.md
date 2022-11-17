# jekyll-mm-portfolio-template
A Portfolio template using Jekyll and Minimal Mistakes theme for Jekyll, and GitHub Pages

# How to use this repository

#### 1. Fork this repository under your GitHub namespace and with repository name:

```
YOUR_GITHUB_USERNAME.github.io
```

#### 2. Edit `_config.yml` file to edit your details. At least edit the following:

* Edit site `title` at line 19.
* Edit site `name` at line 22.
* Edit site `description` at line 23.
* Edit `author:` info from line 105 onwards to change the template info to your info
* Either change your image path inside the `author:` code block or change the `portrait.jpg` image to your image
* Edit Social Links from Line 115 onwards. Lines with uncommented URL will show in your profile

#### 3. Add your projects to your portfolio

* Add a markdown (`.md`) file to `_posts` folder with name format: `YYYY-MM-DD-CONTENT_NAME.md` You can change the template files in the folder or just delete them.

By default, newest projects will show first.

#### 4. Publish your website!
* Go to repository **Settings** -> **Pages** -> **Build and deployment**. 
* Select option `Deploy from a branch`
* As branch, select `main` and folder as `/(root)`
* Now your site will build for a minute and show up at your `USERNAME.github.io`