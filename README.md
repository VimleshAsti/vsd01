<html><head><meta http-equiv="Content-Type" content="text/html; charset=utf-8"/><title>Advanced OpenLANE Workshop</title><style>
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
	
</style></head><body><article id="719b6afb-e8fb-4a3d-896d-7827a597a1eb" class="page sans"><header><h1 class="page-title">Advanced OpenLANE Workshop</h1><p class="page-description"></p></header><div class="page-body"><h1 id="8568a483-5430-4edd-9a0b-4240e153dddf" class="">Advanced Physical Design - OpenLANE Workshop</h1><ul id="e944c5bc-e1ea-4681-8d32-35d4c904ea4e" class="toggle"><li><details open=""><summary>Table Of Contents</summary><ol type="1" id="7b51b84a-cc9a-4b4d-90ef-f917a4695dbc" class="numbered-list" start="1"><li>About The Project</li></ol><ol type="1" id="720bdbb7-1c95-4b6e-b5cc-b09bd7c46c08" class="numbered-list" start="2"><li>Getting Started</li></ol><ol type="1" id="4c4a2f57-a983-4ba7-86a1-3d0c19e7b0bc" class="numbered-list" start="3"><li>RTL to GDSII Introduction</li></ol><ol type="1" id="2647b831-433d-42d6-9ded-9a8689abe343" class="numbered-list" start="4"><li>Different Stages</li></ol><ol type="1" id="fef92e71-8b99-4136-874e-0daef034347d" class="numbered-list" start="5"><li>Day 1 Inception of Open Source EDA<ul id="a4174203-28bf-4e00-a06f-23beda8d0675" class="bulleted-list"><li style="list-style-type:disc">Skywater PDK Files</li></ul><ul id="c52cff96-d9ca-4a01-9c07-f04e1f050bc7" class="bulleted-list"><li style="list-style-type:disc">Invoking OpenLANE</li></ul><ul id="a12d2b47-57b3-4cd3-96de-eb0bcc0b29ca" class="bulleted-list"><li style="list-style-type:disc">Package Importing</li></ul><p id="4196a718-b917-4148-95b4-28d36b1dcb48" class="">
</p><ul id="b1233414-8a4d-4efb-b84a-ed099310e772" class="bulleted-list"><li style="list-style-type:disc">Design Folder Hierarchy</li></ul><ul id="2011faef-8b61-48dc-9a99-ac98de9a6cb9" class="bulleted-list"><li style="list-style-type:disc">Configuration Files</li></ul><ul id="1f95d628-0d13-433b-946f-5f60cb3ced0a" class="bulleted-list"><li style="list-style-type:disc">Prepare Design</li></ul><ul id="dad45492-13b0-4146-b8fa-b1d19ad5551a" class="bulleted-list"><li style="list-style-type:disc">Synthesis</li></ul></li></ol></details></li></ul><h2 id="a469225e-4d83-4b70-b5ac-51d668ff27e4" class="">About The Project</h2><hr id="20a4b94d-bcca-4fb3-8d70-9d2eb456a3e6"/><p id="7901b109-44e6-4046-99ea-00ce83ffa72a" class="">OpenLANE is an automated RTL to GDSII flow based on several components, including OpenROAD, Yosys, Magic, Netgen, Fault, OpenPhySyn, SPEF-Extractor, and custom methodology scripts for design exploration and optimization. It is a tool started for trustworthy open-source tape-out experience and comes with APACHE version 2.0. The goal of OpenLANE is to produce clean GDSII without any human intervention. OpenLANE is tuned for Skywater 130nm open-source PDK and can be used to create complex macros and chips.</p><p id="8cc2a7a2-27d4-463b-9886-14b708f243b5" class="">
</p><h3 id="c211aa10-9925-4e0b-96f3-6cc84ee80ffb" class="">Getting Started</h3><hr id="3e40057b-f8e1-4471-825c-51d497925313"/><p id="95655061-61a1-49d8-a2b4-4d66adfba4e7" class="">To give instructions on setting up your project locally. we need </p><ul id="dc6babfc-255a-4c0c-b662-7ec2011bffe0" class="bulleted-list"><li style="list-style-type:disc">Ubuntu OS-based System</li></ul><ul id="8b5499ed-a673-46b2-a813-1219076cf349" class="bulleted-list"><li style="list-style-type:disc">25+ Disk Space </li></ul><p id="4a1eb651-417c-41f1-8b8d-528083b894b6" class="">💥 Windows users can use a Virtual machine to get access to Ubuntu OS </p><h3 id="06d4fb81-b0c8-4592-870e-0f297b61c00f" class="">RTL to GDSII Introduction</h3><hr id="57bf30e7-5b34-4210-b0ed-a3f42f5fba46"/><p id="9162ab01-058e-495d-91fd-5413a667390a" class="">RTL (Register Transfer Level) to GDS 2 (Graphic Data System 2) represents the process of designing an Application-Specific Integrated Circuit (ASIC), which involves multiple stages and iterations. Despite variations due to factors like Engineering Change Orders (ECOs), Intellectual Property (IP) requirements, Design-for-Test (DFT) insertion, and Synchronous Design Constraints (SDC), the fundamental concepts of the ASIC design flow remain consistent. Here&#x27;s an explanation of the key stages:</p><ol type="1" id="6b1f8fb3-aec9-40eb-a558-42adca234bbf" class="numbered-list" start="1"><li><strong>Architectural Design</strong>:<ul id="349e3f7e-2458-4cf2-a053-75379a98284f" class="bulleted-list"><li style="list-style-type:disc">System specifications are provided, often by system engineers, detailing the functionality and performance requirements.</li></ul><ul id="012d113b-3b46-4f71-97b0-cc6e136d54b6" class="bulleted-list"><li style="list-style-type:disc">The VLSI engineer designs the architecture at a high level, considering physical constraints such as power consumption, speed, and area.</li></ul><ul id="4607dfe7-42c4-4725-8e6a-30eee7d01aa3" class="bulleted-list"><li style="list-style-type:disc">This stage involves trade-offs between performance, area, and power consumption.</li></ul></li></ol><ol type="1" id="5a1a16d8-ae03-4508-bdab-717ce0845f39" class="numbered-list" start="2"><li><strong>RTL Design/Behavioral Modeling</strong>:<ul id="73295376-61e4-4ce6-ae28-593874a0364b" class="bulleted-list"><li style="list-style-type:disc">RTL design involves describing the functionality of the circuit in terms of registers, combinational logic, and modules.</li></ul><ul id="3e0a081a-afd7-4829-b9cd-cb3ac9204275" class="bulleted-list"><li style="list-style-type:disc">Behavioral modeling allows for design at a higher level of abstraction, bridging the gap between C and HDL.</li></ul><ul id="eb8ffbce-d0a2-4738-a01f-b5162f2069de" class="bulleted-list"><li style="list-style-type:disc">Verilog and VHDL are commonly used HDLs for this purpose.</li></ul></li></ol><ol type="1" id="d37808aa-eeec-482f-b5cb-f821ebc8eb07" class="numbered-list" start="3"><li><strong>RTL Verification</strong>:<ul id="643ae1f5-1033-430e-9c9c-10391dd7f86f" class="bulleted-list"><li style="list-style-type:disc">Behavioral verification ensures that the RTL design behaves as expected under various conditions.</li></ul><ul id="046d2849-1741-429e-a76e-cc0cb663c6a8" class="bulleted-list"><li style="list-style-type:disc">Test benches are written to apply stimuli and verify the responses against expected results.</li></ul><ul id="059cf4bd-2f27-4804-96d2-36ba07118eb1" class="bulleted-list"><li style="list-style-type:disc">Simulation and formal verification techniques are employed to validate the design.</li></ul></li></ol><ol type="1" id="c91823b5-c7ee-4f15-b514-c6b54f74104e" class="numbered-list" start="4"><li><strong>DFT Insertion</strong>:<ul id="0112d67b-cc68-448d-b1cc-a2559860c74f" class="bulleted-list"><li style="list-style-type:disc">Design-for-Test (DFT) circuits, such as scan chains and Built-In Self-Test (BIST) structures, are inserted into the design to facilitate manufacturing testing.</li></ul><ul id="967f5259-0704-437d-9c86-a43ceb465558" class="bulleted-list"><li style="list-style-type:disc">DFT insertion aims to enhance fault coverage and reduce test time and cost.</li></ul></li></ol><ol type="1" id="e6ca0d2c-7c82-4363-bf7b-c4ebf0126375" class="numbered-list" start="5"><li><strong>Logic Synthesis</strong>:<ul id="8cda1f4d-900e-4786-a146-32ed140f43cd" class="bulleted-list"><li style="list-style-type:disc">Logic synthesis translates the RTL description into a gate-level netlist, optimizing for area, power, and timing.</li></ul><ul id="905a8731-318b-4423-b4fb-8395649a98ab" class="bulleted-list"><li style="list-style-type:disc">GTECH mapping maps the HDL netlist to generic gates for logical optimization.</li></ul><ul id="74fb4072-615f-433e-8fe7-fcbb0fcc2786" class="bulleted-list"><li style="list-style-type:disc">Technology mapping maps the post-optimized netlist to standard cells from the Process Design Kit (PDK).</li></ul></li></ol><ol type="1" id="be931f52-e3ef-4a2f-89c7-4869af6375f2" class="numbered-list" start="6"><li><strong>Standard Cells</strong>:<ul id="aae1d749-6421-4fa2-9788-4c82ddf2a206" class="bulleted-list"><li style="list-style-type:disc">Standard cells are predefined logic elements with fixed height and width, optimized for area and performance.</li></ul><ul id="93aec169-b4c7-4c82-8304-b6b147777150" class="bulleted-list"><li style="list-style-type:disc">They include SPICE, HDL, liberty, and layout files for use in various stages of the RTL to GDSII flow.</li></ul></li></ol><ol type="1" id="3e05b458-ef75-4b45-8b79-adce5215772f" class="numbered-list" start="7"><li><strong>Post-Synthesis STA Analysis</strong>:<ul id="6d02fa20-b59d-4369-ada7-fb9dbbbc1bf0" class="bulleted-list"><li style="list-style-type:disc">Setup analysis is performed to ensure that all timing constraints are met after logic synthesis.</li></ul><ul id="891e338a-116d-4e57-b42d-3f163e7c370a" class="bulleted-list"><li style="list-style-type:disc">Timing paths are analyzed to identify any setup time violations and optimize for timing closure.</li></ul></li></ol><ol type="1" id="556121d1-ab74-43c3-89e3-595d10f7ec82" class="numbered-list" start="8"><li><strong>Floorplanning</strong>:<ul id="980e29eb-3f0b-462c-b17c-e6b53d7f8884" class="bulleted-list"><li style="list-style-type:disc">Floorplanning involves planning the physical layout of the chip to optimize area and power distribution.</li></ul><ul id="64d46eb6-e079-46f1-a75f-097f02f03893" class="bulleted-list"><li style="list-style-type:disc">Power distribution networks (PDNs) are designed to deliver power to individual components of the chip.</li></ul><ul id="bd91f5e5-3ce9-4fb6-bded-c4e2173cc000" class="bulleted-list"><li style="list-style-type:disc">Macro placement and blockages are defined to ensure a legalized GDS file.</li></ul></li></ol><ol type="1" id="4c310386-e29b-4663-864d-2c19b70aaaee" class="numbered-list" start="9"><li><strong>Placement</strong>:<ul id="6f4f3199-c134-4a10-bc04-4505e82b8a5f" class="bulleted-list"><li style="list-style-type:disc">Standard cells are placed on the floorplan rows, aligned with sites defined in the technology LEF file.</li></ul><ul id="d5505a5b-68ff-4e63-a151-a93851b834e3" class="bulleted-list"><li style="list-style-type:disc">Global placement optimizes cell positions, while detailed placement legalizes the placements to adhere to global placement constraints.</li></ul></li></ol><ol type="1" id="8427ac8b-bcf8-420f-a630-17cb106d6055" class="numbered-list" start="10"><li><strong>CTS (Clock Tree Synthesis)</strong>:<ul id="59ea3765-b7d9-4631-9434-213b5fc65cd6" class="bulleted-list"><li style="list-style-type:disc">Clock tree synthesis creates a clock distribution network to deliver clock signals to sequential elements.</li></ul><ul id="38be9a59-714f-4942-ab05-a98d0e9320a4" class="bulleted-list"><li style="list-style-type:disc">The goal is to minimize clock skew across the chip, often achieved using H-tree topologies.</li></ul></li></ol><ol type="1" id="5b60133f-3bf3-4e1e-a3c3-3b4aadf21882" class="numbered-list" start="11"><li><strong>Routing</strong>:<ul id="6c98821b-a85f-4832-a87b-bf824f97d46c" class="bulleted-list"><li style="list-style-type:disc">Routing implements interconnects between standard cells using available metal layers.</li></ul><ul id="32477d07-0db8-4392-955a-cb450a071f17" class="bulleted-list"><li style="list-style-type:disc">Routing is performed on routing grids to minimize design rule check (DRC) errors and optimize for signal integrity.</li></ul></li></ol><p id="deb2c3a6-990c-495b-b3dd-7a12a70546ff" class="">These steps collectively ensure the successful transformation of the RTL design into a manufacturable layout represented by the GDSII file format. Collaboration and iteration among different design teams and stages are essential for achieving design closure and meeting project goals.</p><figure id="826ffb07-810a-4658-8d47-f4570779456a" class="image"><a href="https://gitlab.com/gab13c/openlane-workshop/-/raw/master/images/asic_flow.png"><img src="https://gitlab.com/gab13c/openlane-workshop/-/raw/master/images/asic_flow.png"/></a></figure><h3 id="b7c8fc65-741b-453f-b0d4-30f4620c3ee8" class="">Different Stages</h3><p id="ed04ab06-036f-4a1a-a623-e41f13a4e44f" class=""> , Device Models (SPICE) for accurate electrical simulation, Digital Standard Cell Libraries for efficient digital logic implementation, and I/O Libraries for interfacing with external devices. These inputs guide various stages of design and verification, ensuring the successful realization of the ASIC design.</p><blockquote id="52f2a0f8-9917-4140-b965-c6d6c31f3ede" class="">The inputs to the ASIC design flow include:<script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/prism.min.js" integrity="sha512-7Z9J3l1+EYfeaPKcGXu3MS/7T+w19WtKQY/n+xzmw4hZhJ9tyYmcUS+4QqAlzhicE5LAfMQSF3iFTK9bQdTxXg==" crossorigin="anonymous" referrerPolicy="no-referrer"></script><link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/themes/prism.min.css" integrity="sha512-tN7Ec6zAFaVSG3TpNAKtk4DOHNpSwKHxxrsiw4GHKESGPs5njn/0sMCUMl2svV4wo4BK/rCP7juYz+zx+l6oeQ==" crossorigin="anonymous" referrerPolicy="no-referrer"/><pre id="129cf40c-8942-4941-a2ea-97ef6ad97ae9" class="code"><code class="language-Plain Text" style="white-space:pre-wrap;word-break:break-all">- Process Design Rules:   for DRC, LVS, PEX   defining fabrication constraints and layout verification 
- Device Models (SPICE)  for accurate electrical simulation
- Digital Standard Cell Libraries for efficient digital logic implementation
- I/O Libraries guide various stages of design and verification
</code></pre></blockquote><p id="1a117b5a-4ff7-4ac2-ab11-c6de583adbb8" class="">The Process Design Kit (PDK) serves as the bridge between CAD designers and foundries, providing essential files to model fabrication processes for Electronic Design Automation (EDA) tools used in Integrated Circuit (IC) design. Traditionally, PDKs have been closed-source, posing a barrier to open-source Digital ASIC Design. However, Google and Skywater made a groundbreaking move by releasing the world&#x27;s first open-source PDK on June 30th, 2020. This pivotal development has spurred the growth of open-source EDA tools.</p><p id="64edd385-5f12-4729-9fe9-48bac2bb465d" class="">We leverage the open-source RTL2GDS EDA tool, OpenLANE, in conjunction with the Skywater 130nm PDK. We can utilize these resources to perform the entire RTL2GDS flow, enabling them to design, simulate, synthesize, place, and route digital ASICs. This integration of open-source tools and PDKs marks a significant step forward in democratizing ASIC design and fostering innovation in the semiconductor industry.</p><figure id="e021d354-af1b-48e8-a97c-5002d6a062af" class="image"><a href="https://gitlab.com/gab13c/openlane-workshop/-/raw/master/images/openlane_flow.png"><img src="https://gitlab.com/gab13c/openlane-workshop/-/raw/master/images/openlane_flow.png"/></a></figure><p id="ba28d64f-6f36-4c76-b1aa-365052ab6716" class="">The OpenLANE flow consists of several stages, each with multiple sub-stages, facilitating the complete RTL2GDS design flow. Here&#x27;s a breakdown of each stage:</p><ol type="1" id="0f83fd77-2b5e-4dfb-8deb-c889a4973899" class="numbered-list" start="1"><li><strong>Synthesis</strong>:<ul id="90121f64-d1eb-46cc-a36a-93ada4e70572" class="bulleted-list"><li style="list-style-type:disc"><strong>Yosys</strong>: Performs RTL synthesis using GTech mapping.</li></ul><ul id="550593ca-f713-4fe7-a14f-90bdfbe93c2c" class="bulleted-list"><li style="list-style-type:disc"><strong>abc</strong>: Conducts technology mapping to standard cells defined in the Process Design Kit (PDK). Various synthesis techniques can be adjusted using different integrated abc scripts.</li></ul><ul id="df47c3be-50c9-4198-a516-bdf0483b8d0e" class="bulleted-list"><li style="list-style-type:disc"><strong>OpenSTA</strong>: Executes static timing analysis on the resulting netlist to generate timing reports.</li></ul><ul id="eeb86da3-a32e-4dc7-b8fd-f3ce56ed5ce2" class="bulleted-list"><li style="list-style-type:disc"><strong>Fault</strong>: Implements scan-chain insertion for post-fabrication testing, supporting ATPG (Automatic Test Pattern Generation) and test patterns compaction.</li></ul></li></ol><ol type="1" id="8d082f6a-6fb0-4d66-b4a5-747216232056" class="numbered-list" start="2"><li><strong>Floorplan and PDN (Power Distribution Network)</strong>:<ul id="f664295a-22b6-4b15-bc2b-f92c9bd6e592" class="bulleted-list"><li style="list-style-type:disc"><strong>Init_fp</strong>: Defines the core area for the macro, along with rows (for placement) and tracks (for routing).</li></ul><ul id="74f55a5a-3930-4fa5-8048-5c4e10cbfa43" class="bulleted-list"><li style="list-style-type:disc"><strong>Ioplacer</strong>: Places macro input and output ports.</li></ul><ul id="720d1e32-ced5-44f8-9c27-e9668ce25bd0" class="bulleted-list"><li style="list-style-type:disc"><strong>PDN</strong>: Generates the power distribution network.</li></ul><ul id="2e7c9c9f-d745-4639-89ed-6eb39f45534d" class="bulleted-list"><li style="list-style-type:disc"><strong>Tapcell</strong>: Inserts welltap and decap cells in the floorplan.</li></ul><ul id="16db376e-235c-4e20-abce-4ad39fd0c11c" class="bulleted-list"><li style="list-style-type:disc"><strong>Placement</strong>: Conducted in two steps, starting with global placement followed by detailed placement to legalize the design and ensure compatibility with standard cell rows.</li></ul><ul id="82ed5242-fd2d-4f5d-a962-954f627e2682" class="bulleted-list"><li style="list-style-type:disc"><strong>RePLace</strong>: Performs global placement.</li></ul><ul id="c4b368ad-d31e-476e-bfbb-9d17a6370d5e" class="bulleted-list"><li style="list-style-type:disc"><strong>Resizer</strong>: Applies optional optimizations on the design.</li></ul><ul id="47955042-7a14-4a6e-aaf5-98bca9d37409" class="bulleted-list"><li style="list-style-type:disc"><strong>OpenPhySyn</strong>: Executes timing optimizations on the design.</li></ul><ul id="0914ddda-6f89-490c-afaf-baa199a87b99" class="bulleted-list"><li style="list-style-type:disc"><strong>OpenDP</strong>: Conducts detailed placement to legalize globally placed components.</li></ul></li></ol><ol type="1" id="5a458b32-f1af-46b7-944d-878092e26a19" class="numbered-list" start="3"><li><strong>CTS (Clock Tree Synthesis)</strong>:<ul id="9670a96a-fa8e-45dd-a2ac-78f08962d869" class="bulleted-list"><li style="list-style-type:disc"><strong>TritonCTS</strong>: Synthesizes the clock distribution network.</li></ul></li></ol><ol type="1" id="216a4018-96f1-4633-9b55-389ef924fe3a" class="numbered-list" start="4"><li><strong>Routing</strong>:<ul id="577de61c-a0af-4404-b6e5-da4dfd8b680c" class="bulleted-list"><li style="list-style-type:disc"><strong>FastRoute</strong>: Executes global routing to generate a guide file for the detailed router.</li></ul><ul id="bfbd3688-dd16-435e-ba60-cf604a429ae6" class="bulleted-list"><li style="list-style-type:disc"><strong>TritonRoute</strong>: Conducts detailed routing based on global routing guides.</li></ul><ul id="3d2db27e-5cd3-4a46-8c24-2f7e46d504f2" class="bulleted-list"><li style="list-style-type:disc"><strong>SPEF-Extractor</strong>: Performs SPEF extraction, incorporating parasitic information into the design.</li></ul></li></ol><ol type="1" id="f07c7413-e9df-44fd-b634-4e78940f5601" class="numbered-list" start="5"><li><strong>GDSII Generation</strong>:<ul id="6e2d7d94-f10d-4048-bf9c-2fcd8e278136" class="bulleted-list"><li style="list-style-type:disc"><strong>Magic</strong>: Streams out the final GDSII layout file from the routed DEF (Design Exchange Format).</li></ul></li></ol><ol type="1" id="fd18b9e2-dd01-4b13-8478-ed09b3cb7d10" class="numbered-list" start="6"><li><strong>Checks</strong>:<ul id="4dad4a29-d035-4a94-aed4-341f2e5533ce" class="bulleted-list"><li style="list-style-type:disc"><strong>Magic</strong>: Performs Design Rule Checks (DRC) and Antenna Checks.</li></ul><ul id="1a0331cf-252b-4d9c-8279-3944aa7598f4" class="bulleted-list"><li style="list-style-type:disc"><strong>Netgen</strong>: Conducts Layout vs. Schematic (LVS) Checks.</li></ul></li></ol><p id="17958ece-275a-48e2-8702-462f1f22a04d" class="">These stages encompass the complete RTL2GDS design flow, covering synthesis, floorplanning, routing, GDSII generation, and various design rule and timing checks to ensure the integrity and manufacturability of the final design.</p><hr id="c06d62db-5bcc-4c9a-8b19-bad9ddf13229"/><h3 id="a3b84abf-47cb-41db-9968-02bb6ef250d6" class="">Day 1 Inception of Open Source EDA</h3><h3 id="046650e1-080e-4776-8a9d-841d1c48a22d" class="">Skywater PDK Files</h3><p id="8d56dcba-f302-4ee3-8f11-8625cc9b3a03" class="">In the context of the Skywater PDK and the workshop, the $PDK_ROOT directory serves as the root directory for the Skywater Process Design Kit (PDK) files. Within this directory, there are three subdirectories essential for the workshop. Here&#x27;s an explanation of each:</p><ol type="1" id="86cc4173-243e-4cff-9da6-0140f87043d4" class="numbered-list" start="1"><li><strong>libs</strong>:<ul id="307480a2-b621-4b7d-b012-6dc9a76d7141" class="bulleted-list"><li style="list-style-type:disc">This directory contains the library files necessary for the ASIC design process. It typically includes files related to standard cells, I/O cells, and other fundamental components required for designing integrated circuits. These library files provide information such as timing characteristics, power consumption, and layout details, enabling designers to effectively utilize the available resources in their designs.</li></ul></li></ol><ol type="1" id="7f5fc360-ab1e-4ad4-bb14-21e70e3c66b8" class="numbered-list" start="2"><li><strong>tech</strong>:<ul id="2c098116-6fba-47a3-a69b-2ff1868cf94a" class="bulleted-list"><li style="list-style-type:disc">The tech directory houses the technology files that define the characteristics and parameters of the semiconductor process technology. These files include information about the transistor models, metal layers, design rules, and other fabrication-related specifications. Designers use these files to ensure that their designs conform to the process technology&#x27;s capabilities and constraints, facilitating successful manufacturing and integration into silicon.</li></ul></li></ol><ol type="1" id="67fe7f47-27ca-4610-aff5-a3b73e0a487e" class="numbered-list" start="3"><li><strong>open_pdks</strong>:<ul id="4c1127d7-ed9f-407b-b281-e2e79c63de8c" class="bulleted-list"><li style="list-style-type:disc">This directory contains scripts and utilities for setting up and configuring the PDK environment, particularly with open-source EDA tools like OpenLANE. It may include scripts for setting environment variables, configuring tool paths, and other necessary setup tasks. The open_pdks directory helps streamline the integration of the Skywater PDK with open-source design tools, enabling designers to leverage the capabilities of the PDK effectively in their design workflows.</li></ul></li></ol><p id="8e30f0a6-4748-448b-8278-89d7e2a2f0e5" class="">Overall, these three subdirectories within the $PDK_ROOT directory provide the necessary resources and infrastructure for designers to work with the Skywater PDK effectively, facilitating the design and implementation of integrated circuits using open-source EDA tools like OpenLANE.</p><figure id="996ef1c8-73c1-4e81-82a9-7c40f6dc8ad7" class="image"><a href="Advanced%20OpenLANE%20Workshop%20719b6afbe8fb4a3d896d7827a597a1eb/Untitled.png"><img style="width:708px" src="Advanced%20OpenLANE%20Workshop%20719b6afbe8fb4a3d896d7827a597a1eb/Untitled.png"/></a></figure><p id="47a387b4-a15d-415d-8f35-a9ca03992c90" class="">In the context of the Skywater PDK and its associated directories:</p><ol type="1" id="656d0292-7ad8-4dab-8151-30ae67e59302" class="numbered-list" start="1"><li><strong>Skywater-pdk</strong>:<ul id="3b69ac1c-bade-4858-a916-9a74fd30ba54" class="bulleted-list"><li style="list-style-type:disc">This directory contains all the files provided by the foundry (Skywater) related to the Process Design Kit (PDK). These files include essential resources such as technology files, library files, design rule files, and other components necessary for designing integrated circuits using the Skywater process technology. The Skywater PDK serves as the foundation for designing ASICs and other semiconductor devices within the Skywater fabrication process.</li></ul></li></ol><ol type="1" id="16b14f09-b26f-4c7f-a6e1-1efffbb09d89" class="numbered-list" start="2"><li><strong>Open_pdks</strong>:<ul id="ae98b098-c7c0-468e-9284-2d1e5c5fbd4c" class="bulleted-list"><li style="list-style-type:disc">The Open_pdks directory contains scripts and utilities aimed at bridging the gap between closed-source and open-source PDKs to enhance compatibility with Electronic Design Automation (EDA) tools. These scripts facilitate the integration of the Skywater PDK with open-source EDA tools, enabling designers to leverage the capabilities of the PDK within their preferred design environments. The scripts may handle tasks such as environment setup, tool configuration, and format conversion to ensure smooth interaction between the PDK and EDA tools.</li></ul></li></ol><ol type="1" id="bb20e9db-a73e-4bf8-b05b-c1f4caa5d571" class="numbered-list" start="3"><li><strong>Sky130A</strong>:<ul id="63d3892e-07de-46e7-b159-27f396351e64" class="bulleted-list"><li style="list-style-type:disc">The Sky130A directory contains open-source compatible PDK files specifically tailored for the Skywater 130nm process technology. These files are designed to be compatible with open-source EDA tools and workflows, allowing designers to utilize the Skywater PDK seamlessly within the open-source ecosystem. The Sky130A PDK files include technology files, library files, and other resources formatted and documented to support open-source design methodologies, fostering collaboration and innovation in semiconductor design.</li></ul><h3 id="7b8c3f56-18e2-46d0-b587-5a4b321705f7" class="">Invoking OpenLane</h3><figure id="40491aa0-d865-4a9c-af5e-546aa3c5c9d4" class="image"><a href="Advanced%20OpenLANE%20Workshop%20719b6afbe8fb4a3d896d7827a597a1eb/Untitled%201.png"><img style="width:657px" src="Advanced%20OpenLANE%20Workshop%20719b6afbe8fb4a3d896d7827a597a1eb/Untitled%201.png"/></a></figure><h3 id="a43099a4-346a-4373-a4b2-aa9c2d46bd81" class="">Package Importing</h3><figure id="78f6e9e6-95c5-46cb-b6c8-b0c8c5bdec13" class="image"><a href="Advanced%20OpenLANE%20Workshop%20719b6afbe8fb4a3d896d7827a597a1eb/Untitled%202.png"><img style="width:575px" src="Advanced%20OpenLANE%20Workshop%20719b6afbe8fb4a3d896d7827a597a1eb/Untitled%202.png"/></a></figure><h3 id="56679c39-0ccd-4c7a-98fe-d2d3a56722c7" class="">Design Folder Hierarchy</h3><figure id="9e81dfa6-cff7-4e3f-8e85-b051541d6490" class="image"><a href="Advanced%20OpenLANE%20Workshop%20719b6afbe8fb4a3d896d7827a597a1eb/Untitled%203.png"><img style="width:680px" src="Advanced%20OpenLANE%20Workshop%20719b6afbe8fb4a3d896d7827a597a1eb/Untitled%203.png"/></a></figure><p id="41e8d9d2-9084-44cf-8911-9e152f9555b6" class="">Each design hierarchy comes with two distinct components:</p><ol type="1" id="3d1cfa71-10a6-49b1-9a34-f172efd333cd" class="numbered-list" start="1"><li>Src folder - Contains verilog files and sdc constraint files</li></ol><ol type="1" id="f97b4181-04bd-4b5c-94ca-3c053f787a66" class="numbered-list" start="2"><li>Config.tcl files - Design specific configuration switches used by OpenLANE</li></ol><p id="1fb20b9f-aa62-44c3-a92f-3800069468b5" class="">An example of a configuration file is given:</p><figure id="83f5767d-bfa2-4c9a-84fe-bc1b0430c783" class="image"><a href="Advanced%20OpenLANE%20Workshop%20719b6afbe8fb4a3d896d7827a597a1eb/Untitled%204.png"><img style="width:1057px" src="Advanced%20OpenLANE%20Workshop%20719b6afbe8fb4a3d896d7827a597a1eb/Untitled%204.png"/></a></figure><h3 id="2715fb0a-085c-46b9-956f-36459d258236" class="">Prepare Design</h3><figure id="7514925f-e904-4168-942f-b89c97de93b9" class="image"><a href="Advanced%20OpenLANE%20Workshop%20719b6afbe8fb4a3d896d7827a597a1eb/Untitled%205.png"><img style="width:680px" src="Advanced%20OpenLANE%20Workshop%20719b6afbe8fb4a3d896d7827a597a1eb/Untitled%205.png"/></a></figure><h3 id="8f645884-11d2-43a6-ba1c-218b0a60b50a" class="">Synthesis</h3><figure id="1300e1e0-2bd4-4709-a957-3fe08229f574" class="image"><a href="Advanced%20OpenLANE%20Workshop%20719b6afbe8fb4a3d896d7827a597a1eb/Untitled%206.png"><img style="width:680px" src="Advanced%20OpenLANE%20Workshop%20719b6afbe8fb4a3d896d7827a597a1eb/Untitled%206.png"/></a></figure><figure id="3b30c30d-6f67-4b79-a29a-1006180a10a9" class="image"><a href="Advanced%20OpenLANE%20Workshop%20719b6afbe8fb4a3d896d7827a597a1eb/Untitled%207.png"><img style="width:631px" src="Advanced%20OpenLANE%20Workshop%20719b6afbe8fb4a3d896d7827a597a1eb/Untitled%207.png"/></a></figure><p id="f2f702bc-6d1e-443d-83fa-1bf136a2644c" class="">
</p></li></ol></div></article><span class="sans" style="font-size:14px;padding-top:2em"></span></body></html>
