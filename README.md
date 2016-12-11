# slider-carousel

## Demo
You can see a demo [here](https://framled.github.io/slider-carousel/components/slider-carousel/)

## Download

`bower install --save framled/slider-carousel`

## Import
`<link rel="import" href="path/to/slider-carousel/slider-carousel.html>`

## Use it

A simple carousel with controls appear when you need it

```html
<simple-carousel>
	<div class="slide-carousel"></div>
	<div class="slide-carousel"></div>
	<div class="slide-carousel"></div>
</slider-carousel>
```

or you can use the controlsAlwaysVisible properties for always show controls

```html
<simple-carousel controls-always-visible>
	<div class="slide-carousel"></div>
	<div class="slide-carousel"></div>
	<div class="slide-carousel"></div>
</slider-carousel>
```

also you can set up duration of animation whit duration property, 280 is default value

```html
<simple-carousel duration="1000">
	<div class="slide-carousel"></div>
	<div class="slide-carousel"></div>
	<div class="slide-carousel"></div>
</slider-carousel>
```

### Styling

The following custom properties and mixins are available for styling:

Custom property | Description | Default
----------------|-------------|----------
`--slide-carousel-width` | The slide's width | `null`
`--slide-carousel-height` | The slide's height | `null`

### Events 

Custom property | Description 
----------------|-------------
`slider-controls-toggle` | Fired when a mouse enter or leave.