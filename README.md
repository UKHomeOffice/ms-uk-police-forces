# Modern Slavery UK Police Forces

Exports a list of UK Police Forces to be used in the modern slavery app.

Can be used with the [Typeahead Aria](https://github.com/UKHomeOffice/typeahed-aria), which is exported with [HOF Frontend Assets](https://github.com/UKHomeOfficeForms/hof-frontend-assets).

## Example Usage

The following is an example of Modern Slavery UK Police Forces in a HOF `field` with Typeahead Aria:
```
'country-select'-step: {
  mixin: 'select',
  className: ['typeahead', 'js-hidden'],
  options: [''].concat(require('ms-uk-police-forces')),
  legend: {
    className: 'visuallyhidden'
  },
  validate: ['required']
},
```