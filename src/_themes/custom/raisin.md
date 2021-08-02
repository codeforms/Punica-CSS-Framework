```scss
///
/// Raisin Theme
///
raisin: (
	///////////////////////////////////////////////////////////
	// GLOBAL
	///////////////////////////////////////////////////////////
	// imported google font and weights
	'google-font'                   : 'Mulish', // or 'Source+Sans+Pro' etc.
    'google-font-weights'           : '300;400;500;600;700;900',
    // main typography settings
    'font-family'                   : 'Mulish', // main font family ('Source Sans Pro' etc)
	'font-size'						: .8133em,
	'font-weight'					: 500,
	'line-height'					: 1.7,
	'header-weight'					: 900, // for h1, h2, h3...
	'background-color'				: #2D2A2E,
	'text-color'					: white,
	///////////////////////////////////////////////////////////
	// COLOR
	///////////////////////////////////////////////////////////
	'primary-color'					: #7080e2,
	'success-color'					: #66923f,
	'warning-color'					: #cf6d4e,
	'error-color'					: #b03767,
	//
	'color-active'					: lighten(#2D2A2E, 3.7%),
	'color-negative'				: white,
	'color-grey'					: lighten(#2D2A2E, 12.5%),
	'color-secondary'				: lighten(#2D2A2E, 5%),
	'color-dark'					: lighten(#2D2A2E, 4.5%),
	///////////////////////////////////////////////////////////
	// BORDER
	///////////////////////////////////////////////////////////
	'border-color' 					: lighten(#2D2A2E, 23%),
	'border-width'					: 1px,
	'border-style'					: solid,
	'border-radius'					: 0,
	///////////////////////////////////////////////////////////
	// SHADOW
	///////////////////////////////////////////////////////////
	'shadow-horizontal'				: 0,
	'shadow-vertical'				: 4px,
	'shadow-blur'					: 3px,
	'shadow-spread'					: 0,
	'shadow-color'					: rgba(0, 0, 0, 0.17),
	///////////////////////////////////////////////////////////
	// INPUT
	///////////////////////////////////////////////////////////
	'input-bg'						: lighten(#2D2A2E, 8.5%),
	'input-color'					: white,
	'input-border-color'			: lighten(#2D2A2E, 26%),
	"input-outline-color"			: white,
	'input-outline-width'			: 2px,
	///////////////////////////////////////////////////////////
	// secondary button
	'button-secondary-bg'			: linear-gradient(to top, #2D2A2E 0%,lighten(#2D2A2E, 8.5%) 100%),
	'button-secondary-bg-hover'		: linear-gradient(to top, lighten(#2D2A2E, 8.5%) 0%,#2D2A2E 100%)
),
```