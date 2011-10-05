Behavior Filter: Behavior.BS.Twipsy
===================================

A behavior filter to instantiate [Bootstrap](http://twitter.github.com/bootstrap/#popovers) simple tips.

### Demo / Fancy Docs

[http://anutron.github.com/mootools-bootstrap/#popover](http://anutron.github.com/mootools-bootstrap/#popover)

### Example

	<a data-behavior="BS.Twipsy" title="A Title"
		data-twipsy-options="
			'location':'left',
			'offset': -10
		">hover for tip</a>

### Options

* content - (*string*) The content of the popup. If not defined, will attempt to read it from the element's `title` property.
* location - (*string*) The location of the tip: `above`, `below`, `left`, or `right`. Defaults to `above`.
* animate - (*boolean*) If true the tip will fade in. Defaults to `true`.
* delayIn - (*number*) The time in milliseconds that the tip should delay from showing. Defaults to `200`.
* delayOut - (*number*) The time in milliseconds that the tip should delay from hiding. Defaults to `0`.
* offset - (*number* or *object*) The offset of the tip. If a number, will be used for the y offset for `top` and `bottom` located tips, x for `left` and `right` located tips. If an object, should contain `.y` and/or `.x` numerical values. Defaults to `10`.
* trigger - (*string*) The event type to attach to the target element to show the tip. Choose from `hover`, `focus`, or `manual`.