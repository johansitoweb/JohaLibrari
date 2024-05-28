# JohaLibrari
JohaLibrari  es una librería de componentes visuales de css desarrollada por el ingeniero en sistema Johan antonio mancebo lebron esta es una  librería  liviana con la cual poidras crear muchas cosas.

Link de la Docmuentacion
https://pickled-walrus-4a0.notion.site/JohaLibrari-bb350c9699ee4e569c1f97d24a19483d#2afc68f4321e4b88abfebdb44fa026a2

Techologias y herramientas que se utilizo para Desarrollar este proyecto.
js html css bootstrap nes.css y una pequeña libreria de javascript

<html><head>
	<meta http-equiv="Content-Type" content="text/html; charset=utf-8"/>
	<title>codigo</title>
	<style>
/* cspell:disable-file */
/* webkit printing magic: print all background colors */
html {
	-webkit-print-color-adjust: exact;
}
* {
	box-sizing: border-box;
	-webkit-print-color-adjust: exact;
}

html,
body {
	margin: 0;
	padding: 0;
}
@media only screen {
	body {
		margin: 2em auto;
		max-width: 900px;
		color: rgb(55, 53, 47);
	}
}

body {
	line-height: 1.5;
	white-space: pre-wrap;
}

a,
a.visited {
	color: inherit;
	text-decoration: underline;
}

.pdf-relative-link-path {
	font-size: 80%;
	color: #444;
}

h1,
h2,
h3 {
	letter-spacing: -0.01em;
	line-height: 1.2;
	font-weight: 600;
	margin-bottom: 0;
}

.page-title {
	font-size: 2.5rem;
	font-weight: 700;
	margin-top: 0;
	margin-bottom: 0.75em;
}

h1 {
	font-size: 1.875rem;
	margin-top: 1.875rem;
}

h2 {
	font-size: 1.5rem;
	margin-top: 1.5rem;
}

h3 {
	font-size: 1.25rem;
	margin-top: 1.25rem;
}

.source {
	border: 1px solid #ddd;
	border-radius: 3px;
	padding: 1.5em;
	word-break: break-all;
}

.callout {
	border-radius: 3px;
	padding: 1rem;
}

figure {
	margin: 1.25em 0;
	page-break-inside: avoid;
}

figcaption {
	opacity: 0.5;
	font-size: 85%;
	margin-top: 0.5em;
}

mark {
	background-color: transparent;
}

.indented {
	padding-left: 1.5em;
}

hr {
	background: transparent;
	display: block;
	width: 100%;
	height: 1px;
	visibility: visible;
	border: none;
	border-bottom: 1px solid rgba(55, 53, 47, 0.09);
}

img {
	max-width: 100%;
}

@media only print {
	img {
		max-height: 100vh;
		object-fit: contain;
	}
}

@page {
	margin: 1in;
}

.collection-content {
	font-size: 0.875rem;
}

.column-list {
	display: flex;
	justify-content: space-between;
}

.column {
	padding: 0 1em;
}

.column:first-child {
	padding-left: 0;
}

.column:last-child {
	padding-right: 0;
}

.table_of_contents-item {
	display: block;
	font-size: 0.875rem;
	line-height: 1.3;
	padding: 0.125rem;
}

.table_of_contents-indent-1 {
	margin-left: 1.5rem;
}

.table_of_contents-indent-2 {
	margin-left: 3rem;
}

.table_of_contents-indent-3 {
	margin-left: 4.5rem;
}

.table_of_contents-link {
	text-decoration: none;
	opacity: 0.7;
	border-bottom: 1px solid rgba(55, 53, 47, 0.18);
}

table,
th,
td {
	border: 1px solid rgba(55, 53, 47, 0.09);
	border-collapse: collapse;
}

table {
	border-left: none;
	border-right: none;
}

th,
td {
	font-weight: normal;
	padding: 0.25em 0.5em;
	line-height: 1.5;
	min-height: 1.5em;
	text-align: left;
}

th {
	color: rgba(55, 53, 47, 0.6);
}

ol,
ul {
	margin: 0;
	margin-block-start: 0.6em;
	margin-block-end: 0.6em;
}

li > ol:first-child,
li > ul:first-child {
	margin-block-start: 0.6em;
}

ul > li {
	list-style: disc;
}

ul.to-do-list {
	padding-inline-start: 0;
}

ul.to-do-list > li {
	list-style: none;
}

.to-do-children-checked {
	text-decoration: line-through;
	opacity: 0.375;
}

ul.toggle > li {
	list-style: none;
}

ul {
	padding-inline-start: 1.7em;
}

ul > li {
	padding-left: 0.1em;
}

ol {
	padding-inline-start: 1.6em;
}

ol > li {
	padding-left: 0.2em;
}

.mono ol {
	padding-inline-start: 2em;
}

.mono ol > li {
	text-indent: -0.4em;
}

.toggle {
	padding-inline-start: 0em;
	list-style-type: none;
}

/* Indent toggle children */
.toggle > li > details {
	padding-left: 1.7em;
}

.toggle > li > details > summary {
	margin-left: -1.1em;
}

.selected-value {
	display: inline-block;
	padding: 0 0.5em;
	background: rgba(206, 205, 202, 0.5);
	border-radius: 3px;
	margin-right: 0.5em;
	margin-top: 0.3em;
	margin-bottom: 0.3em;
	white-space: nowrap;
}

.collection-title {
	display: inline-block;
	margin-right: 1em;
}

.page-description {
    margin-bottom: 2em;
}

.simple-table {
	margin-top: 1em;
	font-size: 0.875rem;
	empty-cells: show;
}
.simple-table td {
	height: 29px;
	min-width: 120px;
}

.simple-table th {
	height: 29px;
	min-width: 120px;
}

.simple-table-header-color {
	background: rgb(247, 246, 243);
	color: black;
}
.simple-table-header {
	font-weight: 500;
}

time {
	opacity: 0.5;
}

.icon {
	display: inline-block;
	max-width: 1.2em;
	max-height: 1.2em;
	text-decoration: none;
	vertical-align: text-bottom;
	margin-right: 0.5em;
}

img.icon {
	border-radius: 3px;
}

.user-icon {
	width: 1.5em;
	height: 1.5em;
	border-radius: 100%;
	margin-right: 0.5rem;
}

.user-icon-inner {
	font-size: 0.8em;
}

.text-icon {
	border: 1px solid #000;
	text-align: center;
}

.page-cover-image {
	display: block;
	object-fit: cover;
	width: 100%;
	max-height: 30vh;
}

.page-header-icon {
	font-size: 3rem;
	margin-bottom: 1rem;
}

.page-header-icon-with-cover {
	margin-top: -0.72em;
	margin-left: 0.07em;
}

.page-header-icon img {
	border-radius: 3px;
}

.link-to-page {
	margin: 1em 0;
	padding: 0;
	border: none;
	font-weight: 500;
}

p > .user {
	opacity: 0.5;
}

td > .user,
td > time {
	white-space: nowrap;
}

input[type="checkbox"] {
	transform: scale(1.5);
	margin-right: 0.6em;
	vertical-align: middle;
}

p {
	margin-top: 0.5em;
	margin-bottom: 0.5em;
}

.image {
	border: none;
	margin: 1.5em 0;
	padding: 0;
	border-radius: 0;
	text-align: center;
}

.code,
code {
	background: rgba(135, 131, 120, 0.15);
	border-radius: 3px;
	padding: 0.2em 0.4em;
	border-radius: 3px;
	font-size: 85%;
	tab-size: 2;
}

code {
	color: #eb5757;
}

.code {
	padding: 1.5em 1em;
}

.code-wrap {
	white-space: pre-wrap;
	word-break: break-all;
}

.code > code {
	background: none;
	padding: 0;
	font-size: 100%;
	color: inherit;
}

blockquote {
	font-size: 1.25em;
	margin: 1em 0;
	padding-left: 1em;
	border-left: 3px solid rgb(55, 53, 47);
}

.bookmark {
	text-decoration: none;
	max-height: 8em;
	padding: 0;
	display: flex;
	width: 100%;
	align-items: stretch;
}

.bookmark-title {
	font-size: 0.85em;
	overflow: hidden;
	text-overflow: ellipsis;
	height: 1.75em;
	white-space: nowrap;
}

.bookmark-text {
	display: flex;
	flex-direction: column;
}

.bookmark-info {
	flex: 4 1 180px;
	padding: 12px 14px 14px;
	display: flex;
	flex-direction: column;
	justify-content: space-between;
}

.bookmark-image {
	width: 33%;
	flex: 1 1 180px;
	display: block;
	position: relative;
	object-fit: cover;
	border-radius: 1px;
}

.bookmark-description {
	color: rgba(55, 53, 47, 0.6);
	font-size: 0.75em;
	overflow: hidden;
	max-height: 4.5em;
	word-break: break-word;
}

.bookmark-href {
	font-size: 0.75em;
	margin-top: 0.25em;
}

.sans { font-family: ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol"; }
.code { font-family: "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace; }
.serif { font-family: Lyon-Text, Georgia, ui-serif, serif; }
.mono { font-family: iawriter-mono, Nitti, Menlo, Courier, monospace; }
.pdf .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK JP'; }
.pdf:lang(zh-CN) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK SC'; }
.pdf:lang(zh-TW) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK TC'; }
.pdf:lang(ko-KR) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK KR'; }
.pdf .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK JP'; }
.pdf:lang(zh-CN) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK SC'; }
.pdf:lang(zh-TW) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK TC'; }
.pdf:lang(ko-KR) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK KR'; }
.pdf .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK JP'; }
.pdf:lang(zh-CN) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK SC'; }
.pdf:lang(zh-TW) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK TC'; }
.pdf:lang(ko-KR) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK KR'; }
.pdf .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK JP'; }
.pdf:lang(zh-CN) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK SC'; }
.pdf:lang(zh-TW) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK TC'; }
.pdf:lang(ko-KR) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK KR'; }
.highlight-default {
	color: rgba(55, 53, 47, 1);
}
.highlight-gray {
	color: rgba(120, 119, 116, 1);
	fill: rgba(120, 119, 116, 1);
}
.highlight-brown {
	color: rgba(159, 107, 83, 1);
	fill: rgba(159, 107, 83, 1);
}
.highlight-orange {
	color: rgba(217, 115, 13, 1);
	fill: rgba(217, 115, 13, 1);
}
.highlight-yellow {
	color: rgba(203, 145, 47, 1);
	fill: rgba(203, 145, 47, 1);
}
.highlight-teal {
	color: rgba(68, 131, 97, 1);
	fill: rgba(68, 131, 97, 1);
}
.highlight-blue {
	color: rgba(51, 126, 169, 1);
	fill: rgba(51, 126, 169, 1);
}
.highlight-purple {
	color: rgba(144, 101, 176, 1);
	fill: rgba(144, 101, 176, 1);
}
.highlight-pink {
	color: rgba(193, 76, 138, 1);
	fill: rgba(193, 76, 138, 1);
}
.highlight-red {
	color: rgba(212, 76, 71, 1);
	fill: rgba(212, 76, 71, 1);
}
.highlight-gray_background {
	background: rgba(241, 241, 239, 1);
}
.highlight-brown_background {
	background: rgba(244, 238, 238, 1);
}
.highlight-orange_background {
	background: rgba(251, 236, 221, 1);
}
.highlight-yellow_background {
	background: rgba(251, 243, 219, 1);
}
.highlight-teal_background {
	background: rgba(237, 243, 236, 1);
}
.highlight-blue_background {
	background: rgba(231, 243, 248, 1);
}
.highlight-purple_background {
	background: rgba(244, 240, 247, 0.8);
}
.highlight-pink_background {
	background: rgba(249, 238, 243, 0.8);
}
.highlight-red_background {
	background: rgba(253, 235, 236, 1);
}
.block-color-default {
	color: inherit;
	fill: inherit;
}
.block-color-gray {
	color: rgba(120, 119, 116, 1);
	fill: rgba(120, 119, 116, 1);
}
.block-color-brown {
	color: rgba(159, 107, 83, 1);
	fill: rgba(159, 107, 83, 1);
}
.block-color-orange {
	color: rgba(217, 115, 13, 1);
	fill: rgba(217, 115, 13, 1);
}
.block-color-yellow {
	color: rgba(203, 145, 47, 1);
	fill: rgba(203, 145, 47, 1);
}
.block-color-teal {
	color: rgba(68, 131, 97, 1);
	fill: rgba(68, 131, 97, 1);
}
.block-color-blue {
	color: rgba(51, 126, 169, 1);
	fill: rgba(51, 126, 169, 1);
}
.block-color-purple {
	color: rgba(144, 101, 176, 1);
	fill: rgba(144, 101, 176, 1);
}
.block-color-pink {
	color: rgba(193, 76, 138, 1);
	fill: rgba(193, 76, 138, 1);
}
.block-color-red {
	color: rgba(212, 76, 71, 1);
	fill: rgba(212, 76, 71, 1);
}
.block-color-gray_background {
	background: rgba(241, 241, 239, 1);
}
.block-color-brown_background {
	background: rgba(244, 238, 238, 1);
}
.block-color-orange_background {
	background: rgba(251, 236, 221, 1);
}
.block-color-yellow_background {
	background: rgba(251, 243, 219, 1);
}
.block-color-teal_background {
	background: rgba(237, 243, 236, 1);
}
.block-color-blue_background {
	background: rgba(231, 243, 248, 1);
}
.block-color-purple_background {
	background: rgba(244, 240, 247, 0.8);
}
.block-color-pink_background {
	background: rgba(249, 238, 243, 0.8);
}
.block-color-red_background {
	background: rgba(253, 235, 236, 1);
}
.select-value-color-uiBlue { background-color: rgba(35, 131, 226, .07); }
.select-value-color-pink { background-color: rgba(245, 224, 233, 1); }
.select-value-color-purple { background-color: rgba(232, 222, 238, 1); }
.select-value-color-green { background-color: rgba(219, 237, 219, 1); }
.select-value-color-gray { background-color: rgba(227, 226, 224, 1); }
.select-value-color-transparentGray { background-color: rgba(227, 226, 224, 0); }
.select-value-color-translucentGray { background-color: rgba(255, 255, 255, 0.0375); }
.select-value-color-orange { background-color: rgba(250, 222, 201, 1); }
.select-value-color-brown { background-color: rgba(238, 224, 218, 1); }
.select-value-color-red { background-color: rgba(255, 226, 221, 1); }
.select-value-color-yellow { background-color: rgba(253, 236, 200, 1); }
.select-value-color-blue { background-color: rgba(211, 229, 239, 1); }
.select-value-color-pageGlass { background-color: undefined; }
.select-value-color-washGlass { background-color: undefined; }

.checkbox {
	display: inline-flex;
	vertical-align: text-bottom;
	width: 16;
	height: 16;
	background-size: 16px;
	margin-left: 2px;
	margin-right: 5px;
}

.checkbox-on {
	background-image: url("data:image/svg+xml;charset=UTF-8,%3Csvg%20width%3D%2216%22%20height%3D%2216%22%20viewBox%3D%220%200%2016%2016%22%20fill%3D%22none%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%0A%3Crect%20width%3D%2216%22%20height%3D%2216%22%20fill%3D%22%2358A9D7%22%2F%3E%0A%3Cpath%20d%3D%22M6.71429%2012.2852L14%204.9995L12.7143%203.71436L6.71429%209.71378L3.28571%206.2831L2%207.57092L6.71429%2012.2852Z%22%20fill%3D%22white%22%2F%3E%0A%3C%2Fsvg%3E");
}

.checkbox-off {
	background-image: url("data:image/svg+xml;charset=UTF-8,%3Csvg%20width%3D%2216%22%20height%3D%2216%22%20viewBox%3D%220%200%2016%2016%22%20fill%3D%22none%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%0A%3Crect%20x%3D%220.75%22%20y%3D%220.75%22%20width%3D%2214.5%22%20height%3D%2214.5%22%20fill%3D%22white%22%20stroke%3D%22%2336352F%22%20stroke-width%3D%221.5%22%2F%3E%0A%3C%2Fsvg%3E");
}
	
</style></head><body><article id="12c0ed98-06a7-43f1-a716-457f4916fa1a" class="page sans"><header><h1 class="page-title">codigo</h1><p class="page-description"></p></header><div class="page-body"><script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/prism.min.js" integrity="sha512-7Z9J3l1+EYfeaPKcGXu3MS/7T+w19WtKQY/n+xzmw4hZhJ9tyYmcUS+4QqAlzhicE5LAfMQSF3iFTK9bQdTxXg==" crossorigin="anonymous" referrerPolicy="no-referrer"></script><link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/themes/prism.min.css" integrity="sha512-tN7Ec6zAFaVSG3TpNAKtk4DOHNpSwKHxxrsiw4GHKESGPs5njn/0sMCUMl2svV4wo4BK/rCP7juYz+zx+l6oeQ==" crossorigin="anonymous" referrerPolicy="no-referrer"/><pre id="3a51b544-e7f1-41cd-8968-a441e20817aa" class="code"><code class="language-HTML">&lt;!--para darle estilo a un titulo o parrafo es tan sencillo com hacer lo siguiente--&gt;
&lt;h2 class=&quot;color-JohaLibrari-primary&quot;&gt;primary&lt;/h2&gt;

&lt;h2 class=&quot;color-JohaLibrari-white&quot;&gt;white&lt;/h2&gt;


&lt;h2 class=&quot;color-JohaLibrari-red&quot;&gt;red&lt;/h2&gt;

  &lt;h2 class=&quot;color-JohaLibrari-orange&quot;&gt;orange&lt;/h2&gt;</code></pre><p id="d189139d-202d-4e0e-b459-92482562a7a4" class="">
</p><script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/prism.min.js" integrity="sha512-7Z9J3l1+EYfeaPKcGXu3MS/7T+w19WtKQY/n+xzmw4hZhJ9tyYmcUS+4QqAlzhicE5LAfMQSF3iFTK9bQdTxXg==" crossorigin="anonymous" referrerPolicy="no-referrer"></script><link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/themes/prism.min.css" integrity="sha512-tN7Ec6zAFaVSG3TpNAKtk4DOHNpSwKHxxrsiw4GHKESGPs5njn/0sMCUMl2svV4wo4BK/rCP7juYz+zx+l6oeQ==" crossorigin="anonymous" referrerPolicy="no-referrer"/><pre id="cbadcc8b-d27c-4bf0-bba9-d73f0cf66af5" class="code"><code class="language-HTML">&lt;!--fuentes tipograficas--&gt;
 &lt;h2 class=&quot;playball-regular color-JohaLibrari-white&quot;&gt;JohaLibrari&lt;/h2&gt;
 
 &lt;h2 class=&quot;jacquard-12-regular color-JohaLibrari-white&quot;&gt;JohaLibrari&lt;/h2&gt;
  
  &lt;h2 class=&quot;freckle-face-regular color-JohaLibrari-white&quot;&gt;JohaLibrari&lt;/h2&gt;
   
  &lt;h2  class=&quot;hachi-maru-pop-regular color-JohaLibrari-white&quot;&gt;JohaLibrari&lt;/h2&gt;</code></pre><p id="688260a9-0fb9-471a-934f-661195bd093e" class="">
</p><script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/prism.min.js" integrity="sha512-7Z9J3l1+EYfeaPKcGXu3MS/7T+w19WtKQY/n+xzmw4hZhJ9tyYmcUS+4QqAlzhicE5LAfMQSF3iFTK9bQdTxXg==" crossorigin="anonymous" referrerPolicy="no-referrer"></script><link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/themes/prism.min.css" integrity="sha512-tN7Ec6zAFaVSG3TpNAKtk4DOHNpSwKHxxrsiw4GHKESGPs5njn/0sMCUMl2svV4wo4BK/rCP7juYz+zx+l6oeQ==" crossorigin="anonymous" referrerPolicy="no-referrer"/><pre id="d5c64acf-0328-4c3d-99a9-13dc9fee2ceb" class="code"><code class="language-HTML">&lt;!--textarea--&gt;
  &lt;label for=&quot;text&quot; class=&quot;color-JohaLibrari-white&quot;&gt;textarea&lt;/label&gt;
 &lt;textarea name=&quot;text&quot; id=&quot;&quot; placeholder=&quot;El texto aqui&quot; width:80px; height:20px; &gt;&lt;/textarea&gt;</code></pre><p id="948702b9-540b-4c76-92e5-7983ccaeffd3" class="">
</p><script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/prism.min.js" integrity="sha512-7Z9J3l1+EYfeaPKcGXu3MS/7T+w19WtKQY/n+xzmw4hZhJ9tyYmcUS+4QqAlzhicE5LAfMQSF3iFTK9bQdTxXg==" crossorigin="anonymous" referrerPolicy="no-referrer"></script><link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/themes/prism.min.css" integrity="sha512-tN7Ec6zAFaVSG3TpNAKtk4DOHNpSwKHxxrsiw4GHKESGPs5njn/0sMCUMl2svV4wo4BK/rCP7juYz+zx+l6oeQ==" crossorigin="anonymous" referrerPolicy="no-referrer"/><pre id="a9db3ba7-ca2e-4b32-883b-0acfd3d2aef7" class="code"><code class="language-HTML">&lt;!--los avatar--&gt;
&lt;img src=&quot;https://www.gravatar.com/avatar?s=15&quot; alt=&quot;&quot; class=&quot;avatar-mediano&quot;&gt;
&lt;img src=&quot;https://www.gravatar.com/avatar?s=15&quot; alt=&quot;&quot; class=&quot;avatar-grande&quot; &gt;
&lt;img src=&quot;https://www.gravatar.com/avatar?s=15&quot; alt=&quot;&quot;  class=&quot;avatar-rounded avatar-grande&quot;&gt;
&lt;img src=&quot;https://www.gravatar.com/avatar?s=15&quot; alt=&quot;&quot; class=&quot;avatar-pequeño&quot;&gt;</code></pre><p id="90cbfe97-0ba6-4c0a-9660-9709198e1861" class="">
</p><p id="b2f43f85-80dc-42e6-95f0-a353e6f0c95f" class="">
</p><script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/prism.min.js" integrity="sha512-7Z9J3l1+EYfeaPKcGXu3MS/7T+w19WtKQY/n+xzmw4hZhJ9tyYmcUS+4QqAlzhicE5LAfMQSF3iFTK9bQdTxXg==" crossorigin="anonymous" referrerPolicy="no-referrer"></script><link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/themes/prism.min.css" integrity="sha512-tN7Ec6zAFaVSG3TpNAKtk4DOHNpSwKHxxrsiw4GHKESGPs5njn/0sMCUMl2svV4wo4BK/rCP7juYz+zx+l6oeQ==" crossorigin="anonymous" referrerPolicy="no-referrer"/><pre id="931207c1-15eb-46c3-98ec-aa5030cb5e19" class="code"><code class="language-HTML">&lt;!--los iconos--&gt;
       &lt;img src=&quot;data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADUAAAA1CAYAAADh5qNwAAAAAXNSR0IArs4c6QAABGNJREFUaEPtmVuIG2UUx/9nknZbvKAPMflms5rJVooXCoqKFIUKIl5AfdIniy/SVSlaKwXxgor2QWldakW77oJYROyLgoLUPkixUKRVwVKq7ZrEZjsndWt3K8USO5ljZ81uk2ySuW3S7TrzOHPO+c7v3L7vYwgL8KEFyIQI6mLJasczldP1e2DbKY1oX4b5UDcC0w2orSTy9BQM0ftxTVvfNzZ2ppNw3YB6j0SeqoH4psD8wF2A1SmwCwEFAdZkmYcWFBRE9hql0sqLGep8T7lT/CPAPhLZZZfLg/0TE6fcVWZLdKP8/EDVejghIgPZUmmHX7BuQDUOCj8+iog8ni2VPvajNN+hHBapDpYPvYI1hcorNSDA3SRygCxrKHPiBHs12CiX03XX8iPgtADDINotwB0k8gSAy2ttEbBHgMr0OwLO2sBu27aHlh0//keDbL0b+VRqFYi+nX4rwOYs8/oQUK7lR8BwhtkBmXpyuu6qUwP3Rob55bZQBV1/XURqhQ4bzMtDQLlmSoDVWebtM1Cp1CNE9JmXNQnYn2G+tX2mlHoWwDs1QlJgXhz0BOAl6mEyBeAXg/m69lC6/jBEPq8TErk/Uyp97SVyQXvKJtrm9A0BK51RDuAyj+sdMpivbwt1JJVKxInqGg9AET09K4xCYdLjQjNiOaU2EfCcXz3P8kQ7DNN8tC2U8zGv1BcAHmowfJREBmLx+Pd9Y2MnvS6aU+oxAnztM15tO3JC9GDWNL90hcrp+nIS+RnAYj8L1MkSvWaY5qu/pdPXapXK4cB22itO/MmcvAU46wpVzda6c3vF5hDO/GQw31y15WT2yhC2WqkOGsyOn/XxbLdQXql1ArxFQDyIQ7F4vPfqYtHMK/XCuaxvDGKjjc4kenqMZn3uekzKK3UvgECTD8AHBvOTAmgFpb4DMGfXDSFamzXNrc2gXaFySl1DQCFolG2iO/tNc08hmTRE0xyw3qC2qnp/CfC8wTxMcO6bs5+OQwH4/W/LuvGG8fHT+UQihVhsJ4hWBAArA/ioYtuvNJ71fPWUIxw2U1MLiuy1y+X7nEvfwUTi0ksWLdogImsBXOEBztlKtsiSJSNe98luZGra719hWauM8fGS86KYTi+1KpXVAJ4BUHfMqSrsEqJ3DdP8qlWZtQpIN6EcHyYF2HTGsgadcpx2Kp9M3k6a5gyRm2yiU0K0pf/YscB7myvUqK73xUSOeigTPyInITJsx2IjYZwPnKkOQc34I8APGvCjTXRAiHbOBaRrpuZkUHjMoQAbs8wvehRvKRZBhY2gm36UqTYRisrPrXzCfu9a+bmM9KJzkvIJsxTAbc10BHgzy/yST3uzxEOVHxG9nTHNDX6cGE2nl8UqlSMtoC78SI+gqqmJMuWnrmtko56adcOMBsV/IYl6Kuqp8xH4fw6K0WTyqpimtfpD/qnBvM1PlRTT6V6rUvmkmQ4Rbc+Y5ogfe03thDUwH/Vdy28+Ou3mUwTlFqH58v1fklJRVJMIegQAAAAASUVORK5CYII=&quot;/&gt;
       &lt;img src=&quot;data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADUAAAA1CAYAAADh5qNwAAAAAXNSR0IArs4c6QAABGNJREFUaEPtmVuIG2UUx/9nknZbvKAPMflms5rJVooXCoqKFIUKIl5AfdIniy/SVSlaKwXxgor2QWldakW77oJYROyLgoLUPkixUKRVwVKq7ZrEZjsndWt3K8USO5ljZ81uk2ySuW3S7TrzOHPO+c7v3L7vYwgL8KEFyIQI6mLJasczldP1e2DbKY1oX4b5UDcC0w2orSTy9BQM0ftxTVvfNzZ2ppNw3YB6j0SeqoH4psD8wF2A1SmwCwEFAdZkmYcWFBRE9hql0sqLGep8T7lT/CPAPhLZZZfLg/0TE6fcVWZLdKP8/EDVejghIgPZUmmHX7BuQDUOCj8+iog8ni2VPvajNN+hHBapDpYPvYI1hcorNSDA3SRygCxrKHPiBHs12CiX03XX8iPgtADDINotwB0k8gSAy2ttEbBHgMr0OwLO2sBu27aHlh0//keDbL0b+VRqFYi+nX4rwOYs8/oQUK7lR8BwhtkBmXpyuu6qUwP3Rob55bZQBV1/XURqhQ4bzMtDQLlmSoDVWebtM1Cp1CNE9JmXNQnYn2G+tX2mlHoWwDs1QlJgXhz0BOAl6mEyBeAXg/m69lC6/jBEPq8TErk/Uyp97SVyQXvKJtrm9A0BK51RDuAyj+sdMpivbwt1JJVKxInqGg9AET09K4xCYdLjQjNiOaU2EfCcXz3P8kQ7DNN8tC2U8zGv1BcAHmowfJREBmLx+Pd9Y2MnvS6aU+oxAnztM15tO3JC9GDWNL90hcrp+nIS+RnAYj8L1MkSvWaY5qu/pdPXapXK4cB22itO/MmcvAU46wpVzda6c3vF5hDO/GQw31y15WT2yhC2WqkOGsyOn/XxbLdQXql1ArxFQDyIQ7F4vPfqYtHMK/XCuaxvDGKjjc4kenqMZn3uekzKK3UvgECTD8AHBvOTAmgFpb4DMGfXDSFamzXNrc2gXaFySl1DQCFolG2iO/tNc08hmTRE0xyw3qC2qnp/CfC8wTxMcO6bs5+OQwH4/W/LuvGG8fHT+UQihVhsJ4hWBAArA/ioYtuvNJ71fPWUIxw2U1MLiuy1y+X7nEvfwUTi0ksWLdogImsBXOEBztlKtsiSJSNe98luZGra719hWauM8fGS86KYTi+1KpXVAJ4BUHfMqSrsEqJ3DdP8qlWZtQpIN6EcHyYF2HTGsgadcpx2Kp9M3k6a5gyRm2yiU0K0pf/YscB7myvUqK73xUSOeigTPyInITJsx2IjYZwPnKkOQc34I8APGvCjTXRAiHbOBaRrpuZkUHjMoQAbs8wvehRvKRZBhY2gm36UqTYRisrPrXzCfu9a+bmM9KJzkvIJsxTAbc10BHgzy/yST3uzxEOVHxG9nTHNDX6cGE2nl8UqlSMtoC78SI+gqqmJMuWnrmtko56adcOMBsV/IYl6Kuqp8xH4fw6K0WTyqpimtfpD/qnBvM1PlRTT6V6rUvmkmQ4Rbc+Y5ogfe03thDUwH/Vdy28+Ou3mUwTlFqH58v1fklJRVJMIegQAAAAASUVORK5CYII=&quot;/&gt;
       &lt;img src=&quot;data:image/png;base64,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&quot;/&gt;
       &lt;img src=&quot;data:image/png;base64,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&quot;/&gt;
        &lt;img src=&quot;data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADUAAAA1CAYAAADh5qNwAAAAAXNSR0IArs4c6QAACENJREFUaEPtWX2MXFUV/503s7tsu/NmKRRq23lvW6gRsKI26c6btmFtq5VGIip+kIgUv1IEtFZB1CqoIYZSvoySlJpIFQ22immtbcEWaj/mzbaWNlVBQdqdNxtwKZSdN/vV3X3vyJ3OvHkzOx9vZmf/gOxNNtl5957fub9z7sc55xLegY3egZwwSert4tVJT016KmOB1u7I+8F2q/hps9QPsnptf2Nv37sOnJ4oI9V9+bXEF10hgZeBeCmADgDBMpM/wITNBPzJDOln6kWybqSCRvj7DLoNwMU1Tm6bRfhBf0j/R43yjti4SQXjketY4g1gqOOdjJBnwh8gSetSsw79p1a8mklN626fPWrRRhCtHKOcECfGVjB2W0Q9tu17Y6DtwKvTXmqXrcaGC5nsCxg8n4BPA/hoicnfair6L2ohVhOpQDx8DYF+C0KgQOkWYnt9Uu086nUy57+8IGg1NHwRoB8CSB8o2cbMm1Jq7KtesbLjqiYlxyM3gPjXbkUE7Ccba3rb9GPVTiA7XnhxpEm6k4Dv5mPQwRb/2RWvzDw64BW7KlLBeHg5E+0G4MspoAfMUPR2EGyvSsuNy+jYBmCKS8d2MxS9FgT2osMzqWB88VyGdTxvyRHdYIaij3tRVM0YcbfZFj8FwkW5tYgfm6p+lxcc76QM7QQD813Wu8VUoo94UVLLmJau8GWSREcATM3tFf5cUon9vhKeJ1JyInwbmH7mAttsKvqqSuDj7ZcNbQWAnQCkDFafZDWFeufs6y2HXZHU9Nc6Ws4One0CcEEG6AVT0S8vBG15dcl0adi6HsA0iXnbeA4NN7Yc174BwkO5ZUg/MtXo3eMiFTC0bxNwnwNi08fMtuhf3KCB7oXvJtunC0Lp74R/myH9svF6KisvG2EdoHD6NyNF8KlJ9eCbpfAreipoaN0MzDo3V/wtqeginstrshE5APBi90dJkpb2zj70bD2IyYlFK8G2Y0hirE6q+saaSGWO179mhRl0bUqJiuPWacGuhXNY8p0co4DwGzOkf6EepASG27gg7DBD+jU1kZIN7QEA38wKNzf2t/TMONGft+YLrOjus0btGf1zO3vqQUw2tJ8DuCWzYgaTiu66x/I1lF1+sqH9HcCCjMguU9HHxHmBhPYJYjxZfOJ0valEn6gHqWBXZClLvNfBIl5phmK7imFXIuXc4MT4XlLVf1oI0hJvv1wi6V9FwM80Nkttr08/lKoHqQtPLwoMD9pmFouY7kyq0XurIpWOIMh62RFi3Giqel7Ml+2TDU3sqTmOQmCQCR1mSD9cD0IuPa9nrxZiWp9Uo9+pitTUhDbfxziRmyitSCrRp4uBBIzwWgLdn+1joDtlNc3DnH1D9SQVMMLHCXSlwCwXwZdcfmOWFaG9pOVPdZwn+4ZfBDiUI0H3mEp0XT1JyYYmoourM5hbTEX/bFWeak5osxoY3VkhifhTvaFYiQMBaDEi75XAeak4s70kpXYerBexvEsY9JipRG+qitTF/3vf1MHhqX3OkiLckQrpuciiCJoc19aA8KCrq5fYXl5N0ljOAAFDSxAwOzPmIVPRnevGLVfp9HM2JgMbU4q+upLVZUPbDMB96faDaHWxFEVOaDvAFGTme1OqvsMDtiufopJZQllSgXj4GSL6UEbZHlPRP1xJseiXDe13AERw6zo88aRl+28VtYr0mHjkbhDn8iPG8bcChwdNCVsR0gcL9QSMRUsI9v7sdxt0VZ8SdX5X4anI/QCvzQgM+EaGZ755ydGkN2KRJwAu3MhDAP0KQDPApVKXw6aitxfqCMa19Uy4PfvdtJqaS52uZT1VGPuBscZU9Ye9kMp4TOyvNV7HZ8YdMhU9LzhOYyW0F8B4j/ifGc+kVH1ZKdyKUbpsaKJyen4G4L+mos+rZpKBePtiIulRAJ5SEWLcl1T1O9w6gnFtGRP2ZL8x86qUGhN7t2irSCpohDcw6FuONOFqM6SL4ktVLZAIfxlMd7lOr7HyhGP+IbvjzLxOJxwSg9yXLoA3TEKo2L7LAlYkJTJa38honNP7IJ1T7U8q+lVVMXINDhjhVUT0dTA+4Fge6CbCphbf8IbCUpgwBjFtyk2Y1yWV2D3l9FckJYSDhvZLBr6UARowFd0phtRKrvVUuA1+tNHwyLFSh08mVIu5ymU9Tec1XXr6on3O/VlMvydS+Tc5iqYgtZIrJScnNFEaeM5do2fwTSkl9lglXRVJnSsLN7qqN7zWVGLuqKGSjqr700WckVFxGS90lihhayqkf8YLWEVSrYnwJ22mP2bBbND8PiX6Ty/gtYwJdoU/yBL9GcDMnDzHmhsHlhdm3aXwK5KSjcgjAN+cAegxFX2GGyz9yCZZS22b9/apnc/XQkTIzHxlwZS+0aa1AP8kD4Owt7mh/+NeCWUOs/LTkA3tJQCXpkcxP944xfe1s0P2csmmlUz8EQCKs0SYnxU1upQS2+6VnHgYGG3yff6t2peo5U0vkKupaFrWU60nI6rtZ1HIzDZRRPHyUngKxJvZxnMSSc8nlWgugwYgvEuSHSbGdaXep9hDVlDT8gsmIl9hZhENjKuRSO8BUccQVV4n7S8BeoTYvnk86Ur5KD2hbSFOv/aNbYQogKeIpZ0+33DPqOUXAar4m1ujBXaD8HAt0Uqhvkr5lCjtnnvdY7wGop0EezfY/3Spsm9rItxhs3RjpmJ7bi+WbCwu1j1+n/XomVlHEjUaY4xYSVKt3YuvtG1rI4G3k027ai34iycZIrpEAl0BcC9gn7R9HE/NPvxivUhU5amJUjrRuBXvqYmewETgT5KaCKtOBOakpybCqhOB+X8tbApjWrgh4wAAAABJRU5ErkJggg==&quot;/&gt;
        &lt;img src=&quot;data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADUAAAA1CAYAAADh5qNwAAAAAXNSR0IArs4c6QAABL9JREFUaEPtWV1oHFUU/s7sVtRkZ7c+VJqdudNY8CGpVm3VhyqxVFGRolKlQvGvQhUqVqqCCIYWBR9U1BYU/0iVguhD/YsgWKRq8UFTbDU+iBizd+5G7YNmZ2sRzM6RCElmNo1zdjbbYNh5nPm+e77vnPs/hEX40CL0hLap/0tV25VqV2oBM9DufpLku7beziENZ7MTx0bHu8clnClMV660LmORQzUe1ie87xvhRrHzWinVWeoJLYqK+dVivlVXvcMSgUVbDxBw1wyWBk3gbpRwW2bKsf0tAO+Pi6DzTeD+KBHm5PQxEC6MYN83gbpJwm2ZqWJeP0OMhyIBTppAdUhErcHQkt/sZX8BsGbwvNsE3i4Jv2WmHNs/CPCGSPf50gTuOomo5fnRSzJsHYmJY9zsV9V7En4LTek/ABSmAjDwYjlQ2yWinJx/D4hfi2KzVq17dLx7VMJviamuc8quNVHTMQFE20zFfVUiyrH1XgD3R7DjJlBLJdx6zLzNfl250kaL6IO6jF3mB+pribCirb8g4IppLOEzU1FXSbgtM+XYfj/AuyMBwnOD42cewdq/JcIcW/8J4OzIeHzBBO6DEm4qU07BT85YLewH0frpAAyDDN0uEcUcLiOmt6NYJjxLRINz8cOa9ctYtfjDqb4ndr/lhREvE2YbHqwSM81gmDBQrqitbVNTGWhXqpn+1CC3qe43GStxogj5UQDXzuji47CszRKdVOMCE96NY2kPrPp3cURTE4VEWNHWQwSsiWA/NoG6XsQtmPUUhp/GZ75wQ7myIvZO0tYUJnH2S26MLcf2JzeiS6YbZTzlV9VjyVzAzemdk9N3FJu1aksbPYtF+U2bcjr8C5Dhb+OZ5s3liveOxJRj+28CHF3PtAmUJ+HOhWnaVNEu3UGgN+rGhPwMldffgbEqwk91hprXSrm2fo6B6HamyTMU7TKBG91uNVy0pivl5PUhMPqmIjNwuByoKyVKXFtfysBXsSwzbvSrKrYxlrQ1r5WavRHlvSbwHpAIKeZL24jp5Sg2zGbU2O9FX8JvyZhS+dJ5IdNPdZne6lfVgESUa+uXGLgvgk19hhJVyrX1bQy8JRF3OjFMfG+54r3yXzHnHFNtU6exVO1K1Sfb7dSr2OJb5ioCg3IE7KxbdD8CwiFZ4eg6AJfHsbHrgFM2YxE+1BUvdpVWD0y9Tjmdfh8sPhSbjomvGat4ByWmHNsfBPiGGSwfNYF3sYSbhElvyi7tAOj5aIBGNqJOXhswipFFe185UHcnCZZ8T21q1mU+w5iqciVBVxR+LkyEmcmLz8jDO0zg7ZHwkzCpTTl26RuALpoJIP9D0ZUvXW0xfRJbMEP0+SfU50mCJd9Tmpp9hmLgiXKg+iVB3Zx+mAlPx8ZjZ7ZjbKzrpISfhEllqlgwqykMj8Yat2iTGXcPJAWc/O7Ypf0AbYlgR0ygVkq4Ekw6U7nSnUS0LxrAIl6pK96IJKhj62EAvdNYxgFTVZskXAkmlan5PkMR8LgfqCclgiWYVKYmG3bzem0Yci9Z6AHIMhX1iCTgv93vLL9onRH2cEirQ0Jvhvl16S9USYzUpiSNLxSmbWqhMt9o3HalGs3YQuHblVqozDcad1FW6h9TfcRF4PTPnQAAAABJRU5ErkJggg==&quot;/&gt;
        &lt;img src=&quot;data:image/png;base64,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&quot;/&gt;
        &lt;img src=&quot;data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADUAAAA1CAYAAADh5qNwAAAAAXNSR0IArs4c6QAABOdJREFUaEPtWV1sFFUU/s50myYsO6NFsWk7s1XgBXxBE0jEmW0oPogxoPEv/iSKGo1/vKjBBAVN0GA08Qd/HhQSE8WQmKoxEpXidtaIPJCYGHmpVXaWFnigYe/SxrW7e3TapS3t7t67dHdbm72v5zvnft89d86cey9hAQ5agJpQF/V/yWo9U/VMzeEK1LffHC5+WVMXzZRn6/eAsL+saHlwDryuw039LPPlTgQSOf00gCUy7Aw70z4rltxSyK8aoo5brlilStKLhF4F0wuq+AlcLUUR+BHTTX2sSnLAaTazyJwAoKn6jOFqKEqkg2LpioNIl0PQixjdYN5cjk8NRdGblpt8tixyAOKdxgbK8Q9l+dUoU9yAQLjNHUqURS4P9mz9DxCWKfvWSNRByxUblUlNA8Yj+jPEeFvZvxaiCLjFdMW3yqSmAfvWNutNTZlTABYpxaiBqITpijABrESoCMhz9A8APK4Uo/qi+DnLTb2hRKYEKG4vXkmk/a4Up8qi0ul0YOmKo0NCiYwE5DlGL8CONFZ1RdFey00+LCWhCIhHjDuJ+YAUXk1RzLlV4dj541ISioB8P+j/FlpKulRLFANHwq64QYVv3NG3Wq54R6WYJBx9x38VZ+eciCLgftMVn8pEDV7fuigTPH8KjLusmPhOhv+rM9jSkGvwsxUoiq1Sps6ammihKDIykl5EfwKM94jwjdkrbpXhfbvn6J8DuLvWonZZrtiuRHCyBVJupbxIyAaTW0tRuayWbbs6Ouwf8EqOuG10EfGhSZB60+s5uv/PWllwgspvP+q23OTtMkH5bfQlgE1TsMrHk7hjPEbgD2siKgfq6nCTh2Wiih0AiflRM5b6SOY/UWAAfQa2opli9FsxsVxGyLfHbWM3ET9fAKt85E84+lsMbK2qKGI8bcbEHpmovpvR1DSsDwJoLoRlje1wNPWTLI633liGDPcB0+79K5ipkcDw4itbjw2OSMk4oS0AlbqrOGC5onjJnjKB5+jfA7jpojkrKOp9yxVPygTlC0TxyjUeIJNpzLZf0zN8RhbPs0ObQOQXnMlRMVEBWm4dTvbLSMTt0Doikm4tZrwSjokdsngMaAlH92+czAlsJUQx+Mewm1ovI5DPUuluYDLIGVMT7SpdSdwxthH4tYqKIqY7zFjyC5moP7uCVwVGG06W7NumBCHgPtMVn8ninuwKLcmN0gCApjFsBTJ12nRFGwE52eRxW3+ZCC/JcBfs5XT6CVv/hAkPVEgUbbfc5C4Voiecy1Y3aDAKlnHO7QFjxpW0pmmr26PnfpXFT9j6GiYcHccVP5yq3KVntEZuae9JnZVNKrMnbP0pJrw7A1diK03Heo5+DMB1s9t+jP1WTNwrI6xi799wudH4T9Yv4ePfxeRI0yhazSNiSBbHs0MPgmjfrESpPsvIyFywe7axF8QPTcczaFvYTe6Wxcl3KgNg+vpSn3JeLOdZRkbItydu1Neyhl8KYP27ww6lYhQxXqccrrgkUUQcLOdZRkWUj/Ec4zeAr535bfFmK5b6ShZnvPvP7ix2i1W0UCQcfePfQdFT7rOMjNCYqPzxfqYoHLJi4uIer0jARCR0m9mb6i5knpOHbP+clA2NrClEyIyei6osTCnMnIiaLWmZf12UbIXmi72eqfmSCRmPeqZkKzRf7AsyU/8CUOtdVNZumFcAAAAASUVORK5CYII=&quot;/&gt;
        &lt;img src=&quot;data:image/png;base64,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&quot;/&gt;
        &lt;img src=&quot;data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADUAAAA1CAYAAADh5qNwAAAAAXNSR0IArs4c6QAAA2dJREFUaEPtms1LFHEYx7/PrK/YjmAECrurQlBSUQcvEhKIUREleVhGjQ7RC9Qh/AeC/oCiUxEUXap1NxKkQ50serMOdVKJjLRdocyKdtQy1/09taax6jozzszOoMwed57n+T6f5/vszPLbJazDF61DJnhQa8XVVTt1p3ykiVjaDbDPEUhCf6qk+MGxscopo3qGoWIYKGLZ38PAfqPF7YojxqjwpRvbftSOGKlpCMpNoAWIDFiqUGo4+j0wqgemC/UIXPBFTtx3w6EczY/MFkiNemCaUPNA9xg4rDcdB6/rgq0IpQnEdDc5MdZxGvWpfMJE/fHjTLgOLHv0jEjpdEN4qvZzLv2cUDGwj+VE9woOXVXU0Jl8wmTX7vLHW0CIAiheovleSqcbc4HlhIrI8SgBYacat6AzVMRSQ+tE4Ft2jWVQETnRTuDbFoScTSXcUJKhE5pQUTl+iYFOZzuzoEboV5KhHZpQXXLiMsDnLMg4nEpvFTVY50E5PHYTcp5TJobmSornlCtjNyHqOWViaFkpRHRKEIa0qpDgHgCyNSUMKmpomyPPKYm4Ppysfq3VcESOfyVgozUoB9fPg7JkleeUpfFhLa/fOBMGc+ELppMdalDz7heV4z2CUL40n5grAdpicKy23/1mBehQuxp8aLAB3bBbFaOBwpTo+3s2EdANngvIz2dqRoBa7ADLABXMiqcAaowB5Q8qU3lGkDjQnqzpNd7M4khzQPmFylSfFiQOmgGLlQ1XCp+vb3UOLQwlP+uXPfJpiXlveKL6mVHH5oEyK7fZaM7iuPxDZfR+Ssz7jIDFNnzaJKTUC/NA+V+/7AHqgv0Dmn0C8FZzDjm3fovAGNTUpgZfLW3aPiBnnVrgmGRQczZYTE5UCOC5dYfcceo/GEjsUZI1b+aAiB+DsejwcS2tX3avSUGiVWK6CNAuaxDLsgcUNbQ9+91lZ+neCa3NIzdXztBz6uMFgM6bE3Al66Wihho01y/iTxwh4m5X2jMnekVRQ2c1oWJIlLKf3xn/6m+uE5uy0kLwzvbJ6gFNqMzFiD/eKBGiDFTZJG5/GcIvgDuVZPW1pcVX/CH7JoZLSv1SMyDVMYky+7syV1Ei/BagD750YW94smo8VxXd/1GYk3Y3y4Nyd/7G1T2njM/K3ch16dQf74XSRYQbKUYAAAAASUVORK5CYII=&quot;/&gt;
        &lt;img src=&quot;data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADUAAAA1CAYAAADh5qNwAAAAAXNSR0IArs4c6QAABcVJREFUaEPtWWtsFFUU/s5sbWeWUunOnQViSGwUDVYlPtCIQsBQTQgPFUzwFTUi4ismKAEMCf5BJaA/FBU0qD98YUQFBRRDkIiGCBhiIBgf+IhB6NypLdCdKXTn2BHBbTvP3Y0byZ5kf91zvu9899x759y7hNPQ6DTUhKqo/0tVq5WqVqqCM1BdfhWc/ETUZatUW1vXxa7rTgLg/bqE0MYnyiTCua2Nz2S2JwA0nRljAPdGIQbs8AsrSZRpOucrCs9hxnQAmUIC11UHZrN0tFRhpunMIuJ7AVxeiMXMcw0jvaxsoiwrN4xZeQ7gG4KSVhSamMmoG4sVJWXuCoBWAbjQN3HCel3XvFXRzxJXyjSdyUT8FoD6sISJaJmuq3OTirIsbmB2ngZwf0TsESG0hpJFSWnPB/BUjET3MNN8w1DXx/A95SJl1wjA3QDg7Ii4HDO9fPRo3YKmJnL6+saulJT2qwDuDifjdYpCSzMZbVsSMZ6vadrjibAWwMCQ2FZmLATUdwyDjgT5xRIlpf0agLtCyExmfsQw0m8nFeP5W1buKmb6KiJ2BZE6T9fpcBRHpCjTzD3q7Y8QoL3MbothDPgjisxvXMrcWcy0mwgiJP4OIbQ34uKHijLNzsuIlJ3BYLRGCNU7zos2Ke0vAYwOAOhw3fy4bLZ+dxKCUFFS2tsBXOkHyIyf29vVEcOHU1cSwkJf07RvI0JIBXiaEOn3k+IHijJNZxIRfxQEyExTDEMNHI9KhJkVy3J+CjnpPhNCuy4Kx288UJRl2VuZMTagShsNQ5tYDOHJGMvK3cxM7wZhuC4Nz2bVH4vh8BXV2uqcqyj8QxCgovA1mUza2wtFm5T2JgAtAZO22jC0GcWC+4qyLHsRM54IAd3qNa0AdhHxN4pCOxobtV/jJnHw4JFsTU3NoRB/b1n+DmA/QDuB/I6g5jX28pPS9rrfXg1kjIQ3p1K4J444Ke07e/bS6zEwC1y4nYjm6LrmfTNDrV+lmPkMy3K81kOJCvYZt5l5UU9P9iwR5YPiLcteyYxZReB7IVvyeZo5eLC6Pyi+n6i2ttzVrkuJ25xCAmasMgxtZhCpaeZ2E9HIIkUB4HbXdUdks/UHYy0/KZ0HAH6heMITkcx8a1DbJKXNpeIT4Qtd13xP536VktJ+sucQWFAqKYBcKoXmxkbtl0Isry0CyDsEymGLhdAW9gXyE+VtYG8jl2xEWKnr2uzeojpHAcrXJYP/A2DbanrYMLIL8XxEOe8BPK0cpETYr+vaOYVYpmmPI8KWcuB7GH43bB9RubUATSkXaSqFpsIlaFlOCzN7H96yGBE9o+vqY/9ZpTwiIp6h6+nVJ0nLXSlmbDMMbUyoKNO0XyFC4HGcdHqJ6HpdV09V5tChYyNTqXyiq0Q4J68TIj01olL2YgCPJ00+2F+5QIi6ff9WqnMokXKgfPj8ohDpB0NFtbbaYxUFXm9XFuvuVuuHDKHO3ieg/S2Ai8pCAJ4vRHpJqChvUEp7D4DmMpBuFkKb0BfHNJ37iHhFGfBdQGkWou67SFGm6cwm4pdKJWV2RxnGgH7PAQcOcLq21jEBpEvkeFMI7fa+GL5Xj/KQ8sdCpCcHJS1l7nmAHipBVD6fp/P8GtvAm6+UXVMB98MiSQ8TKaN1vW5vULz34O+6XVsAvqQ4DloihOo9rvaziNckZwoRrwFQk4D4N2ZqMQz1+6iYjo6OzPHjtZ8nPDR6bjc8zzDSS4PwI9/9WludiUS8nAhNUUkC2F5be3xyQ0ODjOH7t4snrLu7djkzbokXwzcJkf4gzDdS1Mlgy8pNY6aHAVza+2mYdgH8CRFv0PV01CtrYC7euwgRe8vp2j4TaAH4lIjXpVLHNg0aNOjPKPGxRRUCnfgrB0OZtX1hb9pR5EHjJw6qXHMqpZh9ry5xMIsSFQe4kj5VUZWc/STc1Uolma1K+lYrVcnZT8JdrVSS2aqk72lZqb8Adm4VVHVSEuoAAAAASUVORK5CYII=&quot;/&gt;
        &lt;img src=&quot;data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADUAAAA1CAYAAADh5qNwAAAAAXNSR0IArs4c6QAABHFJREFUaEPtmF9oHFUUxr+zu0lbo1I1NTtLks7cTUyIBiFWkUorCj5YUYogFLQPihYUKgjqg9QXRfyLL/5DKigqPvgiSGsfq4I+qBG0tDYke+/ExJ1NiCg0ITHJzpGJCcRNdufMbmbThp3X/c453++cu3fmXsIWfGgLMqEBdalMtTGpxqQ2sQON5bfS/F19k5enZqevaUkWCyMj3f9s4lDWLR1pUpmsOciMpwDsX8lG4JPMeM0z6tuLBU4Mlc66zxPzC2WNMz3mGfuDiwFMBLU8oS9CDScWb/JGun8O1cUsEEFZynyzesmV80TAR3ntPByz59D0oVBLm8LczIXQTEsC+sPTdrtMG58qFMpy9G4QuRILDCwUtNMs0capCYXq6hreNuOn5oQmjKcdJdG2t4/t8Jvnd+V19neJPoomFCpIllH6BIPuCUvMRG8VcvaTYbrg97QyrxCj1zPOQYk+ikYEZTl6P4iCzaLCQ9Psc3/BdUKXasbRPSA6w0ATEx0o5OxTUUyHaUVQQRLLcR8F8fH1E9I0A4cK2j4ZVnAplzLfAdi7rB1Lzqd6xsc7ZiWxEo0YaslM1/AA+amjDLqLwdcSMM5EJ1DkNyUT+q85+iEQfVJi7mVPO89JDEs0kaAkCStpWnvOX9G0sF0D3LpaR8ACmPvzRg3VWiOIrytURul3GPREGePfe9q57ZKCalO5/gQSv1RsJPNhz6hPawWr06SYLDX6A8B7QnbQqYWmOTU11Cv8gimzbdXaFUl8WpnHCXhXoiXgvbx2yi1RSYr4/1OZ64ZaebF5GMBOkSOAAf8WT2d/EurXyGJfflbW/RjMhyMaPONp+0aAOGLckjxWqEzW3cvMwYs28kPMR/NGvR05sFaotrZCy8REeqZcYUuZ8wB6qjEG4EKRuXvSqImo8VVPqrNz9KrFlP/jfJH2TY3aXmnhTNY8y4xXoxoq0X/maefBqDmqhkor8yUB94LxtWecO1YXzmRHOpiTwdfBjqiGSvVMdGchZ5+OkqcqKCurj4Dp/ZVCpevfUia4z9iYIwVDe1f/2YvBPQtSsMhQbd2jKlH0zwLYvqrIXDGRvGFypDOXzrp3E/NXUgMiHdMxz9gvibTVbBSWMoMABtYW4MHkfNO+YvNisOw6pAakOqJiZz7XNSbRR5qU5bgvgvhYhcTnAPRJClehOeVp54AkTgzVZptbEwkE75yEJHEsGqL7vZwdev8oggreR4mW2d/iWFYR4QvJ+ZQKOyWLoKr81InoVyYnojfyOfuZSupQqLSjHyCiz2Ul66IqEvP1lU7JFaFad7tWU5KDT50r62JXXqTiKbkCFJOVdU+Dcbu8Vv2UBDyS186H61UsC5V29NNE9Hr9bEatRFPbfO52Xefv0sh1oZbvE4JD2qbfi1dEJTru5ewjoVB9fWeb/5q77NcajgxRW16j3r+59JS8ZlJWlztAPt9XY6W6hfvM5wpG/W93Dt3S6+ZuAws1oDawmbGmakwq1vZuYPLGpDawmbGm2pKT+heO02hFciBgKAAAAABJRU5ErkJggg==&quot;/&gt;
        &lt;img src=&quot;data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADUAAAA1CAYAAADh5qNwAAAAAXNSR0IArs4c6QAABIBJREFUaEPtmV9oHFUUxr8zs8E/0RdRd2bj4s5uUwWRKqS16IMUKtaX1p3E9Q8qKgqK0qpU+yKK4ENtHyItUvHFBwsVYSatLdU+CIoUrG0fahEqbTKrbHY2FpViSiDZmSOjG9lq5t47m826XTKv893vnN+5d869M0PowYt6kAnLUJfLrHZ0pjLuxH1guieuODNBOPp7qXBhscXrMFR5B4Nfi0taD8OVlZHC2Z6CIuDRqm190lNQTLS7Vsxt7ikogE/6dn6ox6AAhOFqf6RwYjFgXdUoGiCn/XruTpQoaBWsG6Eilld92xrtNahZMLb5w9Z7rYB1dKYMx3uXCK+rJkqgQ0EKm6c25jzVMZGuq6GaQH4g0OdE9MXs3PSx86XbpkWQHYXKuOIThfpsiFv/MpR6JRdWLs+UsIJdtPxk3Y8Yexh4EoR+8aroMJThjK+GpvWDwTXb+ro5ORlUdESaI30ypfEoMR6OB1tCqLR77kYd+tMMrAFwO4DB5kR827qkEalAzZ/7bvjUM1J9/CyYSg3vJuslgBoY8+4IGa8gWiqC699Q0kYRc5jNHvg5Uw+CjcQwonCscdUv5j+MC524pRvuxFYC7VTphEmhmMM1teHCcRXvtm2+Gdd7m4E3VYN2PVTGLe9k8FZVoEjX1VDGWPkBYj6cBKjroUzX+/6/HUiO2LUzlXG9RxjYJ0fAKQbvJWgTxLgyJF5fs61nLtmnXG87AdtivdrwKq/06mG63hkAt8RD0TSBn1P5tJVkn1IoYqxE2NLTzk95jcJxUQA95FWVkXy0PKVXV0CZrvc8gD2CbHf5trVFStMQyDbfjuxTpus5AOyYpJnr9XStNHj+MoMq/wHwNQslzeAva3Z+vSpQpPvfl1/6SK1fuzgj+hbwgW9bLySBki0/kDbkF28+mcRzIa2wUZiux3EBCPx+1c6/lCQB0y1/DPDjcWP0euqmSik7mcSzFahfAVy3YBDGMX/YWpskAdPxjoJwd8yYwLetVBK/+IILXAynfJaIV8RWVg8GK5tWnFNJxBjzcsQQfb/70betW1W8ZBrh8ss43kdMeEpg8pVvW+tkQaL7puu5AIqxWsIRv2htUPGSaYRQ0as5kfadyCT6iqrV9VKllJ2J05muF+110Z4nYMKWqm3tkiWscl/6kmiOlY+DWfLPiI9qwIuTdv5Uc9C0463VCNsB3CsBuhD0XzUwdb9xUSVpmUYKld7v3aWF+FZm9M99ohNgjpLLA8iqjGPGjtqwFX/QVTFp0kih/noeHO9lEFr+tSLOiet6vS/XjlY+H0cJqvGg7wewKWHRZHIm4DGVE77MqPm+MtT1B85c2xdc8Q2AVUkCCLXET/jF/N62+TWMlKEifQPsoOzBV0hySWYo8fJrTtRwyruJONERaX48A5+xFr4x9WDhtAJ8S5JEM9UcYcAdXxlCfwfgh5QiEw4jCN9a7J93lVgtQ82bZw5Wr+a52Q3MWKcRD/Hfz1y0Ef8CoMygQ6m6vq9Syv6mklA7NIuGakcS7fZYhmp3RZfKrydn6k9hSxxUrKqaxwAAAABJRU5ErkJggg==&quot;/&gt;</code></pre><p id="53c8f0bf-c3ac-4f5d-8a2e-5f9dce3ca2c3" class="">
</p><p id="d489f80d-4b8c-450c-940a-f644bb990b46" class="">
</p><script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/prism.min.js" integrity="sha512-7Z9J3l1+EYfeaPKcGXu3MS/7T+w19WtKQY/n+xzmw4hZhJ9tyYmcUS+4QqAlzhicE5LAfMQSF3iFTK9bQdTxXg==" crossorigin="anonymous" referrerPolicy="no-referrer"></script><link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/themes/prism.min.css" integrity="sha512-tN7Ec6zAFaVSG3TpNAKtk4DOHNpSwKHxxrsiw4GHKESGPs5njn/0sMCUMl2svV4wo4BK/rCP7juYz+zx+l6oeQ==" crossorigin="anonymous" referrerPolicy="no-referrer"/><pre id="21b92c3a-4c6a-4578-9d17-909bec6e6e9c" class="code"><code class="language-HTML">&lt;!--Botones--&gt;
  &lt;button class=&quot;boton-JohaLibrari-white&quot;&gt;white&lt;/button&gt;
  
   &lt;button class=&quot;boton-JohaLibrari-red color-JohaLibrari-white&quot;&gt;red&lt;/button&gt;
   
   &lt;button class=&quot;boton-JohaLibrari-orange color-JohaLibrari-white&quot;&gt;orange&lt;/button&gt;
      
   &lt;button class=&quot;boton-JohaLibrari-primary color-JohaLibrari-white&quot;&gt;primary&lt;/button&gt;</code></pre><p id="a75129c5-9756-4fd2-a0ef-eca979bd0888" class="">
</p><script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/prism.min.js" integrity="sha512-7Z9J3l1+EYfeaPKcGXu3MS/7T+w19WtKQY/n+xzmw4hZhJ9tyYmcUS+4QqAlzhicE5LAfMQSF3iFTK9bQdTxXg==" crossorigin="anonymous" referrerPolicy="no-referrer"></script><link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/themes/prism.min.css" integrity="sha512-tN7Ec6zAFaVSG3TpNAKtk4DOHNpSwKHxxrsiw4GHKESGPs5njn/0sMCUMl2svV4wo4BK/rCP7juYz+zx+l6oeQ==" crossorigin="anonymous" referrerPolicy="no-referrer"/><pre id="a26f5c90-fb73-47a1-ac90-8bf0bb7a99af" class="code"><code class="language-HTML">&lt;!--crear input--&gt;
&lt;input type=&quot;text&quot; class=&quot;color-rededor-JohaLibrari-red&quot; placeholder=&quot;Escribe un texto&quot; style=&quot;padding-left: 5px;&quot;&gt;&lt;/input&gt;

&lt;input type=&quot;text&quot; class=&quot;color-rededor-JohaLibrari-primary&quot; placeholder=&quot;Escribe un texto&quot; style=&quot;padding-left: 5px;&quot;&gt;&lt;/input&gt;

&lt;input type=&quot;text&quot; class=&quot;color-rededor-JohaLibrari-orange&quot; placeholder=&quot;Escribe un texto&quot; style=&quot;padding-left: 5px;&quot;&gt;&lt;/input&gt;</code></pre><p id="e579a518-fb92-448a-a408-15f6182df101" class="">
</p></div></article><span class="sans" style="font-size:14px;padding-top:2em"></span></body></html>
