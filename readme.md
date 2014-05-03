This is woefully out of date and in no way will it be updated.

# Web Components talk

The future of web development is through low level APIs that offer developers flexibility and granular control. Web Components are a part of this movement and offer great control over truly encapsulation "widgets".

## Dog fooding

This slide deck is itself a series of web components that demostrate the very topics I discuss through out the talk.

1. [`<x-slideshow \>`](https://github.com/ryanseddon/slideshow-component) is the top level container element
1. [`<x-slide \>`](https://github.com/ryanseddon/slideshow-component) is the individual peice within a slideshow element that itself extends another custom element.
1. [`<x-markdown />`](https://github.com/ryanseddon/markdown-component) is an element that excepts markdown as input and converts it to HTML.

## Polymer

This slideshow uses the very cool Polymer library that offers both a series of polyfills as well as a wrapper on top of the Web Components API to abstract and add extra functionality.
