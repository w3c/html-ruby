# Diagrams for example 8

This is the source used to generate the images
used in [example 8](https://www.w3.org/TR/html-ruby-extensions/#jukugo-ruby) of [HTML Ruby Markup Extensions](https://www.w3.org/TR/html-ruby-extensions/),
in case they need to be modified and regenerated.

Meant for use in Firefox (or any browser that supports tabular ruby markup and css-ruby).

```html
<style>
body {
	font-family: serif;	font-size: 40px;
	padding: 0.5em;
	line-height: 2em;
}

o {
	color: crimson;
}

a {
	color: darkviolet;
}

#s rt { font-size: 0.33em;}
#b rt { font-size: 0.6em;}

div {
	border-left: 2px dotted gray;
	border-right: 2px dotted gray;
	width: 5.5em;
	line-height: 1;
}

#i, #i * {
    display: inline;
    font-size: 1em;
    color: inherit;
}
</style>

<body lang=ja>
<ruby id=m><rb><o>浄</o><rb>瑠<rb><a>璃</a><rt><o>じょう</o><rt>る<rt><a>り</a></ruby>
<br>	<br>

<ruby><rb><o>浄</o>瑠<a>璃</a><rt><o>じょう</o>る<a>り</a></ruby>
<br>	<br>

<ruby id=i><rb><o>浄</o>瑠<a>璃</a><rp>（<rt><o>じょう</o>る<a>り</a><rp>）</ruby>
<br>	<br>

<ruby id=s><rb><o>浄</o><rb>瑠<rb><a>璃</a><rt><o>じょう</o><rt>る<rt><a>り</a></ruby>
<br>	<br>

<ruby id=b><rb><o>浄</o>瑠<a>璃</a><rt><o>じょう</o>る<a>り</a></ruby>
<br>	<br>

<ruby><rb><o>浄</o>瑠<rb><a>璃</a><rt><o>じょう</o>る<rt><a>り</a></ruby>
<br>	<br>

<div>　　　…<ruby><rb><o>浄</o><rb>瑠<rb><a>璃</a><rt><o>じょう</o><rt>る<rt><a>り</a></ruby>…</div>
</body>
```
