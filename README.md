# Skycons-Component


## Installation  

	yarn add skycons-component
	npm install skycons-component


## What is this?  
This is a configurable react component that is easy to use.
It was mainly done for presenting icons that corresponds
to the response values retrieved from darksky weather api.

## Usage

### Component Properties
The component accept properties in order to make it
customizable. Each prop **except** the icon prop
has a default value.

|prop name|default|description|
|---|---|---|
|animate|false|Boolean representing whether the component should
be animated or not.|
|icon||String representing which icon should be presented.
The icons allowed are the once specified in the skycons lib|
|iconColor|black|String representing the color of the icon.|


### Basic Example
```javascript

// import export style
import Skycons from 'skycons-component'

// require style
const Skycons = require('skycons-component')

const WeatherPresentation = () =>
	<div>
		<Skycons 
			icon='rain'
			colorIcon='purple'
			animate={true}
			style={{ width: 128, height: 128}}
		/>
	</div>

```
