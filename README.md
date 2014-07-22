# harp-neat

> A fluid grid framework built upon Bourbon and Sass

## Dependencies

* [NodeJS](http://nodejs.org/) – _Server-side JavaScript runtime_
* [Harp](http://harpjs.com/) – _The static web server with built-in preprocessing_

## Install

To install Neat, you can [download this repository](https://github.com/harp/neat/archive/master.zip) or use the [Component](http://component.io) package manager.

```bash
npm install -g component
component install harp/neat
```

Your project will look something like this…

```
myproject/                  <-- your project root (or public dir if in framework-mode)
  |- components/            <-- harp puts components here
  |   +- harp-bourbon/      <-- where Bourbon is installed
  |   +- harp-neat/         <-- where this lib is installed
  |       …
  |- main.scss              <-- where you reference Bourbon and Neat 
  +- index.jade             <-- where you reference main.css
```

## Link

Now, from within an `.scss` file in your project, you can `@import` Bourbon and Neat:

```scss
@import "components/harp-bourbon/scss/bourbon";
@import "components/harp-neat/scss/neat";
```

## Resources

* [Harp documentation](http://harpjs.com/docs)
* [Sass documentation](http://sass-lang.com/documentation/file.SASS_REFERENCE.html)
* [Bourbon documentation](http://bourbon.io/docs/)
* [Neat documentation](http://neat.bourbon.io/docs)

## License

This component is [Neat](http://github.com/thoughtbot/bourbon), which is Copyright © 2011-2013 thoughtbot and MIT licensed.
