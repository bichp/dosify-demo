## DocsifyJS Tutorial
> Build a Markdown-based docs site using _DocsifyJS_ and _GitHub Pages_

[![GitHub tag](https://img.shields.io/github/tag/MichaelCurrin/docsify-js-tutorial?color=3271a8)](https://GitHub.com/MichaelCurrin/docsify-js-tutorial/tags/)
[![stars - docsify-js-tutorial](https://img.shields.io/github/stars/MichaelCurrin/docsify-js-tutorial?style=social)](https://github.com/MichaelCurrin/docsify-js-tutorial)
[![forks - docsify-js-tutorial](https://img.shields.io/github/forks/MichaelCurrin/docsify-js-tutorial?style=social)](https://github.com/MichaelCurrin/docsify-js-tutorial)

[![Made with Docsify latest](https://img.shields.io/npm/v/docsify?label=docsify&color=3271a8)](https://docsify.js.org/ "Go to Docsify homepage")


Convert your **docs** folder into a pretty and modern docs website, built around your Markdown content and a theme. 

Using a JavaScript library called "DocsifyJS", this tutorial shows you how by doing some light set up. This can all be done on the GitHub and is simple enough for those without JavaScript experience and does not require using Node.

?> See [docsify.js.org](https://docsify.js.org/) homepage or the [docsify](https://www.npmjs.com/package/docsify) package on NPM.

Unlike other JavaScript-based frameworks, DocsifyJS needs just a few lines of JavaScript as configuration and the rest of your content is mostly Markdown and YAML. It is built on Vue, but you don't need to know anything about Vue to get the benefits.

This project's site itself is also running on _DocsifyJS_. :tada:

Start below with the basics, or skip to the later sections with the sidebar to get to menu customization, plugins and styling.

Code snippets and recommendations are provided here as kind of cheatsheet or cookbook, so you don't have to spend a lot of time pouring over all the possible options and features covered in the docs that you probably don't need to know.

?> _DocsifyJS_ is sometimes just called _Docsify_ in this guide. Also known as _Docsify.js_.

View the source for this tutorial, which is built on Docsify:

- [![MichaelCurrin - docsify-js-tutorial](https://img.shields.io/static/v1?label=MichaelCurrin&message=docsify-js-tutorial&color=3271a8&logo=github)](https://github.com/MichaelCurrin/docsify-js-tutorial "Go to DocsifyJS Tutorial repo on GitHub")


## Purpose of this tutorial

This project is for you if you answer _yes_ to any of the following:

- Are you new to making a docs site?
- Tired of writing HTML/CSS/JS and just want to write docs using plain Markdown?
- What is DocsifyJS?
- Want to add features and style to your DocsifyJS site?
- Looking for a template which is based on real world use?
- Can I make a build a docs site without having a build step?


## Set up site to run

This project provides three approaches for choosing a Docsify site to run:

- Use the [Quickstart local server](#quickstart-local-server)
    - Clone this repo and start serving the docs repo immediately.
- [Set up your own docs site](#setup-your-own-docs-site) from scratch.
    - Convert your _docs_ directory into a docs site hosted on GitHub Pages. Copy from some templates files to get up and running with as little effort as possible.
- Use my [DocsifyJS Template](https://github.com/michaelcurrin/docsify-js-template/) repo
    - A minimal template which goes with this tutorial.
    - Click [Use this template](https://img.shields.io/badge/Use_this_template-green.svg?style=for-the-badge) to add a copy to you own repos. you'll be able to starting serving a site on GitHub Pages or locally.

_Note: The instructions in this repo are intended for Linux and macOS environments._
