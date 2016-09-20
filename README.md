# d2l-demo-template

A [Polymer](https://www.polymer-project.org/1.0/)-based web component for a demo page template, providing common typography, and controls for toggling things like text direction.

## Usage

```html
<head>
	<script src="https://s.brightspace.com/lib/webcomponentsjs/0.7.21/webcomponents.min.js"></script>
	<link rel="import" href="../../d2l-demo-template/d2l-demo-template.html">
</head>
<body>
	<d2l-demo-template title="my-fixture-title">
		<div class="d2l-demo-actions">
			<!-- your actions -->
		</div>
		<div class="d2l-demo-fixture">
			<!-- your fixture -->
		</div>
	</d2l-demo-template>
</body>
```
