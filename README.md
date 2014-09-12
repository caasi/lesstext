# lesstext

As a light weight version of [MoreText.js](http://more.handlino.com/), this is a pure js implemetation of the lorem ipsum part of [view_helpers.rb](https://github.com/tka/serve/blob/master/lib/serve/view_helpers.rb#L542-L786) which can be used in front-end or back-end without making any request.

## Installation

```shell
npm install lesstext
```

## Usage

```JavaScript
lesstext = require("lesstext");

console.log(lesstext.zh.loremParagraphs(2));
```

sample output:

```
憑這一身！不是容易就能奏功，來--來！要開始了。

他高興的時候，盲目地前進！互有參差，頂部放上奶油。 實在想不到！地方自治的權能，被另一邊阻撓著，忽然地顛蹶，終也渡過彼岸。是不容有異議，滾到了天半，老不死的混蛋！暫時的時空靜止。甘失掉了麵皮！
```
