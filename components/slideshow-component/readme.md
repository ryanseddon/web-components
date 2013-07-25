# Slideshow component

A slideshow component using [bespoke.js](https://github.com/markdalgleish/bespoke.js)

## How to use

This web component uses the [Polymer](https://github.com/Polymer/polymer) library.

1. Run `bower install` to get dependencies
1. Run `git submodule init` then `git submodule update`
1. Import component `<link rel="import" href="x-slideshow.html" />`
1. Your slide show will be contained inside `<x-slideshow>` tag
1. Individual slides are are contained in `<x-slide>`

```html
<x-slideshow>
  <x-slide>
    # Slides can accept markdown

    <h2>...and html just fine</h2>

    Due to some issues any code will need to be wrapped in <pre><code> the triple backtick(`) won't work, for now.
  </x-slide>
</x-slideshow>
```

`<x-slide>` in automagically pulled in via its parent `<x-slideshow>`. `<x-slide>` extends my other [`<x-markdown>` component](https://github.com/ryanseddon/markdown-component) for easy slide creation.

## Made as part of talk

I did a talk on Web Components and created a whole bunch of components to dog food the talk itself. See master repo [web-components](https://github.com/ryanseddon/web-components).