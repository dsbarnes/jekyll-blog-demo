# Jekyll Blog Demo
> Demo to show off a minimal Jekyll blog

This repo was created using Jekyll's base template for a blog.

```bash
$ jekyll new jekyll-blog-demo
```

## Setup and Run

This project was created to be run locally and on Github Pages.

For instructions on how to setup and run this project locally, see my [gist](https://gist.github.com/MichaelCurrin/1085ab164550b31272699920b5549d4b).

Since this is a _Project Page_ and not a _User Page_, the assets are relative to the root domain by default and that gives `404` errors. Therefore the empty `baseurl` in [config file](_config.yml) had to be replaced with a value.


## Gems

This project uses the following gems:

- [jekyll](https://github.com/jekyll/jekyll)
    > "Jekyll is a blog-aware static site generator in Ruby"
- [minima](https://github.com/jekyll/minima)
    > _"Minima is a one-size-fits-all Jekyll theme for writers."_
- [jekyll-feed](https://github.com/jekyll/jekyll-feed)
    > _"A Jekyll plugin to generate an Atom (RSS-like) feed of your Jekyll posts."_
