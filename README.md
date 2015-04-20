# styl-font-face
Font-face mixin for stylus

## Install

```bash
$ npm install styl-font-face --save
```

## Usage

```Stylus
@import '../_font-face'

font-regular = 'Open Sans Regular'

	font-face(font-regular, 'fonts/', 'OpenSans-Regular-webfont', 'open_sansregular')

.element
	font-family font-regular;


```

## License

MIT