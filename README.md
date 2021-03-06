# airtable-blog

This is an example from the tutorial on Airtable's blog [Build your own custom blog CMS with Airtable and GatsbyJS](https://blog.airtable.com/build-your-own-custom-blog-cms-with-airtable-and-gatsbyjs/).

It uses [GatsbyJS](https://github.com/gatsbyjs/gatsby) and [Airtable](https://airtable.com/) as a backend.

This is a starter for [GatsbyJS](https://github.com/gatsbyjs/gatsby)
based on
[gatsby-starter-gatsbytheme](https://github.com/saschajullmann/gatsby-starter-gatsbythemes).
It's a minimal theme inspired by https://www.helloper.com/.

## Demo
A preview of the starter can be seen [here](http://dmwl.net/gatsby-hampton-theme/).

## What's included

Currently this starter includes the following:

* CSS-in-JS via [Emotion](https://github.com/emotion-js/emotion)
* Jest and Enzyme for testing
* Eslint in dev mode with the airbnb config and prettier formatting rules
* React 16
* A basic blog, with posts under src/pages/blog. There's also a script which creates a new Blog entry (post.sh).
* Data per JSON files
* A few basic components (Navigation, Layout, Link wrapper around
  `gatsby-link`))
* Layout components make use of [Styled-System](https://github.com/jxnblk/styled-system)
* Google Analytics (you just have to enter your tracking-id)
* Gatsby-Plugin-Offline which includes Service Workers
* [Prettier](https://github.com/prettier/prettier) for a uniform codebase
* [Normalize](https://github.com/necolas/normalize.css/) css (7.0)
* [React Icons](https://gorangajic.github.io/react-icons/)


## How to use it?

After you clone and cd to the project you can run

```
gatsby develop
```

or

```
gatsby build
```
