dothivify
=========

Place digital stumbling blocks on your website to support the cause of [dotHIV](https://click4life.hiv/)

* Support the fight against HIV
* 2.73KB minified and gzipped

#### What this does
Basically, it helps you helping us making the world a tiny bit better: dothivify replaces all dots in text content of your site with tiny stumbling blocks directing to [click4life.hiv](https://click4life.hiv/) or the .hiv domain of your choosing. Every click on any .hiv domains generates charity spendings for initiatives supporting the fight against HIV.

#### Getting started

##### 1. Using our generator
* Visit [mydotfor.hiv/dothivify](http://mydotfor.hiv/dothivify/)
* Configure the dothivify script as you wish (our go with the turnkey solution)
* Embedd it at the end of your document's `<body>` tag

##### 2. Build it yourself
```bash
git clone https://github.com/dothiv/dothivify.git
cd dothivify
npm install
npm run build
```

##### Options
* `buttonHref` - Target of the popover button
* `buttonText` - Display text of the popover button
* `diameter` - Diameter of the replacement dots
* `dotBackground` - Background color of the replacement dots
* `popoverBackground` - Background color of the popover
* `popoverFontSize` - Font size of the popover
* `popoverColor` - Text color of the popover
* `text` - Text displayed in the popover
* `buttonTarget` - `[target]` of the popover button
* `replaced` - Character to search and replace
* `queries` - `document.querySelectorAll` query strings. Matched elements text contents will be search and replaced for `replaced`
* `offset` - Offset between dots and popovers

#### License
dothivify is published under the MIT License. See the [License File](https://github.com/dothiv/dothivify/blob/master/LICENSE) for details.
