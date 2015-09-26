# Jekyll Starter Kit

This Jekyll starter was made by [Chloe Atchue-Mamlet](http://chloeam.com/).

## What's Included

* Structure for modular Sass styles
* Bourbon
* Neat
* Google Analytics Capability (can delete the _includes file if you don't want it)
* Google Fonts Capability (can delete the _includes file if you don't want it)
* Default 'Welcome to Jekyll' Post for testing
* Minimal base styling

## What's Not Included

* Opinionated styling
* Content

## Getting Started

This Jekyll starter kit requires Jekyll 2.x. 

### Setup a New Jekyll Site

1. Install bundler with `gem install bundler` then install Jekyll and all its dependencies with `gem install jekyll`.

2. Clone this repository with `git clone git://github.com/chloeam/jekyll-starter.git`

3. Rename the directory `jekyll-starter` to the name of your new site

4. `cd your-site-folder`

5. Edit `_config.yml` to personalize the site

6. Run jekyll with `jekyll serve`. The site will be available locally at [http://localhost:8000](http://localhost:8000)

### Adding Your Own Remote Repository

At this point, you've cloned this entire repository, including the remote and commit history. To add your own remote,

1. Delete the current remote with `git remote rm origin`

2. Start a new repo on github

3. Run `git remote add origin https//github.com/user/repo.git`

4. Run `git push -u origin master`

Now, you have your own remote set up!

### Setup Disqus Comments

1. If you're not already signed up with diqus, [do that](https://disqus.com)

2. In `_config.yml`, set the variable `disqus` (under `owner`) to your disqus shortname

3. To enable comments on any page, simply type `{% include disqus.html %}`

### Setup Google Analytics

1. If you're not signed up with Google Analytics, do that [here](http://www.google.com/analytics/)

2. In `_config.yml`, set the variable `google-analytics` to your Google Analyitcs tracking ID

### Use Google Fonts

1. In [Google fonts,]() add the fonts you'd like to your collection

2. Click "Use"

3. Copy and paste the text in the box labeled "Add this code to your website" into the file `_includes/google-fonts.html`

4. To use the fonts, change the `$base-font`, `$heading-font`, `$secondary-heading-font`, or `$caption-font` variables in `_assets/stylesheets/_variables.scss` to the name of the Google font in single quotes