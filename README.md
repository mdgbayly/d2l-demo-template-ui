# d2l-demo-template
[![Bower version][bower-image]][bower-url]
[![Build status][ci-image]][ci-url]

A [Polymer](https://www.polymer-project.org/1.0/)-based web component for a demo page template, providing common typography, and controls for toggling things like text direction.

## Installation

`d2l-demo-template` can be installed from [Bower][bower-url]:
```shell
bower install d2l-demo-template --save-dev
```

## Usage

```html
<head>
	<script src="https://s.brightspace.com/lib/webcomponentsjs/0.7.21/webcomponents.min.js"></script>
	<link rel="import" href="../../d2l-demo-template/d2l-demo-template.html">
</head>
<body>
	<d2l-demo-template title="my-fixture-title">
		<div slot="d2l-demo-actions">
			<!-- your actions -->
		</div>
		<div slot="d2l-demo-fixture">
			<!-- your fixture -->
		</div>
	</d2l-demo-template>
</body>
```

## Coding styles

See the [VUI Best Practices & Style Guide](https://github.com/Brightspace/valence-ui-docs/wiki/Best-Practices-&-Style-Guide) for information on VUI naming conventions, plus information about the [EditorConfig](http://editorconfig.org) rules used in this repo.

[bower-url]: http://bower.io/search/?q=d2l-demo-template
[bower-image]: https://img.shields.io/bower/v/d2l-demo-template.svg
[ci-url]: https://travis-ci.org/Brightspace/d2l-demo-template-ui
[ci-image]: https://travis-ci.org/Brightspace/d2l-demo-template-ui.svg?branch=master
