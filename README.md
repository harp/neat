# harp-neat

> A fluid grid framework built upon Bourbon and Sass

## Dependencies

* [NodeJS](http://nodejs.org/) – _Server-side JavaScript runtime_
* [Harp](http://harpjs.com/) – _The static web server with built-in preprocessing_

## Install

To install Bourbon and Neat, run the following command from the root of your harp project:

```bash
harp install neat
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

Now, from within a `.scss` file in your project, you can `@import` Bourbon and Neat:

```scss
@import "components/harp-bourbon/scss/bourbon";
@import "components/harp-bourbon/scss/neat";
```

# Resources

* [Harp documentation](http://harpjs.com/docs)
* [Sass documentation](http://sass-lang.com/documentation/file.SASS_REFERENCE.html)
* [Bourbon documentation](http://bourbon.io/docs/)
* [Neat documentation](http://neat.bourbon.io/docs)

## License

This component is [Neat](http://github.com/thoughtbot/bourbon), which is Copyright © 2011-2013 thoughtbot and MIT licensed.
