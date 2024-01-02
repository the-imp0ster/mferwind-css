# mferwind css library

mferwind is a free-to-use custom css library designed to provide simple and nice-looking utility classes for web design based on the colors found in the mfer collection.

## features

- **mferish color palette**: a set of predefined colors from the mfer traits.
- **flexible layout classes**: utility classes for common flexbox layouts, with more on the way!
- **custom font**: integration of 'sartoshi script', a cc0 font based on sartoshi's handwriting.
- **border styles**: a variety of border styles in different thicknesses and patterns.

## installation

mferwind is not yet an npm package, so you'll need to manually grab the css file from this repo to make use of the styles.

luckily, this is a super simple process!

to use mferwind in your project, copy the `mferwind.css` file into your project folder and link to it file in the head element of your html:

```html

<link rel="stylesheet" href="path/to/mferwind.css">

```
make sure you also grab the file for the sartoshi script (`SartoshiScript-Regular.otf`) to include in your project folder!

now you can start using mferwind style classes right in your html, like this:
```html
<div class="bg-green sartoshi">
```

the example above provides a green background to the div and applies the sartoshi font family to any text present in the div.

## color variables

mferwind currently consists of 8 custom colors based on the mfer background colors.

## font integration

mferwind includes *sartoshi script*, a font created by mfer @hyreal3 that mimics sartoshi's handwriting.

## utility & style classes

mferwind includes classes for styles and utilities, such as:

* layout (flex, centering, etc)
* font utility (applying sartoshi script)
* background color
* text color & size
* border colors & styles


## permitted use

you are welcome to use mferwind in any project you like!

you are also welcome to add to the library via pull request if you'd like to contribute :)


## future additions

i'm working on adding classes for:
* grid layout and flexwrapping
* screen size responsiveness
* opacity & blur filters
* hover styles
