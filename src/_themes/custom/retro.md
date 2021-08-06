```scss
///
/// Retro Theme
///
retro: (
	///////////////////////////////////////////////////////////
	// GLOBAL
	///////////////////////////////////////////////////////////
	// imported google font and weights
    // elements->typography->variables
	'google-font'                   : 'Montserrat+Alternates',
    'google-font-weights'           : '300;400;500;700;900',
    // typography settings
    'font-family'                   : 'Montserrat Alternates',
	'font-size'						: .7493em,
	'font-weight'					: 500,
	'line-height'					: 1.8,
	'header-weight'					: 900,
	'background-color'				: #493323,
	'text-color'					: white,
	///////////////////////////////////////////////////////////
	// COLOR
	///////////////////////////////////////////////////////////
	'primary-color'					: #5eaaa8,
	'success-color'					: #879a67,
	'warning-color'					: #de7e57,
	'error-color'					: #cd5c5c,
	//
	'color-active'					: lighten(#493323, 3.7%),
	'color-negative'				: white,
	'color-grey'					: lighten(#493323, 24%),
	'color-secondary'				: lighten(#493323, 7.4%),
	'color-dark'					: lighten(#493323, 8.5%),
	///////////////////////////////////////////////////////////
	// BORDER
	///////////////////////////////////////////////////////////
	'border-color' 					: lighten(#493323, 10%),
	'border-width'					: 1px,
	'border-style'					: solid,
	'border-radius'					: 2px,
	///////////////////////////////////////////////////////////
	// SHADOW
	///////////////////////////////////////////////////////////
	'shadow-horizontal'				: 0,
	'shadow-vertical'				: 2px,
	'shadow-blur'					: 4px,
	'shadow-spread'					: 1px,
	'shadow-color'					: rgba(0, 0, 0, 0.24),
	///////////////////////////////////////////////////////////
	// INPUT
	///////////////////////////////////////////////////////////
	'input-bg'						: lighten(#493323, 8.5%),
	'input-color'					: white,
	'input-border-color'			: lighten(#493323, 26%),
	"input-outline-color"			: lighten(#493323, 38%),
	'input-outline-width'			: 2px,
	///////////////////////////////////////////////////////////
	// secondary button
	'button-secondary-bg'			: linear-gradient(to top, #493323 0%,lighten(#493323, 8.5%) 100%),
	'button-secondary-bg-hover'		: linear-gradient(to top, lighten(#493323, 8.5%) 0%,#493323 100%)
)
```