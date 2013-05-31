# connect-fonts-snowburstone

Snowburst One fontpack for [connect-fonts](https://github.com/shane-tomlinson/connect-fonts).

## Usage

1. Include [connect-fonts](https://github.com/shane-tomlinson/connect-fonts) in a node module.
```js
const font_middleware = require("connect-fonts");
```

2. Include the font packs that you want to serve.
```js
const font_pack  = require("connect-fonts-snowburstone");
```

3. Add a middleware by calling the `setup` function.
```js
    app.use(font_middleware.setup({
      fonts: [ font_pack ],
      allow_origin: "https://exampledomain.com"
    }));
```

4. Add a link tag to include the font CSS.
```html
<link href="/snowburstone-regular/fonts.css" type="text/css" rel="stylesheet"/ >
```


Available fonts:
* snowburstone-regular

Locale-optimised font sets can be served by specifying the locale in the fonts.css URL.
```html
<link href="/latin/snowburstone-regular/fonts.css" type="text/css" rel="stylesheet"/ >
```

Available subsets:
* latin
* en

5. Set your CSS up to use the new font by using the "Snowburst One" font-family.
```
    body {
      font-family: 'Snowburst One', 'sans-serif', 'serif';
    }
```

## Font Info
Snowburst One

* Description: Snowburst is a low contrast serifed text typeface inspired by one of Annet Stirling's distictive styles of lettering. Snowburst's personality consistently shows in both small and large sizes. Becuase of the thin stokes this font is best used from medium to large sizes.
* Copyright: Copyright (c) 2011-2012, Sorkin Type Co (www.sorkintype.com)with Reserved Font Name 'Snowburst'
* Trademark: Snowburst is a trademark of Sorkin Type Co.
* Designer: Annet Stirling
* Designer URL: www.incisiveletterwork.com 
* Vendor: Annet Stirling
* Vendor URL: www.sorkintype.com

## Development Info
* Homepage: https://github.com/shane-tomlinson/connect-fonts-snowburstone
* Repo: https://github.com/shane-tomlinson/connect-fonts-snowburstone

## Author
* Shane Tomlinson
* shane@shanetomlinson.com
* stomlinson@mozilla.com
* set117@yahoo.com
* https://shanetomlinson.com
* https://github.com/shane-tomlinson
* https://github.com/stomlinson
* @shane_tomlinson


## License

Software: Licenced under version 2.0 of the MPL

  https://www.mozilla.org/MPL/

Fonts: Licensed under version 1.1 of the SIL Open Font License

  http://scripts.sil.org/OFL

