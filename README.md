# JQuery Form Autofill

JQuery Plugins for auto filling form.

## Getting Started

In your web page:

```html
<script src="plugins/jQuery/jQuery-2.1.4.min.js"></script>
<script src="js/shollu-autofill.js"></script>
<script>
jQuery(function($) {
	var data = [
		{id:1, code:"XYZ", name:"XYZ, PT."}
	];
  $("form").shollu_autofill('load', data);  
});
</script>
```

## Documentation
_(Coming soon)_

## Examples

For Reset Form:
```html
$("form").shollu_autofill('reset');
```

## Release History
_(Nothing yet)_
