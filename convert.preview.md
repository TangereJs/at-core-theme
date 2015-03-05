#Convert from 0.5 to 0.8

##demo-basic.html

1. remove `<polymer-element>`, not required anylonger
2. the template is wrapped into a new `<dom-module>`, the id matches the element name
3. in Polymer( a new is: parameter now defines the component name, is: matches the id used in 4. change demo to use only components defined in external.html files, inline components in main html file don't work in FF/IE

see https://github.com/TangereJs/at-core-theme/commit/545b100e508acf2e679c35e3257ac2dcc7a824af?diff=split
