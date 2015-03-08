#Convert from 0.5 to 0.8

##demo-basic.html

1. remove `<polymer-element>`, not required anylonger
2. the template is wrapped into a new `<dom-module>`, the id matches the element name
3. in Polymer( a new *is:* parameter now defines the *component name*, *is:* matches the *id* used in `<dom-module>`
4. convert attributes and published to new properties
5. change demo to use only components defined in external.html files, inline components in main html file don't work in FF/IE

