```scss
///
/// Custom Palenight Theme
/// Material Design
///
palenight: (
	///////////////////////////////////////////////////////////
	// GLOBAL
	///////////////////////////////////////////////////////////
	// imported google font and weights
	'font-family'					: 'Nunito', // main font family
	'font-weights'					: '300;400;600;700;900',
	// main typography settings
	'font-size'						: 13px,
	'font-weight'					: 400,
	'line-height'					: 1.7,
	'header-weight'					: 900, // for h1, h2, h3...
	'background-color'				: #292d3e,
	'text-color'					: white,
	///////////////////////////////////////////////////////////
	// COLOR
	///////////////////////////////////////////////////////////
	'primary-color'					: #30a3d1,
	'success-color'					: #87a45d,
	'warning-color'					: #b9924a,
	'error-color'					: #bf5b60,
	//
	'color-active'					: lighten(#292d3e, 3.7%),
	'color-negative'				: white,
	'color-grey'					: #565e81,
	'color-secondary'				: lighten(#292d3e, 5%),
	'color-dark'					: lighten(#292d3e, 4.5%),
	///////////////////////////////////////////////////////////
	// BORDER
	///////////////////////////////////////////////////////////
	'border-color' 					: lighten(#292d3e, 23%),
	'border-width'					: 1px,
	'border-style'					: solid,
	'border-radius'					: 4px,
	///////////////////////////////////////////////////////////
	// SHADOW
	///////////////////////////////////////////////////////////
	'shadow-horizontal'				: 0,
	'shadow-vertical'				: 4px,
	'shadow-blur'					: 7px,
	'shadow-color'					: rgba(0, 0, 0, 0.21),
	///////////////////////////////////////////////////////////
	// INPUT
	///////////////////////////////////////////////////////////
	'input-bg'						: lighten(#292d3e, 8.5%),
	'input-color'					: white,
	'input-border-color'			: lighten(#292d3e, 26%),
	"input-outline-color"			: white,
	'input-outline-width'			: 2px,
	///////////////////////////////////////////////////////////
	// secondary button
	'button-secondary-bg'			: linear-gradient(to top, #292d3e 0%,#31364b 100%),
	'button-secondary-bg-hover'		: linear-gradient(to top, #31364b 0%,#292d3e 100%)
)
```