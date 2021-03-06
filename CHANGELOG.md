## 0.1.0 - 31/08/2018

* Initial Release.

## 0.1.1 - 31/08/2018

* Fixed CHANGELOG.
* Small fix to documentation

## 0.1.2 - 31/08/2018

* Small fix to README

## 0.2.0 - 02/09/2018

* Changed the suggestions box decoration
to decorate a material sheet instead of 
decorating a container
* Moved the `TextField` properties inside a class
called `TextFieldConfiguration`, which is provided
to the `TypeAhead` widgets through a 
`textFieldConfiguration` property. This was done to 
decrease the clutter in the interface
* Added more configuration properties to the 
`TextField`
* Added a configurable vertical offset for the 
suggestions box
* Changed the mechanism used to open/close the suggestions box
* Added meta-tags to README for SEO
* Updated the GIF to show the changes
* Added "How you can help" section to README

## 0.2.1 - 04/09/2018

* Added mention of 'autocomplete' in README and pubspec
* Executed 'flutter format'

## 0.3.0 - 15/09/2018

* Added a constraints property to the `SuggestionsBoxDecorations`
which allows to set the height and width of the suggestions box

## 0.4.0 - 20/09/2018

* Added property `getImmediateSuggestions` to allow fetching 
suggestions before the user types
* Added assertion in the form field to disallow having `initialValue`
and `textFieldConfiguration.controller` defined at the same time