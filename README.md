# sapire.github.io

Live demo at https://sapire.github.io/

# Quick Setup

1. Install Jekyll: `gem install jekyll bundler`
2. Fork this repository and clone your fork
3. Edit `_config.yml` to personalize your site

# Settings

You have to fill some informations on `_config.yml` to customize your site:

## Site settings
```yml
description: A blog about lorem ipsum dolor sit amet
baseurl: "" # the subpath of your site, e.g. /blog/
url: "http://localhost:3000" # the base hostname & protocol for your site
```

## User settings
```yml
username: Lorem Ipsum
user_description: Software Engineer at Lorem Ipsum Dolor
user_title: Mauricio Urraco
email: mauriurraco@gmail.com
```

> Don't forget to change your URL before you deploy your site!

# Content

You can (and should) edit the `.html` files for adding your own information, icons, working experience, social links or whatever you want to add. I.e.:

```html
<a aria-label="My Github" target="_blank" href="https://github.com/sapire">
  <i class="icon fa fa-github-alt" aria-hidden="true"></i>
</a>
```

# Running locally

In order to compile the assets and run `Jekyll` locally you need to follow those steps:

1. Install Jekyll
2. Run `bundle install`
3. Run `bundle exec jekyll build`
4. Start and http-server in the folder `_site`
