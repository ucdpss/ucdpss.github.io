## About

This is the [Agency Bootstrap theme](https://startbootstrap.com/themes/agency/), converted to a gem-based Jekyll theme with GitHub Pages support.

While this has been done before, [here](https://github.com/y7kim/agency-jekyll-theme), [here](https://github.com/SotiriosVrachas/jekyll-theme-startbootstrap-agency), and [here](https://github.com/laklau/agency-jekyll-theme/), these are outdated and have not been updated or maintained for years. I built this theme from the most recent Bootstrap source.

I also added a lot of new features that go beyond the original theme's capabilities:

The Jekyll structure of this theme includes:

- `_portfolio` files - what generate the portfolio grid. YAML front matter handles all the details
- the `page` layout allows custom pages, as seen in the legal and 404 pages
- `sitetext.yml` enables complete customization of all site text
- `navigation.yml` enables fully customizable navigation
- `style.yml` enables fully customizable colors, background images, and other style-related things



## Development

To set up your environment to develop this theme, clone this repo or your fork.

```sh
$ git clone https://github.com/raviriley/agency-jekyll-theme.git
$ cd agency-jekyll-theme
```

Then run:

```sh
$ bundle install
```

To test the theme, run this. (Using the `--trace` flag for verbose errors.)

```sh
$ bundle exec jekyll serve --trace
```

Then open your browser at:

- http://localhost:4000

Add pages, documents, data, etc. like normal to test the theme's contents. As you make modifications, your site will regenerate and you should see the changes in the browser after a refresh.



