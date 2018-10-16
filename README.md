[![N|Solid](https://safehaven.io/files/tb-logo.png)](https://thorblock.io/)        [![N|Solid](https://safehaven.io/img/logo_color.png)](https://safehaven.io/)

The first communal funding turnkey solution on the VechainThor Blockchain
##

## ThorBlock API

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<!--[if IE]><meta http-equiv="X-UA-Compatible" content="IE=edge"><![endif]-->
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="generator" content="Asciidoctor 1.5.3">
<meta name="author" content="Thorblock Team">
<title>Thorblock Documentation</title>
<script src="/cdn-cgi/apps/head/hEpXqKn1xyK9uuO89Hw1AX8YcE8.js"></script><style>
@import url(http://cdnjs.cloudflare.com/ajax/libs/font-awesome/3.2.0/css/font-awesome.css);
/* normalize.css v2.1.1 | MIT License | git.io/normalize */
/* ========================================================================== HTML5 display definitions ========================================================================== */
/** Correct `block` display not defined in IE 8/9. */
article, aside, details, figcaption, figure, footer, header, hgroup, main, nav, section, summary {
    display: block;
}

/** Correct `inline-block` display not defined in IE 8/9. */
audio, canvas, video {
    display: inline-block;
}

/** Prevent modern browsers from displaying `audio` without controls. Remove excess height in iOS 5 devices. */
audio:not([controls]) {
    display: none;
    height: 0;
}

/** Address styling not present in IE 8/9. */
[hidden] {
    display: none;
}

/* ========================================================================== Base ========================================================================== */
/** 1. Prevent system color scheme's background color being used in Firefox, IE, and Opera. 2. Prevent system color scheme's text color being used in Firefox, IE, and Opera. 3. Set default font family to sans-serif. 4. Prevent iOS text size adjust after orientation change, without disabling user zoom. */
html {
    background: #fff; /* 1 */
    color: #000; /* 2 */
    font-family: sans-serif; /* 3 */
    -ms-text-size-adjust: 100%; /* 4 */
    -webkit-text-size-adjust: 100%; /* 4 */
}

/** Remove default margin. */
body {
    margin: 0;
}

/* ========================================================================== Links ========================================================================== */
/** Address `outline` inconsistency between Chrome and other browsers. */
a:focus {
    outline: thin dotted;
}

/** Improve readability when focused and also mouse hovered in all browsers. */
a:active, a:hover {
    outline: 0;
}

/* ========================================================================== Typography ========================================================================== */
/** Address variable `h1` font-size and margin within `section` and `article` contexts in Firefox 4+, Safari 5, and Chrome. */
h1 {
    font-size: 2em;
    margin: 0.67em 0;
}

/** Address styling not present in IE 8/9, Safari 5, and Chrome. */
abbr[title] {
    border-bottom: 1px dotted;
}

/** Address style set to `bolder` in Firefox 4+, Safari 5, and Chrome. */
b, strong {
    font-weight: bold;
}

/** Address styling not present in Safari 5 and Chrome. */
dfn {
    font-style: italic;
}

/** Address differences between Firefox and other browsers. */
hr {
    -moz-box-sizing: content-box;
    box-sizing: content-box;
    height: 0;
}

/** Address styling not present in IE 8/9. */
mark {
    background: #ff0;
    color: #000;
}

/** Correct font family set oddly in Safari 5 and Chrome. */
code, kbd, pre, samp {
    font-family: monospace, serif;
    font-size: 1em;
}

/** Improve readability of pre-formatted text in all browsers. */
pre {
    white-space: pre-wrap;
}

/** Set consistent quote types. */
q {
    quotes: "\201C" "\201D" "\2018" "\2019";
}

/** Address inconsistent and variable font size in all browsers. */
small {
    font-size: 80%;
}

/** Prevent `sub` and `sup` affecting `line-height` in all browsers. */
sub, sup {
    font-size: 75%;
    line-height: 0;
    position: relative;
    vertical-align: baseline;
}

sup {
    top: -0.5em;
}

sub {
    bottom: -0.25em;
}

/* ========================================================================== Embedded content ========================================================================== */
/** Remove border when inside `a` element in IE 8/9. */
img {
    border: 0;
}

/** Correct overflow displayed oddly in IE 9. */
svg:not(:root) {
    overflow: hidden;
}

/* ========================================================================== Figures ========================================================================== */
/** Address margin not present in IE 8/9 and Safari 5. */
figure {
    margin: 0;
}

/* ========================================================================== Forms ========================================================================== */
/** Define consistent border, margin, and padding. */
fieldset {
    border: 1px solid #c0c0c0;
    margin: 0 2px;
    padding: 0.35em 0.625em 0.75em;
}

/** 1. Correct `color` not being inherited in IE 8/9. 2. Remove padding so people aren't caught out if they zero out fieldsets. */
legend {
    border: 0; /* 1 */
    padding: 0; /* 2 */
}

/** 1. Correct font family not being inherited in all browsers. 2. Correct font size not being inherited in all browsers. 3. Address margins set differently in Firefox 4+, Safari 5, and Chrome. */
button, input, select, textarea {
    font-family: inherit; /* 1 */
    font-size: 100%; /* 2 */
    margin: 0; /* 3 */
}

/** Address Firefox 4+ setting `line-height` on `input` using `!important` in the UA stylesheet. */
button, input {
    line-height: normal;
}

/** Address inconsistent `text-transform` inheritance for `button` and `select`. All other form control elements do not inherit `text-transform` values. Correct `button` style inheritance in Chrome, Safari 5+, and IE 8+. Correct `select` style inheritance in Firefox 4+ and Opera. */
button, select {
    text-transform: none;
}

/** 1. Avoid the WebKit bug in Android 4.0.* where (2) destroys native `audio` and `video` controls. 2. Correct inability to style clickable `input` types in iOS. 3. Improve usability and consistency of cursor style between image-type `input` and others. */
button, html input[type="button"], input[type="reset"], input[type="submit"] {
    -webkit-appearance: button; /* 2 */
    cursor: pointer; /* 3 */
}

/** Re-set default cursor for disabled elements. */
button[disabled], html input[disabled] {
    cursor: default;
}

/** 1. Address box sizing set to `content-box` in IE 8/9. 2. Remove excess padding in IE 8/9. */
input[type="checkbox"], input[type="radio"] {
    box-sizing: border-box; /* 1 */
    padding: 0; /* 2 */
}

/** 1. Address `appearance` set to `searchfield` in Safari 5 and Chrome. 2. Address `box-sizing` set to `border-box` in Safari 5 and Chrome (include `-moz` to future-proof). */
input[type="search"] {
    -webkit-appearance: textfield; /* 1 */
    -moz-box-sizing: content-box;
    -webkit-box-sizing: content-box; /* 2 */
    box-sizing: content-box;
}

/** Remove inner padding and search cancel button in Safari 5 and Chrome on OS X. */
input[type="search"]::-webkit-search-cancel-button, input[type="search"]::-webkit-search-decoration {
    -webkit-appearance: none;
}

/** Remove inner padding and border in Firefox 4+. */
button::-moz-focus-inner, input::-moz-focus-inner {
    border: 0;
    padding: 0;
}

/** 1. Remove default vertical scrollbar in IE 8/9. 2. Improve readability and alignment in all browsers. */
textarea {
    overflow: auto; /* 1 */
    vertical-align: top; /* 2 */
}

/* ========================================================================== Tables ========================================================================== */
/** Remove most spacing between table cells. */
table {
    border-collapse: collapse;
    border-spacing: 0;
}

*, *:before, *:after {
    -moz-box-sizing: border-box;
    -webkit-box-sizing: border-box;
    box-sizing: border-box;
}

html, body {
    font-size: 100%;
}

body {
    background: white;
    color: #222222;
    padding: 0;
    margin: 0;
    font-family: "Helvetica Neue", "Helvetica", Helvetica, Arial, sans-serif;
    font-weight: normal;
    font-style: normal;
    line-height: 1;
    position: relative;
    cursor: auto;
}

a:hover {
    cursor: pointer;
}

a:focus {
    outline: none;
}

img, object, embed {
    max-width: 100%;
    height: auto;
}

object, embed {
    height: 100%;
}

img {
    -ms-interpolation-mode: bicubic;
}

#map_canvas img, #map_canvas embed, #map_canvas object, .map_canvas img, .map_canvas embed, .map_canvas object {
    max-width: none !important;
}

.left {
    float: left !important;
}

.right {
    float: right !important;
}

.text-left {
    text-align: left !important;
}

.text-right {
    text-align: right !important;
}

.text-center {
    text-align: center !important;
}

.text-justify {
    text-align: justify !important;
}

.hide {
    display: none;
}

.antialiased, body {
    -webkit-font-smoothing: antialiased;
}

img {
    display: inline-block;
    vertical-align: middle;
}

textarea {
    height: auto;
    min-height: 50px;
}

select {
    width: 100%;
}

p.lead, .paragraph.lead > p, #preamble > .sectionbody > .paragraph:first-of-type p {
    font-size: 1.21875em;
    line-height: 1.6;
}

.subheader, #content #toctitle, .admonitionblock td.content > .title, .exampleblock > .title, .imageblock > .title, .videoblock > .title, .listingblock > .title, .literalblock > .title, .openblock > .title, .paragraph > .title, .quoteblock > .title, .sidebarblock > .title, .tableblock > .title, .verseblock > .title, .dlist > .title, .olist > .title, .ulist > .title, .qlist > .title, .hdlist > .title, .tableblock > caption {
    line-height: 1.4;
    color: #980050;
    font-weight: 300;
    margin-top: 0.2em;
    margin-bottom: 0.5em;
}

/* Typography resets */
div, dl, dt, dd, ul, ol, li, h1, h2, h3, #toctitle, .sidebarblock > .content > .title, h4, h5, h6, pre, form, p, blockquote, th, td {
    margin: 0;
    padding: 0;
    direction: ltr;
}

/* Default Link Styles */
a {
    color: #b1005d;
    text-decoration: none;
    line-height: inherit;
}

a:hover, a:focus {
    color: #640035;
}

a img {
    border: none;
}

/* Default paragraph styles */
p {
    font-family: inherit;
    font-weight: normal;
    font-size: 1em;
    line-height: 1.6;
    margin-bottom: 1.25em;
    text-rendering: optimizeLegibility;
}

p aside {
    font-size: 0.875em;
    line-height: 1.35;
    font-style: italic;
}

/* Default header styles */
h1, h2, h3, #toctitle, .sidebarblock > .content > .title, h4, h5, h6 {
    font-family: "Helvetica Neue", "Helvetica", Helvetica, Arial, sans-serif;
    font-weight: normal;
    font-style: normal;
    color: #333333;
    text-rendering: optimizeLegibility;
    margin-top: 1em;
    margin-bottom: 0.5em;
    line-height: 1.2125em;
}

h1 small, h2 small, h3 small, #toctitle small, .sidebarblock > .content > .title small, h4 small, h5 small, h6 small {
    font-size: 60%;
    color: gray;
    line-height: 0;
}

h1 {
    font-size: 2.125em;
}

h2 {
    font-size: 1.6875em;
}

h3, #toctitle, .sidebarblock > .content > .title {
    font-size: 1.375em;
}

h4 {
    font-size: 1.125em;
}

h5 {
    font-size: 1.125em;
}

h6 {
    font-size: 1em;
}

hr {
    border: dotted #cccccc;
    border-width: 1px 0 0;
    clear: both;
    margin: 1.25em 0 1.1875em;
    height: 0;
}

/* Helpful Typography Defaults */
em, i {
    font-style: italic;
    line-height: inherit;
}

strong, b {
    font-weight: bold;
    line-height: inherit;
}

small {
    font-size: 60%;
    line-height: inherit;
}

code {
    font-family: Consolas, "Liberation Mono", Courier, monospace;
    font-weight: bold;
    color: #320348;
}

/* Lists */
ul, ol, dl {
    font-size: 1em;
    line-height: 1.6;
    margin-bottom: 1.25em;
    list-style-position: outside;
    font-family: inherit;
}

ul, ol {
    margin-left: 1.5em;
}

/* Unordered Lists */
ul li ul, ul li ol {
    margin-left: 1.25em;
    margin-bottom: 0;
    font-size: 1em; /* Override nested font-size change */
}

ul.square li ul, ul.circle li ul, ul.disc li ul {
    list-style: inherit;
}

ul.square {
    list-style-type: square;
}

ul.circle {
    list-style-type: circle;
}

ul.disc {
    list-style-type: disc;
}

ul.no-bullet {
    list-style: none;
}

/* Ordered Lists */
ol li ul, ol li ol {
    margin-left: 1.25em;
    margin-bottom: 0;
}

/* Definition Lists */
dl dt {
    margin-bottom: 0.3125em;
    font-weight: bold;
}

dl dd {
    margin-bottom: 1.25em;
}

/* Abbreviations */
abbr, acronym {
    text-transform: uppercase;
    font-size: 90%;
    color: #555555;
    border-bottom: 1px dotted #dddddd;
    cursor: help;
}

abbr {
    text-transform: none;
}

/* Blockquotes */
blockquote {
    margin: 0 0 1.25em;
    padding: 0.5625em 1.25em 0 1.1875em;
    border-left: 1px solid #efefef;
}

blockquote cite {
    display: block;
    font-size: 0.8125em;
    color: #5e5e5e;
}

blockquote cite:before {
    content: "\2014 \0020";
}

blockquote cite a, blockquote cite a:visited {
    color: #5e5e5e;
}

blockquote, blockquote p {
    line-height: 1.6;
    color: #777777;
}

/* Microformats */
.vcard {
    display: inline-block;
    margin: 0 0 1.25em 0;
    border: 1px solid #dddddd;
    padding: 0.625em 0.75em;
}

.vcard li {
    margin: 0;
    display: block;
}

.vcard .fn {
    font-weight: bold;
    font-size: 0.9375em;
}

.vevent .summary {
    font-weight: bold;
}

.vevent abbr {
    cursor: auto;
    text-decoration: none;
    font-weight: bold;
    border: none;
    padding: 0 0.0625em;
}

@media only screen and (min-width: 768px) {
    h1, h2, h3, #toctitle, .sidebarblock > .content > .title, h4, h5, h6 {
        line-height: 1.4;
    }

    h1 {
        font-size: 2.75em;
    }

    h2 {
        font-size: 2.3125em;
    }

    h3, #toctitle, .sidebarblock > .content > .title {
        font-size: 1.6875em;
    }

    h4 {
        font-size: 1.4375em;
    }
}

/* Print styles.  Inlined to avoid required HTTP connection: www.phpied.com/delay-loading-your-print-css/ Credit to Paul Irish and HTML5 Boilerplate (html5boilerplate.com)
*/
.print-only {
    display: none !important;
}

@media print {
    * {
        background: transparent !important;
        color: #000 !important; /* Black prints faster: h5bp.com/s */
        box-shadow: none !important;
        text-shadow: none !important;
    }

    a, a:visited {
        text-decoration: underline;
    }

    a[href]:after {
        content: " (" attr(href) ")";
    }

    abbr[title]:after {
        content: " (" attr(title) ")";
    }

    .ir a:after, a[href^="javascript:"]:after, a[href^="#"]:after {
        content: "";
    }

    pre, blockquote {
        border: 1px solid #999;
        page-break-inside: avoid;
    }

    thead {
        display: table-header-group; /* h5bp.com/t */
    }

    tr, img {
        page-break-inside: avoid;
    }

    img {
        max-width: 100% !important;
    }

    @page {
        margin: 0.5cm;
    }

    p, h2, h3, #toctitle, .sidebarblock > .content > .title {
        orphans: 3;
        widows: 3;
    }

    h2, h3, #toctitle, .sidebarblock > .content > .title {
        page-break-after: avoid;
    }

    .hide-on-print {
        display: none !important;
    }

    .print-only {
        display: block !important;
    }

    .hide-for-print {
        display: none !important;
    }

    .show-for-print {
        display: inherit !important;
    }
}

/* Tables */
table {
    background: white;
    margin-bottom: 1.25em;
    border: solid 1px #dddddd;
}

table thead, table tfoot {
    background: whitesmoke;
    font-weight: normal;
}

table thead tr th, table thead tr td, table tfoot tr th, table tfoot tr td {
    padding: 0.5em 0.625em 0.625em;
    font-size: inherit;
    color: #333333;
    text-align: left;
}

table tr th, table tr td {
    padding: 0.5625em 0.625em;
    font-size: inherit;
    color: #555555;
}

table tr.even, table tr.alt, table tr:nth-of-type(even) {
    background: #f9f9f9;
}

table thead tr th, table tfoot tr th, table tbody tr td, table tr td, table tfoot tr td {
    display: table-cell;
    line-height: 1.4;
}

.clearfix:before, .clearfix:after, .float-group:before, .float-group:after {
    content: " ";
    display: table;
}

.clearfix:after, .float-group:after {
    clear: both;
}

*:not(pre) > code {
    font-size: inherit;
    padding: 0;
    white-space: nowrap;
    background-color: inherit;
    border: 0 solid #dddddd;
    -webkit-border-radius: 0;
    border-radius: 0;
    text-shadow: none;
}

pre, pre > code {
    line-height: 1.4;
    color: black;
    font-family: monospace, serif;
    font-weight: normal;
}

kbd.keyseq {
    color: #888888;
}

kbd:not(.keyseq) {
    display: inline-block;
    color: #555555;
    font-size: 0.75em;
    line-height: 1.4;
    background-color: #F7F7F7;
    border: 1px solid #ccc;
    -webkit-border-radius: 3px;
    border-radius: 3px;
    -webkit-box-shadow: 0 1px 0 rgba(0, 0, 0, 0.2), 0 0 0 2px white inset;
    box-shadow: 0 1px 0 rgba(0, 0, 0, 0.2), 0 0 0 2px white inset;
    margin: -0.15em 0.15em 0 0.15em;
    padding: 0.2em 0.6em 0.2em 0.5em;
    vertical-align: middle;
    white-space: nowrap;
}

kbd kbd:first-child {
    margin-left: 0;
}

kbd kbd:last-child {
    margin-right: 0;
}

.menuseq, .menu {
    color: #3b3b3b;
}

#header, #content, #footnotes, #footer {
    width: 100%;
    margin-left: auto;
    margin-right: auto;
    margin-top: 0;
    margin-bottom: 0;
    max-width: 62.5em;
    *zoom: 1;
    position: relative;
    padding-left: 0.9375em;
    padding-right: 0.9375em;
}

#header:before, #header:after, #content:before, #content:after, #footnotes:before, #footnotes:after, #footer:before, #footer:after {
    content: " ";
    display: table;
}

#header:after, #content:after, #footnotes:after, #footer:after {
    clear: both;
}

#header {
    margin-bottom: 2.5em;
}

#header > h1 {
    color: #b1005d;
    font-weight: normal;
    border-bottom: 1px dotted #cccccc;
    margin-bottom: -28px;
    padding-bottom: 32px;
}

#header span {
    color: #777777;
}

#header #revnumber {
    text-transform: capitalize;
}

#header br {
    display: none;
}

#header br + span {
    padding-left: 3px;
}

#header br + span:before {
    content: "\2013 \0020";
}

#header br + span.author {
    padding-left: 0;
}

#header br + span.author:before {
    content: ", ";
}

#toc {
    border-bottom: 1px solid #cccccc;
    padding-bottom: 1.25em;
}

#toc > ul {
    margin-left: 0.25em;
}

#toc ul.sectlevel0 > li > a {
    font-style: italic;
}

#toc ul.sectlevel0 ul.sectlevel1 {
    margin-left: 0;
    margin-top: 0.5em;
    margin-bottom: 0.5em;
}

#toc ul {
    list-style-type: none;
}

#toctitle {
    color: #980050;
}

@media only screen and (min-width: 1280px) {
    body.toc2 {
        padding-left: 20em;
    }

    #toc.toc2 {
        position: fixed;
        width: 20em;
        left: 0;
        top: 0;
        border-right: 1px solid #cccccc;
        border-bottom: 0;
        z-index: 1000;
        padding: 1em;
        height: 100%;
        overflow: auto;
    }

    #toc.toc2 #toctitle {
        margin-top: 0;
    }

    #toc.toc2 > ul {
        font-size: .95em;
    }

    #toc.toc2 ul ul {
        margin-left: 0;
        padding-left: 1.25em;
    }

    #toc.toc2 ul.sectlevel0 ul.sectlevel1 {
        padding-left: 0;
        margin-top: 0.5em;
        margin-bottom: 0.5em;
    }

    body.toc2.toc-right {
        padding-left: 0;
        padding-right: 20em;
    }

    body.toc2.toc-right #toc.toc2 {
        border-right: 0;
        border-left: 1px solid #cccccc;
        left: auto;
        right: 0;
    }
}

#content #toc {
    border-style: solid;
    border-width: 1px;
    border-color: #d9d9d9;
    margin-bottom: 1.25em;
    padding: 1.25em;
    background: #f2f2f2;
    border-width: 0;
    -webkit-border-radius: 0;
    border-radius: 0;
}

#content #toc > :first-child {
    margin-top: 0;
}

#content #toc > :last-child {
    margin-bottom: 0;
}

#content #toc a {
    text-decoration: none;
}

#content #toctitle {
    font-weight: bold;
    font-family: "Helvetica Neue", "Helvetica", Helvetica, Arial, sans-serif;
    font-size: 1em;
    padding-left: 0.125em;
}

#footer {
    max-width: 100%;
    background-color: #272727;
    padding: 1.25em;
}

#footer-text {
    color: #bcbcbc;
    line-height: 1.44;
}

.sect1 {
    padding-bottom: 1.25em;
}

.sect1 + .sect1 {
    border-top: 1px solid #cccccc;
}

#content h1 > a.anchor, h2 > a.anchor, h3 > a.anchor, #toctitle > a.anchor, .sidebarblock > .content > .title > a.anchor, h4 > a.anchor, h5 > a.anchor, h6 > a.anchor {
    position: absolute;
    width: 1em;
    margin-left: -1em;
    display: block;
    text-decoration: none;
    visibility: hidden;
    text-align: center;
    font-weight: normal;
}

#content h1 > a.anchor:before, h2 > a.anchor:before, h3 > a.anchor:before, #toctitle > a.anchor:before, .sidebarblock > .content > .title > a.anchor:before, h4 > a.anchor:before, h5 > a.anchor:before, h6 > a.anchor:before {
    content: '\00A7';
    font-size: .85em;
    vertical-align: text-top;
    display: block;
    margin-top: 0.05em;
}

#content h1:hover > a.anchor, #content h1 > a.anchor:hover, h2:hover > a.anchor, h2 > a.anchor:hover, h3:hover > a.anchor, #toctitle:hover > a.anchor, .sidebarblock > .content > .title:hover > a.anchor, h3 > a.anchor:hover, #toctitle > a.anchor:hover, .sidebarblock > .content > .title > a.anchor:hover, h4:hover > a.anchor, h4 > a.anchor:hover, h5:hover > a.anchor, h5 > a.anchor:hover, h6:hover > a.anchor, h6 > a.anchor:hover {
    visibility: visible;
}

#content h1 > a.link, h2 > a.link, h3 > a.link, #toctitle > a.link, .sidebarblock > .content > .title > a.link, h4 > a.link, h5 > a.link, h6 > a.link {
    color: #333333;
    text-decoration: none;
}

#content h1 > a.link:hover, h2 > a.link:hover, h3 > a.link:hover, #toctitle > a.link:hover, .sidebarblock > .content > .title > a.link:hover, h4 > a.link:hover, h5 > a.link:hover, h6 > a.link:hover {
    color: #262626;
}

.imageblock, .literalblock, .listingblock, .verseblock, .videoblock {
    margin-bottom: 1.25em;
}

.admonitionblock td.content > .title, .exampleblock > .title, .imageblock > .title, .videoblock > .title, .listingblock > .title, .literalblock > .title, .openblock > .title, .paragraph > .title, .quoteblock > .title, .sidebarblock > .title, .tableblock > .title, .verseblock > .title, .dlist > .title, .olist > .title, .ulist > .title, .qlist > .title, .hdlist > .title {
    text-align: left;
    font-weight: bold;
}

.tableblock > caption {
    text-align: left;
    font-weight: bold;
    white-space: nowrap;
    overflow: visible;
    max-width: 0;
}

table.tableblock #preamble > .sectionbody > .paragraph:first-of-type p {
    font-size: inherit;
}

.admonitionblock > table {
    border: 0;
    background: none;
    width: 100%;
}

.admonitionblock > table td.icon {
    text-align: center;
    width: 80px;
}

.admonitionblock > table td.icon img {
    max-width: none;
}

.admonitionblock > table td.icon .title {
    font-weight: bold;
    text-transform: uppercase;
}

.admonitionblock > table td.content {
    padding-left: 1.125em;
    padding-right: 1.25em;
    border-left: 1px dotted #cccccc;
    color: #777777;
}

.admonitionblock > table td.content > :last-child > :last-child {
    margin-bottom: 0;
}

.exampleblock > .content {
    border-style: solid;
    border-width: 1px;
    border-color: #e6e6e6;
    margin-bottom: 1.25em;
    padding: 1.25em;
    background: white;
    -webkit-border-radius: 0;
    border-radius: 0;
}

.exampleblock > .content > :first-child {
    margin-top: 0;
}

.exampleblock > .content > :last-child {
    margin-bottom: 0;
}

.exampleblock > .content h1, .exampleblock > .content h2, .exampleblock > .content h3, .exampleblock > .content #toctitle, .sidebarblock.exampleblock > .content > .title, .exampleblock > .content h4, .exampleblock > .content h5, .exampleblock > .content h6, .exampleblock > .content p {
    color: #555555;
}

.exampleblock > .content h1, .exampleblock > .content h2, .exampleblock > .content h3, .exampleblock > .content #toctitle, .sidebarblock.exampleblock > .content > .title, .exampleblock > .content h4, .exampleblock > .content h5, .exampleblock > .content h6 {
    line-height: 1;
    margin-bottom: 0.625em;
}

.exampleblock > .content h1.subheader, .exampleblock > .content h2.subheader, .exampleblock > .content h3.subheader, .exampleblock > .content .subheader#toctitle, .sidebarblock.exampleblock > .content > .subheader.title, .exampleblock > .content h4.subheader, .exampleblock > .content h5.subheader, .exampleblock > .content h6.subheader {
    line-height: 1.4;
}

.exampleblock.result > .content {
    -webkit-box-shadow: 0 1px 8px #d9d9d9;
    box-shadow: 0 1px 8px #d9d9d9;
}

.sidebarblock {
    border-style: solid;
    border-width: 1px;
    border-color: #d9d9d9;
    margin-bottom: 1.25em;
    padding: 1.25em;
    background: #f2f2f2;
    -webkit-border-radius: 0;
    border-radius: 0;
}

.sidebarblock > :first-child {
    margin-top: 0;
}

.sidebarblock > :last-child {
    margin-bottom: 0;
}

.sidebarblock h1, .sidebarblock h2, .sidebarblock h3, .sidebarblock #toctitle, .sidebarblock > .content > .title, .sidebarblock h4, .sidebarblock h5, .sidebarblock h6, .sidebarblock p {
    color: #555555;
}

.sidebarblock h1, .sidebarblock h2, .sidebarblock h3, .sidebarblock #toctitle, .sidebarblock > .content > .title, .sidebarblock h4, .sidebarblock h5, .sidebarblock h6 {
    line-height: 1;
    margin-bottom: 0.625em;
}

.sidebarblock h1.subheader, .sidebarblock h2.subheader, .sidebarblock h3.subheader, .sidebarblock .subheader#toctitle, .sidebarblock > .content > .subheader.title, .sidebarblock h4.subheader, .sidebarblock h5.subheader, .sidebarblock h6.subheader {
    line-height: 1.4;
}

.sidebarblock > .content > .title {
    color: #980050;
    margin-top: 0;
    line-height: 1.6;
}

.exampleblock > .content > :last-child > :last-child, .exampleblock > .content .olist > ol > li:last-child > :last-child, .exampleblock > .content .ulist > ul > li:last-child > :last-child, .exampleblock > .content .qlist > ol > li:last-child > :last-child, .sidebarblock > .content > :last-child > :last-child, .sidebarblock > .content .olist > ol > li:last-child > :last-child, .sidebarblock > .content .ulist > ul > li:last-child > :last-child, .sidebarblock > .content .qlist > ol > li:last-child > :last-child {
    margin-bottom: 0;
}

.literalblock > .content pre, .listingblock > .content pre {
    background: #efefef;
    border-width: 1px;
    border-style: solid;
    border-color: #cccccc;
    -webkit-border-radius: 0;
    border-radius: 0;
    padding: 0.75em 0.75em 0.625em 0.75em;
    word-wrap: break-word;
}

.literalblock > .content pre.nowrap, .listingblock > .content pre.nowrap {
    overflow-x: auto;
    white-space: pre;
    word-wrap: normal;
}

.literalblock > .content pre > code, .listingblock > .content pre > code {
    display: block;
}

@media only screen {
    .literalblock > .content pre, .listingblock > .content pre {
        font-size: 0.72em;
    }
}

@media only screen and (min-width: 768px) {
    .literalblock > .content pre, .listingblock > .content pre {
        font-size: 0.81em;
    }
}

@media only screen and (min-width: 1280px) {
    .literalblock > .content pre, .listingblock > .content pre {
        font-size: 0.9em;
    }
}

.listingblock > .content {
    position: relative;
}

.listingblock:hover code[class*=" language-"]:before {
    text-transform: uppercase;
    font-size: 0.9em;
    color: #999;
    position: absolute;
    top: 0.375em;
    right: 0.375em;
}

.listingblock:hover code.asciidoc:before {
    content: "asciidoc";
}

.listingblock:hover code.clojure:before {
    content: "clojure";
}

.listingblock:hover code.css:before {
    content: "css";
}

.listingblock:hover code.groovy:before {
    content: "groovy";
}

.listingblock:hover code.html:before {
    content: "html";
}

.listingblock:hover code.java:before {
    content: "java";
}

.listingblock:hover code.javascript:before {
    content: "javascript";
}

.listingblock:hover code.python:before {
    content: "python";
}

.listingblock:hover code.ruby:before {
    content: "ruby";
}

.listingblock:hover code.scss:before {
    content: "scss";
}

.listingblock:hover code.xml:before {
    content: "xml";
}

.listingblock:hover code.yaml:before {
    content: "yaml";
}

.listingblock.terminal pre .command:before {
    content: attr(data-prompt);
    padding-right: 0.5em;
    color: #999;
}

.listingblock.terminal pre .command:not([data-prompt]):before {
    content: '$';
}

table.pyhltable {
    border: 0;
    margin-bottom: 0;
}

table.pyhltable td {
    vertical-align: top;
    padding-top: 0;
    padding-bottom: 0;
}

table.pyhltable td.code {
    padding-left: .75em;
    padding-right: 0;
}

.highlight.pygments .lineno, table.pyhltable td:not(.code) {
    color: #999;
    padding-left: 0;
    padding-right: .5em;
    border-right: 1px solid #cccccc;
}

.highlight.pygments .lineno {
    display: inline-block;
    margin-right: .25em;
}

table.pyhltable .linenodiv {
    background-color: transparent !important;
    padding-right: 0 !important;
}

.quoteblock {
    margin: 0 0 1.25em;
    padding: 0.5625em 1.25em 0 1.1875em;
    border-left: 1px solid #efefef;
}

.quoteblock blockquote {
    margin: 0 0 1.25em 0;
    padding: 0 0 0.5625em 0;
    border: 0;
}

.quoteblock blockquote > .paragraph:last-child p {
    margin-bottom: 0;
}

.quoteblock .attribution {
    margin-top: -.25em;
    padding-bottom: 0.5625em;
    font-size: 0.8125em;
    color: #5e5e5e;
}

.quoteblock .attribution br {
    display: none;
}

.quoteblock .attribution cite {
    display: block;
    margin-bottom: 0.625em;
}

table thead th, table tfoot th {
    font-weight: normal;
}

table.tableblock.grid-all {
    border-collapse: separate;
    border-spacing: 1px;
    -webkit-border-radius: 0;
    border-radius: 0;
    border-top: 1px solid #dddddd;
    border-bottom: 1px solid #dddddd;
}

table.tableblock.frame-topbot, table.tableblock.frame-none {
    border-left: 0;
    border-right: 0;
}

table.tableblock.frame-sides, table.tableblock.frame-none {
    border-top: 0;
    border-bottom: 0;
}

table.tableblock td .paragraph:last-child p, table.tableblock td > p:last-child {
    margin-bottom: 0;
}

th.tableblock.halign-left, td.tableblock.halign-left {
    text-align: left;
}

th.tableblock.halign-right, td.tableblock.halign-right {
    text-align: right;
}

th.tableblock.halign-center, td.tableblock.halign-center {
    text-align: center;
}

th.tableblock.valign-top, td.tableblock.valign-top {
    vertical-align: top;
}

th.tableblock.valign-bottom, td.tableblock.valign-bottom {
    vertical-align: bottom;
}

th.tableblock.valign-middle, td.tableblock.valign-middle {
    vertical-align: middle;
}

p.tableblock.header {
    color: #333333;
    font-weight: normal;
}

td > div.verse {
    white-space: pre;
}

ol {
    margin-left: 1.75em;
}

ul li ol {
    margin-left: 1.5em;
}

dl dd {
    margin-left: 1.125em;
}

dl dd:last-child, dl dd:last-child > :last-child {
    margin-bottom: 0;
}

ol > li p, ul > li p, ul dd, ol dd, .olist .olist, .ulist .ulist, .ulist .olist, .olist .ulist {
    margin-bottom: 0.625em;
}

ul.unstyled, ol.unnumbered, ul.checklist, ul.none {
    list-style-type: none;
}

ul.unstyled, ol.unnumbered, ul.checklist {
    margin-left: 0.625em;
}

ul.checklist li > p:first-child > i[class^="icon-check"]:first-child, ul.checklist li > p:first-child > input[type="checkbox"]:first-child {
    margin-right: 0.25em;
}

ul.checklist li > p:first-child > input[type="checkbox"]:first-child {
    position: relative;
    top: 1px;
}

ul.inline {
    margin: 0 auto 0.625em auto;
    margin-left: -1.375em;
    margin-right: 0;
    padding: 0;
    list-style: none;
    overflow: hidden;
}

ul.inline > li {
    list-style: none;
    float: left;
    margin-left: 1.375em;
    display: block;
}

ul.inline > li > * {
    display: block;
}

.unstyled dl dt {
    font-weight: normal;
    font-style: normal;
}

ol.arabic {
    list-style-type: decimal;
}

ol.decimal {
    list-style-type: decimal-leading-zero;
}

ol.loweralpha {
    list-style-type: lower-alpha;
}

ol.upperalpha {
    list-style-type: upper-alpha;
}

ol.lowerroman {
    list-style-type: lower-roman;
}

ol.upperroman {
    list-style-type: upper-roman;
}

ol.lowergreek {
    list-style-type: lower-greek;
}

.hdlist > table, .colist > table {
    border: 0;
    background: none;
}

.hdlist > table > tbody > tr, .colist > table > tbody > tr {
    background: none;
}

td.hdlist1 {
    padding-right: .8em;
    font-weight: bold;
}

td.hdlist1, td.hdlist2 {
    vertical-align: top;
}

.literalblock + .colist, .listingblock + .colist {
    margin-top: -0.5em;
}

.colist > table tr > td:first-of-type {
    padding: 0 .8em;
    line-height: 1;
}

.colist > table tr > td:last-of-type {
    padding: 0.25em 0;
}

.qanda > ol > li > p > em:only-child {
    color: #980050;
}

.thumb, .th {
    line-height: 0;
    display: inline-block;
    border: solid 4px white;
    -webkit-box-shadow: 0 0 0 1px #dddddd;
    box-shadow: 0 0 0 1px #dddddd;
}

.imageblock.left, .imageblock[style*="float: left"] {
    margin: 0.25em 0.625em 1.25em 0;
}

.imageblock.right, .imageblock[style*="float: right"] {
    margin: 0.25em 0 1.25em 0.625em;
}

.imageblock > .title {
    margin-bottom: 0;
}

.imageblock.thumb, .imageblock.th {
    border-width: 6px;
}

.imageblock.thumb > .title, .imageblock.th > .title {
    padding: 0 0.125em;
}

.image.left, .image.right {
    margin-top: 0.25em;
    margin-bottom: 0.25em;
    display: inline-block;
    line-height: 0;
}

.image.left {
    margin-right: 0.625em;
}

.image.right {
    margin-left: 0.625em;
}

a.image {
    text-decoration: none;
}

span.footnote, span.footnoteref {
    vertical-align: super;
    font-size: 0.875em;
}

span.footnote a, span.footnoteref a {
    text-decoration: none;
}

#footnotes {
    padding-top: 0.75em;
    padding-bottom: 0.75em;
    margin-bottom: 0.625em;
}

#footnotes hr {
    width: 20%;
    min-width: 6.25em;
    margin: -.25em 0 .75em 0;
    border-width: 1px 0 0 0;
}

#footnotes .footnote {
    padding: 0 0.375em;
    line-height: 1.3;
    font-size: 0.875em;
    margin-left: 1.2em;
    text-indent: -1.2em;
    margin-bottom: .2em;
}

#footnotes .footnote a:first-of-type {
    font-weight: bold;
    text-decoration: none;
}

#footnotes .footnote:last-of-type {
    margin-bottom: 0;
}

#content #footnotes {
    margin-top: -0.625em;
    margin-bottom: 0;
    padding: 0.75em 0;
}

.gist .file-data > table {
    border: none;
    background: #fff;
    width: 100%;
    margin-bottom: 0;
}

.gist .file-data > table td.line-data {
    width: 99%;
}

div.unbreakable {
    page-break-inside: avoid;
}

.big {
    font-size: larger;
}

.small {
    font-size: smaller;
}

.underline {
    text-decoration: underline;
}

.overline {
    text-decoration: overline;
}

.line-through {
    text-decoration: line-through;
}

.aqua {
    color: #00bfbf;
}

.aqua-background {
    background-color: #00fafa;
}

.black {
    color: black;
}

.black-background {
    background-color: black;
}

.blue {
    color: #0000bf;
}

.blue-background {
    background-color: #0000fa;
}

.fuchsia {
    color: #bf00bf;
}

.fuchsia-background {
    background-color: #fa00fa;
}

.gray {
    color: #606060;
}

.gray-background {
    background-color: #7d7d7d;
}

.green {
    color: #006000;
}

.green-background {
    background-color: #007d00;
}

.lime {
    color: #00bf00;
}

.lime-background {
    background-color: #00fa00;
}

.maroon {
    color: #600000;
}

.maroon-background {
    background-color: #7d0000;
}

.navy {
    color: #000060;
}

.navy-background {
    background-color: #00007d;
}

.olive {
    color: #606000;
}

.olive-background {
    background-color: #7d7d00;
}

.purple {
    color: #600060;
}

.purple-background {
    background-color: #7d007d;
}

.red {
    color: #bf0000;
}

.red-background {
    background-color: #fa0000;
}

.silver {
    color: #909090;
}

.silver-background {
    background-color: #bcbcbc;
}

.teal {
    color: #006060;
}

.teal-background {
    background-color: #007d7d;
}

.white {
    color: #bfbfbf;
}

.white-background {
    background-color: #fafafa;
}

.yellow {
    color: #bfbf00;
}

.yellow-background {
    background-color: #fafa00;
}

span.icon > [class^="icon-"], span.icon > [class*=" icon-"] {
    cursor: default;
}

.admonitionblock td.icon [class^="icon-"]:before {
    font-size: 2.5em;
    text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.5);
    cursor: default;
}

.admonitionblock td.icon .icon-note:before {
    content: "\f05a";
    color: #b1005d;
    color: #850046;
}

.admonitionblock td.icon .icon-tip:before {
    content: "\f0eb";
    text-shadow: 1px 1px 2px rgba(155, 155, 0, 0.8);
    color: #111;
}

.admonitionblock td.icon .icon-warning:before {
    content: "\f071";
    color: #bf6900;
}

.admonitionblock td.icon .icon-caution:before {
    content: "\f06d";
    color: #bf3400;
}

.admonitionblock td.icon .icon-important:before {
    content: "\f06a";
    color: #bf0000;
}

.conum {
    display: inline-block;
    color: white !important;
    background-color: #555555;
    -webkit-border-radius: 100px;
    border-radius: 100px;
    text-align: center;
    width: 20px;
    height: 20px;
    font-size: 12px;
    font-weight: bold;
    line-height: 20px;
    font-family: Arial, sans-serif;
    font-style: normal;
    position: relative;
    top: -2px;
    letter-spacing: -1px;
}

.conum * {
    color: white !important;
}

.conum + b {
    display: none;
}

.conum:after {
    content: attr(data-value);
}

.conum:not([data-value]):empty {
    display: none;
}

#header > h1 {
    border-bottom-style: solid;
}

#toctitle {
    color: #333333;
}

.sidebarblock {
    background: none;
    border: none;
    -webkit-box-shadow: 0 0 5px rgba(177, 0, 93, 0.5);
    box-shadow: 0 0 5px rgba(177, 0, 93, 0.5);
}

.sidebarblock > .content > .title {
    color: #181818;
}

</style>
</head>
<body class="book toc2 toc-left">
<div id="header">
<h1>Thorblock Documentation</h1>
<div class="details">
<span id="author" class="author">Thorblock Team</span><br>
<span id="email" class="email"><a href="/cdn-cgi/l/email-protection#ef86818980af9b87809d8d83808c84c18680"><span class="__cf_email__" data-cfemail="f49d9a929bb4809c9b8696989b979fda9d9b">[email&#160;protected]</span></a></span><br>
<span id="revnumber">version 1.0</span>
</div>
<div id="toc" class="toc2">
<div id="toctitle">Table of Contents</div>
<ul class="sectlevel1">
<li><a href="#_authorization">Authorization</a>
<ul class="sectlevel2">
<li><a href="#_authorization_curl_request">Example Curl request</a></li>
</ul>
</li>
<li><a href="#_pool">Pool</a>
<ul class="sectlevel2">
<li><a href="#_get_all_pools">Get all pools</a></li>
<li><a href="#_get_contributions">Get contributions</a></li>
<li><a href="#_get_a_specific_pool">Get a specific pool</a></li>
<li><a href="#_create_a_new_pool">Create a new pool</a></li>
<li><a href="#_cancel_a_pool">Cancel a pool</a></li>
<li><a href="#_contribute_to_a_pool">Contribute to a pool</a></li>
<li><a href="#_revoke_contributions_from_a_pool">Revoke contributions from a pool</a></li>
<li><a href="#_set_destination_adress">Set destination adress</a></li>
<li><a href="#_set_token_adress">Set token adress</a></li>
<li><a href="#_transfer_pool_funds">Transfer pool funds</a></li>
<li><a href="#_distribute_pool_funds">Distribute pool funds</a></li>
<li><a href="#_withdraw_funds">Withdraw funds</a></li>
<li><a href="#_withdrawal_balance">Withdrawal balance</a></li>
<li><a href="#_update_whitelist">Update whitelist</a></li>
<li><a href="#_whitelist_count">Whitelist count</a></li>
<li><a href="#_whitelist_check">Whitelist check</a></li>
</ul>
</li>
</ul>
</div>
</div>
<div id="content">
<div class="sect1">
<h2 id="_authorization">Authorization</h2>
<div class="sectionbody">
<div class="paragraph">
<p>Authorization is done using the Arkane identity provider Bearer token. For every call to the rest API, the bearer token must be included in the header.</p>
</div>
<div class="sect2">
<h3 id="_authorization_curl_request">Example Curl request</h3>
<div class="listingblock">
<div class="content">
<pre class="highlight"><code class="language-bash" data-lang="bash">$ curl 'https://api.thorblock.io/api/pools' -i -X GET \
    -H 'Authorization: eyJhbGciOiJSUzI1NiIsInR5cCIgOiAiSldUIiwia2lkIiA6ICJmQi1UenBOb0hBVGhwT2J4aW9qTDBrdm83MldmRzRXRXh1eFpiaXlGQUhzIn0.eyJqdGkiOiIzNTQxOGRmMy05YTg1LTQ5MTctYmFhMy1iOGQ0ZDc0YzEyOWQiLCJleHAiOjE1MzQ5Mzk5OTUsIm5iZiI6MCwiaWF0IjoxNTM0OTM5Mzk1LCJpc3MiOiJodHRwczovL2xvZ2luLXN0YWdpbmcuYXJrYW5lLm5ldHdvcmsvYXV0aC9yZWFsbXMvQXJrYW5lIiwiYXVkIjoiVGhvckJsb2NrIiwic3ViIjoiNzNiMDZjMDgtMTk3Zi00OGI2LWEwZjItY2MwMDI0YzliZDAwIiwidHlwIjoiQmVhcmVyIiwiYXpwIjoiVGhvckJsb2NrIiwibm9uY2UiOiJjMTk2MTY5YS02ZjFjLTQ2NTItOWM2NC04Nzg5NWJkNzdiZGUiLCJhdXRoX3RpbWUiOjE1MzQ5MzkzOTQsInNlc3Npb25fc3RhdGUiOiI0OTk3Njg1OC04ODQ3LTRmOGItYjMwMC02ZGNjZGViNzEwMDciLCJhY3IiOiIxIiwiYWxsb3dlZC1vcmlnaW5zIjpbImh0dHA6Ly9sb2NhbGhvc3Q6NjMzNDIiLCJodHRwOi8vMTI3LjAuMC4xKiIsImh0dHBzOi8vcHAudGhvcmJsb2NrLmlvKiIsImh0dHA6Ly9sb2NhbGhvc3Q6NjMzNDIqIiwiaHR0cHM6Ly90aG9yYmxvY2suaW8qIiwiaHR0cHM6Ly93d3cuYmV0dGVyaG9kbC5udSoiXSwicmVzb3VyY2VfYWNjZXNzIjp7fSwic2NvcGUiOiJvcGVuaWQgcmVhZDp3YWxsZXRzIHNpZ246d2FsbGV0cyBlbWFpbCBwcm9maWxlIiwiZW1haWxfdmVyaWZpZWQiOnRydWUsIm5hbWUiOiJKb2huIERvZSIsInByZWZlcnJlZF91c2VybmFtZSI6ImpvaG4iLCJnaXZlbl9uYW1lIjoiSm9obiIsImZhbWlseV9uYW1lIjoiRG9lIiwiZW1haWwiOiJqb2huZG9lX2tscWZkanFta2xmanFtQG1haWxpbmF0b3IuY29tIn0.hHOKNiqLlHpmDekDUfPiKPFW8nfTPXk0ybBTZsm0ITYp0Kos4zuhQYT2CNtAg4tkt1EpmiLHsAAmJuVT9--Js-ekwm0WNxyPHQX4QLZrvR8yqurdUtfXktzC5a-PZdn6mqXYkSURNiUXL8R8c43qhK0uuiKROmUyM3XJ_PvzfNIKH4kSDdJ-2zpJ6EkMeA25wABQU6-YsedP_7UcOgphuJhqN93VM16jw0OUOGlSN2pJzpgAe3piIwKpj6k3ZxX6WX2kwUAgKG1dacE4UiQTQqV_r9pZD74dHq3kAWtrLRzJ4KuhZ6ybF5EPapHbkj0rZw_XDruadUiQqthBFexgdA'</code></pre>
</div>
</div>
</div>
</div>
</div>
<div class="sect1">
<h2 id="_pool">Pool</h2>
<div class="sectionbody">
<div class="sect2">
<h3 id="_get_all_pools">Get all pools</h3>
<div class="sect3">
<h4 id="_get_all_pools_curl_request">Example Curl request</h4>
<div class="listingblock">
<div class="content">
<pre class="highlight"><code class="language-bash" data-lang="bash">$ curl 'https://api.thorblock.io/api/pools' -i -X GET</code></pre>
</div>
</div>
</div>
<div class="sect3">
<h4 id="_get_all_pools_http_response">Example response</h4>
<div class="listingblock">
<div class="content">
<pre class="highlight nowrap"><code class="language-http" data-lang="http">HTTP/1.1 200 OK
Content-Type: application/json;charset=UTF-8
Content-Length: 1685

[ {
  "address" : "0xbcae8341c929d2d98eed711577e017f96bc8129a",
  "admin" : "0x00000000000000000000000000000000000Ad310",
  "maxCap" : 1000000000000000000000,
  "minPersonalCap" : 50000000000000000000,
  "destinationAddress" : "0x7f547f2f6b90f52011b2366f4febd558ddd56db4",
  "feePerMille" : 5,
  "feeAddress" : "0x000000000000000000000000000000000000de71",
  "destinationAddressLocked" : false,
  "currentState" : "OPEN",
  "totalContributed" : 100000000000000000000,
  "totalRemaining" : 900000000000000000000,
  "tokenAddress" : null,
  "whitelisted" : null
}, {
  "address" : "0xbcae8341c929d2d98eed711577e017f96bc8129a",
  "admin" : "0x00000000000000000000000000000000000Ad310",
  "maxCap" : 1000000000000000000000,
  "minPersonalCap" : 50000000000000000000,
  "destinationAddress" : "0x0fcd82A10Ab3ED65f11336a1e9Fa47eb58A01C42",
  "feePerMille" : 5,
  "feeAddress" : "0x000000000000000000000000000000000000de71",
  "destinationAddressLocked" : false,
  "currentState" : "OPEN",
  "totalContributed" : 100000000000000000000,
  "totalRemaining" : 900000000000000000000,
  "tokenAddress" : null,
  "whitelisted" : null
}, {
  "address" : "0xbcae8341c929d2d98eed711577e017f96bc8129a",
  "admin" : "0x00000000000000000000000000000000000Ad310",
  "maxCap" : 1000000000000000000000,
  "minPersonalCap" : 50000000000000000000,
  "destinationAddress" : "0xC7E99C24Fe6FBcBD136caec13836656B3552E166",
  "feePerMille" : 5,
  "feeAddress" : "0x000000000000000000000000000000000000de71",
  "destinationAddressLocked" : false,
  "currentState" : "OPEN",
  "totalContributed" : 100000000000000000000,
  "totalRemaining" : 900000000000000000000,
  "tokenAddress" : null,
  "whitelisted" : null
} ]</code></pre>
</div>
</div>
</div>
<div class="sect3">
<h4 id="_get_all_pools_response_fields">Response fields</h4>
<table class="tableblock frame-all grid-all spread">
<colgroup>
<col style="width: 33%;">
<col style="width: 33%;">
<col style="width: 33%;">
</colgroup>
<thead>
<tr>
<th class="tableblock halign-left valign-top">Path</th>
<th class="tableblock halign-left valign-top">Type</th>
<th class="tableblock halign-left valign-top">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>[]</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>Array</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">An array of pools</p></td>
</tr>
</tbody>
</table>
</div>
</div>
<div class="sect2">
<h3 id="_get_contributions">Get contributions</h3>
<div class="paragraph">
<p>Returns all pools you contributed to</p>
</div>
<div class="sect3">
<h4 id="_get_contributions_curl_request">Example Curl request</h4>
<div class="listingblock">
<div class="content">
<pre class="highlight"><code class="language-bash" data-lang="bash">$ curl 'https://api.thorblock.io/api/contributions' -i -X GET</code></pre>
</div>
</div>
</div>
<div class="sect3">
<h4 id="_get_contributions_http_response">Example response</h4>
<div class="listingblock">
<div class="content">
<pre class="highlight nowrap"><code class="language-http" data-lang="http">HTTP/1.1 200 OK
Content-Type: application/json;charset=UTF-8
Content-Length: 293

[ {
  "pool" : "0x7f547f2f6b90f52011b2366f4febd558ddd56db4",
  "amount" : 100000000000000000000
}, {
  "pool" : "0x0fcd82A10Ab3ED65f11336a1e9Fa47eb58A01C42",
  "amount" : 200000000000000000000
}, {
  "pool" : "0xC7E99C24Fe6FBcBD136caec13836656B3552E166",
  "amount" : 300000000000000000000
} ]</code></pre>
</div>
</div>
</div>
<div class="sect3">
<h4 id="_get_contributions_response_fields">Response fields</h4>
<table class="tableblock frame-all grid-all spread">
<colgroup>
<col style="width: 33%;">
<col style="width: 33%;">
<col style="width: 33%;">
</colgroup>
<thead>
<tr>
<th class="tableblock halign-left valign-top">Path</th>
<th class="tableblock halign-left valign-top">Type</th>
<th class="tableblock halign-left valign-top">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>[]</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>Array</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">An array of pools the user contributed to</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>[].pool</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>String</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">The pool the user has contributed to</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>[].amount</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>Number</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">The amount the user has contributed (in WEI)</p></td>
</tr>
</tbody>
</table>
</div>
</div>
<div class="sect2">
<h3 id="_get_a_specific_pool">Get a specific pool</h3>
<div class="sect3">
<h4 id="_get_a_specific_pool_curl_request">Example Curl request</h4>
<div class="listingblock">
<div class="content">
<pre class="highlight"><code class="language-bash" data-lang="bash">$ curl 'https://api.thorblock.io/api/pools/0x0fcd82A10Ab3ED65f11336a1e9Fa47eb58A01C42' -i -X GET</code></pre>
</div>
</div>
</div>
<div class="sect3">
<h4 id="_get_a_specific_pool_path_parameters">Path parameters</h4>
<table class="tableblock frame-all grid-all spread">
<caption class="title">Table 1. /api/pools/{poolAddress}</caption>
<colgroup>
<col style="width: 50%;">
<col style="width: 50%;">
</colgroup>
<thead>
<tr>
<th class="tableblock halign-left valign-top">Parameter</th>
<th class="tableblock halign-left valign-top">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>poolAddress</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">the address of the pool</p></td>
</tr>
</tbody>
</table>
</div>
<div class="sect3">
<h4 id="_get_a_specific_pool_http_response">Example response</h4>
<div class="listingblock">
<div class="content">
<pre class="highlight nowrap"><code class="language-http" data-lang="http">HTTP/1.1 200 OK
Content-Type: application/json;charset=UTF-8
Content-Length: 559

{
  "address" : "0xbcae8341c929d2d98eed711577e017f96bc8129a",
  "admin" : "0x00000000000000000000000000000000000Ad310",
  "maxCap" : 1000000000000000000000,
  "minPersonalCap" : 50000000000000000000,
  "destinationAddress" : "0x7f547f2f6b90f52011b2366f4febd558ddd56db4",
  "feePerMille" : 5,
  "feeAddress" : "0x000000000000000000000000000000000000de71",
  "destinationAddressLocked" : false,
  "currentState" : "OPEN",
  "totalContributed" : 100000000000000000000,
  "totalRemaining" : 900000000000000000000,
  "tokenAddress" : null,
  "whitelisted" : null
}</code></pre>
</div>
</div>
</div>
<div class="sect3">
<h4 id="_get_a_specific_pool_response_fields">Response fields</h4>
<table class="tableblock frame-all grid-all spread">
<colgroup>
<col style="width: 33%;">
<col style="width: 33%;">
<col style="width: 33%;">
</colgroup>
<thead>
<tr>
<th class="tableblock halign-left valign-top">Path</th>
<th class="tableblock halign-left valign-top">Type</th>
<th class="tableblock halign-left valign-top">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>address</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>String</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">the address of the pool</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>admin</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>String</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">the address of the admin</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>maxCap</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>Number</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">the maximum cap for this pool (in WEI)</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>minPersonalCap</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>Number</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">the minimum personal cap to be allowed in this pool (in WEI)</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>destinationAddress</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>String</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">the destination address</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>feePerMille</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>Number</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">the fee per mille (ex. 1 PERMILLE = 0,1%)</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>feeAddress</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>String</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">the address the fee will be send to</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>destinationAddressLocked</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>Boolean</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">whether the destination address is locked or not</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>currentState</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>String</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">the state of this pool. This can be one of the following: OPEN, CANCELLED, TRANSFERRED, REFUNDED, TOKENS_TRANSFERRED, REFUNDED_AND_TOKENS_TRANSFERRED</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>totalContributed</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>Number</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">the total contribution amount (in WEI)</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>totalRemaining</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>Number</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">the total contribution amount remaining (in WEI)</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>tokenAddress</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>Null</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">The token address</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>whitelisted</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>Null</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">Indicating the pool has a whitelist or not</p></td>
</tr>
</tbody>
</table>
</div>
<div class="sect3">
<h4 id="_get_a_specific_pool_response_body">Response body</h4>
<div class="listingblock">
<div class="content">
<pre class="highlight nowrap"><code>{
  "address" : "0xbcae8341c929d2d98eed711577e017f96bc8129a",
  "admin" : "0x00000000000000000000000000000000000Ad310",
  "maxCap" : 1000000000000000000000,
  "minPersonalCap" : 50000000000000000000,
  "destinationAddress" : "0x7f547f2f6b90f52011b2366f4febd558ddd56db4",
  "feePerMille" : 5,
  "feeAddress" : "0x000000000000000000000000000000000000de71",
  "destinationAddressLocked" : false,
  "currentState" : "OPEN",
  "totalContributed" : 100000000000000000000,
  "totalRemaining" : 900000000000000000000,
  "tokenAddress" : null,
  "whitelisted" : null
}</code></pre>
</div>
</div>
</div>
</div>
<div class="sect2">
<h3 id="_create_a_new_pool">Create a new pool</h3>
<div class="sect3">
<h4 id="_create_a_new_pool_curl_request">Example Curl request</h4>
<div class="listingblock">
<div class="content">
<pre class="highlight"><code class="language-bash" data-lang="bash">$ curl 'https://api.thorblock.io/api/pools' -i -X POST \
    -H 'Content-Type: application/json' \
    -d '{
  "maxCap" : 1000000000000000000000,
  "minPersonalCap" : 50000000000000000000,
  "destinationAddress" : "0x7f547f2f6b90f52011b2366f4febd558ddd56db4",
  "destinationAddressLocked" : false,
  "whitelisted" : null
}'</code></pre>
</div>
</div>
</div>
<div class="sect3">
<h4 id="_create_a_new_pool_request_fields">Request fields</h4>
<table class="tableblock frame-all grid-all spread">
<colgroup>
<col style="width: 33%;">
<col style="width: 33%;">
<col style="width: 33%;">
</colgroup>
<thead>
<tr>
<th class="tableblock halign-left valign-top">Path</th>
<th class="tableblock halign-left valign-top">Type</th>
<th class="tableblock halign-left valign-top">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>maxCap</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>Number</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">The maxcap of the pool (VET in WEI)</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>minPersonalCap</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>Number</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">The minimum a person can contribute to the pool (VET in WEI)</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>destinationAddress</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>String</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">The destination address where the funds will (ex. the ICO contract)</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>destinationAddressLocked</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>Boolean</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">Boolean indicating destination address can be changed or not after creation</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>whitelisted</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>Null</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">True if pool has a whitelist, false otherwise</p></td>
</tr>
</tbody>
</table>
</div>
<div class="sect3">
<h4 id="_create_a_new_pool_http_response">Example response</h4>
<div class="listingblock">
<div class="content">
<pre class="highlight nowrap"><code class="language-http" data-lang="http">HTTP/1.1 200 OK
Content-Type: application/json;charset=UTF-8
Content-Length: 428

{
  "clauses" : [ {
    "to" : "0x6605598CE7E2E3E160c6D8aD5EEa7A562F7ab0af",
    "amount" : "0",
    "data" : "0x8a2640360000000000000000000000000000000000000000000000008ac7230489e8000000000000000000000000000000000000000000000000000006f05b59d3b200000000000000000000000000007f547f2f6b90f52011b2366f4febd558ddd56db40000000000000000000000000000000000000000000000000000000000000000"
  } ],
  "gasPriceCoef" : "0",
  "gas" : 350000
}</code></pre>
</div>
</div>
</div>
<div class="sect3">
<h4 id="_create_a_new_pool_response_fields">Response fields</h4>
<table class="tableblock frame-all grid-all spread">
<colgroup>
<col style="width: 33%;">
<col style="width: 33%;">
<col style="width: 33%;">
</colgroup>
<thead>
<tr>
<th class="tableblock halign-left valign-top">Path</th>
<th class="tableblock halign-left valign-top">Type</th>
<th class="tableblock halign-left valign-top">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>gas</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>Number</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">The amount of gas to be used</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>gasPriceCoef</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>String</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">The gasprice coef to be used</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>clauses[]</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>Array</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">The different clauses included in the transaction</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>clauses[].to</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>String</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">The target address of the transaction</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>clauses[].amount</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>String</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">The vet amount (not in WEI!) included in the transaction</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>clauses[].data</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>String</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">The data for the transaction</p></td>
</tr>
</tbody>
</table>
</div>
<div class="sect3">
<h4 id="_create_a_new_pool_response_body">Response body</h4>
<div class="listingblock">
<div class="content">
<pre class="highlight nowrap"><code>{
  "clauses" : [ {
    "to" : "0x6605598CE7E2E3E160c6D8aD5EEa7A562F7ab0af",
    "amount" : "0",
    "data" : "0x8a2640360000000000000000000000000000000000000000000000008ac7230489e8000000000000000000000000000000000000000000000000000006f05b59d3b200000000000000000000000000007f547f2f6b90f52011b2366f4febd558ddd56db40000000000000000000000000000000000000000000000000000000000000000"
  } ],
  "gasPriceCoef" : "0",
  "gas" : 350000
}</code></pre>
</div>
</div>
</div>
</div>
<div class="sect2">
<h3 id="_cancel_a_pool">Cancel a pool</h3>
<div class="sect3">
<h4 id="_cancel_a_pool_curl_request">Example Curl request</h4>
<div class="listingblock">
<div class="content">
<pre class="highlight"><code class="language-bash" data-lang="bash">$ curl 'https://api.thorblock.io/api/pools/poolAddress/cancel' -i -X POST \
    -H 'Content-Type: application/json'</code></pre>
</div>
</div>
</div>
<div class="sect3">
<h4 id="_cancel_a_pool_path_parameters">Path parameters</h4>
<table class="tableblock frame-all grid-all spread">
<caption class="title">Table 1. /api/pools/{poolAddress}/cancel</caption>
<colgroup>
<col style="width: 50%;">
<col style="width: 50%;">
</colgroup>
<thead>
<tr>
<th class="tableblock halign-left valign-top">Parameter</th>
<th class="tableblock halign-left valign-top">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>poolAddress</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">the address of the pool</p></td>
</tr>
</tbody>
</table>
</div>
<div class="sect3">
<h4 id="_cancel_a_pool_http_response">Example response</h4>
<div class="listingblock">
<div class="content">
<pre class="highlight nowrap"><code class="language-http" data-lang="http">HTTP/1.1 200 OK
Content-Type: application/json;charset=UTF-8
Content-Length: 171

{
  "clauses" : [ {
    "to" : "0x7b0eb37e542f8d18d0e13b1144f5309d947300d9",
    "amount" : "0",
    "data" : "0xea8a1af0"
  } ],
  "gasPriceCoef" : "0",
  "gas" : 40000
}</code></pre>
</div>
</div>
</div>
<div class="sect3">
<h4 id="_cancel_a_pool_response_fields">Response fields</h4>
<table class="tableblock frame-all grid-all spread">
<colgroup>
<col style="width: 33%;">
<col style="width: 33%;">
<col style="width: 33%;">
</colgroup>
<thead>
<tr>
<th class="tableblock halign-left valign-top">Path</th>
<th class="tableblock halign-left valign-top">Type</th>
<th class="tableblock halign-left valign-top">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>gas</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>Number</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">The amount of gas to be used</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>gasPriceCoef</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>String</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">The gasprice coef to be used</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>clauses[]</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>Array</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">The different clauses included in the transaction</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>clauses[].to</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>String</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">The target address of the transaction</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>clauses[].amount</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>String</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">The vet amount (not in WEI!) included in the transaction</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>clauses[].data</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>String</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">The data for the transaction</p></td>
</tr>
</tbody>
</table>
</div>
<div class="sect3">
<h4 id="_cancel_a_pool_response_body">Response body</h4>
<div class="listingblock">
<div class="content">
<pre class="highlight nowrap"><code>{
  "clauses" : [ {
    "to" : "0x7b0eb37e542f8d18d0e13b1144f5309d947300d9",
    "amount" : "0",
    "data" : "0xea8a1af0"
  } ],
  "gasPriceCoef" : "0",
  "gas" : 40000
}</code></pre>
</div>
</div>
</div>
</div>
<div class="sect2">
<h3 id="_contribute_to_a_pool">Contribute to a pool</h3>
<div class="sect3">
<h4 id="_contribute_to_a_pool_curl_request">Example Curl request</h4>
<div class="listingblock">
<div class="content">
<pre class="highlight"><code class="language-bash" data-lang="bash">$ curl 'https://api.thorblock.io/api/pools/0x0fcd82A10Ab3ED65f11336a1e9Fa47eb58A01C42/contributions' -i -X POST \
    -H 'Content-Type: application/json' \
    -d '{
  "amount" : 100,
  "contributor" : "0x7f547f2f6b90f52011b2366f4febd558ddd56db4"
}'</code></pre>
</div>
</div>
</div>
<div class="sect3">
<h4 id="_contribute_to_a_pool_request_fields">Request fields</h4>
<table class="tableblock frame-all grid-all spread">
<colgroup>
<col style="width: 33%;">
<col style="width: 33%;">
<col style="width: 33%;">
</colgroup>
<thead>
<tr>
<th class="tableblock halign-left valign-top">Path</th>
<th class="tableblock halign-left valign-top">Type</th>
<th class="tableblock halign-left valign-top">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>amount</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>Number</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">The amount to contribute to the pool (in VET)</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>contributor</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>String</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">The contributor (the address of the person that will be recorded in the pool with the contribution)</p></td>
</tr>
</tbody>
</table>
</div>
<div class="sect3">
<h4 id="_contribute_to_a_pool_path_parameters">Path parameters</h4>
<table class="tableblock frame-all grid-all spread">
<caption class="title">Table 1. /api/pools/{poolAddress}/contributions</caption>
<colgroup>
<col style="width: 50%;">
<col style="width: 50%;">
</colgroup>
<thead>
<tr>
<th class="tableblock halign-left valign-top">Parameter</th>
<th class="tableblock halign-left valign-top">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>poolAddress</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">the address of the pool</p></td>
</tr>
</tbody>
</table>
</div>
<div class="sect3">
<h4 id="_contribute_to_a_pool_http_response">Example response</h4>
<div class="listingblock">
<div class="content">
<pre class="highlight nowrap"><code class="language-http" data-lang="http">HTTP/1.1 200 OK
Content-Type: application/json;charset=UTF-8
Content-Length: 238

{
  "clauses" : [ {
    "to" : "0x7b0eb37e542f8d18d0e13b1144f5309d947300d9",
    "amount" : "100",
    "data" : "0x73e888fd0000000000000000000000002cfc414feaca3f073768e61cdfcaaad75db2b773"
  } ],
  "gasPriceCoef" : "0",
  "gas" : 100000
}</code></pre>
</div>
</div>
</div>
<div class="sect3">
<h4 id="_contribute_to_a_pool_response_fields">Response fields</h4>
<table class="tableblock frame-all grid-all spread">
<colgroup>
<col style="width: 33%;">
<col style="width: 33%;">
<col style="width: 33%;">
</colgroup>
<thead>
<tr>
<th class="tableblock halign-left valign-top">Path</th>
<th class="tableblock halign-left valign-top">Type</th>
<th class="tableblock halign-left valign-top">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>gas</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>Number</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">The amount of gas to be used</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>gasPriceCoef</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>String</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">The gasprice coef to be used</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>clauses[]</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>Array</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">The different clauses included in the transaction</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>clauses[].to</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>String</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">The target address of the transaction</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>clauses[].amount</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>String</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">The vet amount (not in WEI!) included in the transaction</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>clauses[].data</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>String</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">The data for the transaction</p></td>
</tr>
</tbody>
</table>
</div>
<div class="sect3">
<h4 id="_contribute_to_a_pool_response_body">Response body</h4>
<div class="listingblock">
<div class="content">
<pre class="highlight nowrap"><code>{
  "clauses" : [ {
    "to" : "0x7b0eb37e542f8d18d0e13b1144f5309d947300d9",
    "amount" : "100",
    "data" : "0x73e888fd0000000000000000000000002cfc414feaca3f073768e61cdfcaaad75db2b773"
  } ],
  "gasPriceCoef" : "0",
  "gas" : 100000
}</code></pre>
</div>
</div>
</div>
</div>
<div class="sect2">
<h3 id="_revoke_contributions_from_a_pool">Revoke contributions from a pool</h3>
<div class="sect3">
<h4 id="_revoke_contributions_from_a_pool_curl_request">Example Curl request</h4>
<div class="listingblock">
<div class="content">
<pre class="highlight"><code class="language-bash" data-lang="bash">$ curl 'https://api.thorblock.io/api/pools/0x0fcd82A10Ab3ED65f11336a1e9Fa47eb58A01C42/contributions' -i -X DELETE \
    -H 'Content-Type: application/json'</code></pre>
</div>
</div>
</div>
<div class="sect3">
<h4 id="_revoke_contributions_from_a_pool_path_parameters">Path parameters</h4>
<table class="tableblock frame-all grid-all spread">
<caption class="title">Table 1. /api/pools/{poolAddress}/contributions</caption>
<colgroup>
<col style="width: 50%;">
<col style="width: 50%;">
</colgroup>
<thead>
<tr>
<th class="tableblock halign-left valign-top">Parameter</th>
<th class="tableblock halign-left valign-top">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>poolAddress</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">the address of the pool</p></td>
</tr>
</tbody>
</table>
</div>
<div class="sect3">
<h4 id="_revoke_contributions_from_a_pool_http_response">Example response</h4>
<div class="listingblock">
<div class="content">
<pre class="highlight nowrap"><code class="language-http" data-lang="http">HTTP/1.1 200 OK
Content-Type: application/json;charset=UTF-8
Content-Length: 171

{
  "clauses" : [ {
    "to" : "0x7b0eb37e542f8d18d0e13b1144f5309d947300d9",
    "amount" : "0",
    "data" : "0xb48309da"
  } ],
  "gasPriceCoef" : "0",
  "gas" : 30000
}</code></pre>
</div>
</div>
</div>
<div class="sect3">
<h4 id="_revoke_contributions_from_a_pool_response_fields">Response fields</h4>
<table class="tableblock frame-all grid-all spread">
<colgroup>
<col style="width: 33%;">
<col style="width: 33%;">
<col style="width: 33%;">
</colgroup>
<thead>
<tr>
<th class="tableblock halign-left valign-top">Path</th>
<th class="tableblock halign-left valign-top">Type</th>
<th class="tableblock halign-left valign-top">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>gas</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>Number</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">The amount of gas to be used</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>gasPriceCoef</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>String</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">The gasprice coef to be used</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>clauses[]</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>Array</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">The different clauses included in the transaction</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>clauses[].to</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>String</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">The target address of the transaction</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>clauses[].amount</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>String</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">The vet amount (not in WEI!) included in the transaction</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>clauses[].data</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>String</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">The data for the transaction</p></td>
</tr>
</tbody>
</table>
</div>
<div class="sect3">
<h4 id="_revoke_contributions_from_a_pool_response_body">Response body</h4>
<div class="listingblock">
<div class="content">
<pre class="highlight nowrap"><code>{
  "clauses" : [ {
    "to" : "0x7b0eb37e542f8d18d0e13b1144f5309d947300d9",
    "amount" : "0",
    "data" : "0xb48309da"
  } ],
  "gasPriceCoef" : "0",
  "gas" : 30000
}</code></pre>
</div>
</div>
</div>
</div>
<div class="sect2">
<h3 id="_set_destination_adress">Set destination adress</h3>
<div class="sect3">
<h4 id="_set_destination_adress_curl_request">Example Curl request</h4>
<div class="listingblock">
<div class="content">
<pre class="highlight"><code class="language-bash" data-lang="bash">$ curl 'https://api.thorblock.io/api/pools/0x0fcd82A10Ab3ED65f11336a1e9Fa47eb58A01C42/destinationaddress' -i -X POST \
    -H 'Content-Type: application/json' \
    -d '{
  "address" : "0x7f547f2f6b90f52011b2366f4febd558ddd56db4"
}'</code></pre>
</div>
</div>
</div>
<div class="sect3">
<h4 id="_set_destination_adress_path_parameters">Path parameters</h4>
<table class="tableblock frame-all grid-all spread">
<caption class="title">Table 1. /api/pools/{poolAddress}/destinationaddress</caption>
<colgroup>
<col style="width: 50%;">
<col style="width: 50%;">
</colgroup>
<thead>
<tr>
<th class="tableblock halign-left valign-top">Parameter</th>
<th class="tableblock halign-left valign-top">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>poolAddress</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">the address of the pool</p></td>
</tr>
</tbody>
</table>
</div>
<div class="sect3">
<h4 id="_set_destination_adress_request_fields">Request fields</h4>
<table class="tableblock frame-all grid-all spread">
<colgroup>
<col style="width: 33%;">
<col style="width: 33%;">
<col style="width: 33%;">
</colgroup>
<thead>
<tr>
<th class="tableblock halign-left valign-top">Path</th>
<th class="tableblock halign-left valign-top">Type</th>
<th class="tableblock halign-left valign-top">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>address</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>String</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">The new destination address</p></td>
</tr>
</tbody>
</table>
</div>
<div class="sect3">
<h4 id="_set_destination_adress_http_response">Example response</h4>
<div class="listingblock">
<div class="content">
<pre class="highlight nowrap"><code class="language-http" data-lang="http">HTTP/1.1 200 OK
Content-Type: application/json;charset=UTF-8
Content-Length: 236

{
  "clauses" : [ {
    "to" : "0x7b0eb37e542f8d18d0e13b1144f5309d947300d9",
    "amount" : "0",
    "data" : "0x7fa4cacb0000000000000000000000002cfc414feaca3f073768e61cdfcaaad75db2b773"
  } ],
  "gasPriceCoef" : "0",
  "gas" : 100000
}</code></pre>
</div>
</div>
</div>
<div class="sect3">
<h4 id="_set_destination_adress_response_fields">Response fields</h4>
<table class="tableblock frame-all grid-all spread">
<colgroup>
<col style="width: 33%;">
<col style="width: 33%;">
<col style="width: 33%;">
</colgroup>
<thead>
<tr>
<th class="tableblock halign-left valign-top">Path</th>
<th class="tableblock halign-left valign-top">Type</th>
<th class="tableblock halign-left valign-top">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>gas</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>Number</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">The amount of gas to be used</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>gasPriceCoef</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>String</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">The gasprice coef to be used</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>clauses[]</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>Array</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">The different clauses included in the transaction</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>clauses[].to</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>String</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">The target address of the transaction</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>clauses[].amount</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>String</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">The vet amount (not in WEI!) included in the transaction</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>clauses[].data</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>String</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">The data for the transaction</p></td>
</tr>
</tbody>
</table>
</div>
<div class="sect3">
<h4 id="_set_destination_adress_response_body">Response body</h4>
<div class="listingblock">
<div class="content">
<pre class="highlight nowrap"><code>{
  "clauses" : [ {
    "to" : "0x7b0eb37e542f8d18d0e13b1144f5309d947300d9",
    "amount" : "0",
    "data" : "0x7fa4cacb0000000000000000000000002cfc414feaca3f073768e61cdfcaaad75db2b773"
  } ],
  "gasPriceCoef" : "0",
  "gas" : 100000
}</code></pre>
</div>
</div>
</div>
</div>
<div class="sect2">
<h3 id="_set_token_adress">Set token adress</h3>
<div class="sect3">
<h4 id="_set_token_adress_curl_request">Example Curl request</h4>
<div class="listingblock">
<div class="content">
<pre class="highlight"><code class="language-bash" data-lang="bash">$ curl 'https://api.thorblock.io/api/pools/0x0fcd82A10Ab3ED65f11336a1e9Fa47eb58A01C42/tokenaddress' -i -X POST \
    -H 'Content-Type: application/json' \
    -d '{
  "address" : "0x7f547f2f6b90f52011b2366f4febd558ddd56db4"
}'</code></pre>
</div>
</div>
</div>
<div class="sect3">
<h4 id="_set_token_adress_request_fields">Request fields</h4>
<table class="tableblock frame-all grid-all spread">
<colgroup>
<col style="width: 33%;">
<col style="width: 33%;">
<col style="width: 33%;">
</colgroup>
<thead>
<tr>
<th class="tableblock halign-left valign-top">Path</th>
<th class="tableblock halign-left valign-top">Type</th>
<th class="tableblock halign-left valign-top">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>address</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>String</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">The new token address</p></td>
</tr>
</tbody>
</table>
</div>
<div class="sect3">
<h4 id="_set_token_adress_path_parameters">Path parameters</h4>
<table class="tableblock frame-all grid-all spread">
<caption class="title">Table 1. /api/pools/{poolAddress}/tokenaddress</caption>
<colgroup>
<col style="width: 50%;">
<col style="width: 50%;">
</colgroup>
<thead>
<tr>
<th class="tableblock halign-left valign-top">Parameter</th>
<th class="tableblock halign-left valign-top">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>poolAddress</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">the address of the pool</p></td>
</tr>
</tbody>
</table>
</div>
<div class="sect3">
<h4 id="_set_token_adress_http_response">Example response</h4>
<div class="listingblock">
<div class="content">
<pre class="highlight nowrap"><code class="language-http" data-lang="http">HTTP/1.1 200 OK
Content-Type: application/json;charset=UTF-8
Content-Length: 236

{
  "clauses" : [ {
    "to" : "0x7b0eb37e542f8d18d0e13b1144f5309d947300d9",
    "amount" : "0",
    "data" : "0x7fa4cacb0000000000000000000000002cfc414feaca3f073768e61cdfcaaad75db2b773"
  } ],
  "gasPriceCoef" : "0",
  "gas" : 100000
}</code></pre>
</div>
</div>
</div>
<div class="sect3">
<h4 id="_set_token_adress_response_fields">Response fields</h4>
<table class="tableblock frame-all grid-all spread">
<colgroup>
<col style="width: 33%;">
<col style="width: 33%;">
<col style="width: 33%;">
</colgroup>
<thead>
<tr>
<th class="tableblock halign-left valign-top">Path</th>
<th class="tableblock halign-left valign-top">Type</th>
<th class="tableblock halign-left valign-top">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>gas</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>Number</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">The amount of gas to be used</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>gasPriceCoef</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>String</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">The gasprice coef to be used</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>clauses[]</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>Array</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">The different clauses included in the transaction</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>clauses[].to</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>String</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">The target address of the transaction</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>clauses[].amount</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>String</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">The vet amount (not in WEI!) included in the transaction</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>clauses[].data</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>String</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">The data for the transaction</p></td>
</tr>
</tbody>
</table>
</div>
<div class="sect3">
<h4 id="_set_token_adress_response_body">Response body</h4>
<div class="listingblock">
<div class="content">
<pre class="highlight nowrap"><code>{
  "clauses" : [ {
    "to" : "0x7b0eb37e542f8d18d0e13b1144f5309d947300d9",
    "amount" : "0",
    "data" : "0x7fa4cacb0000000000000000000000002cfc414feaca3f073768e61cdfcaaad75db2b773"
  } ],
  "gasPriceCoef" : "0",
  "gas" : 100000
}</code></pre>
</div>
</div>
</div>
</div>
<div class="sect2">
<h3 id="_transfer_pool_funds">Transfer pool funds</h3>
<div class="paragraph">
<p>Will transfer all the funds of the pool to the destination address (ex. the crowdsale address).</p>
</div>
<div class="sect3">
<h4 id="_transfer_pool_funds_curl_request">Example Curl request</h4>
<div class="listingblock">
<div class="content">
<pre class="highlight"><code class="language-bash" data-lang="bash">$ curl 'https://api.thorblock.io/api/pools/0x0fcd82A10Ab3ED65f11336a1e9Fa47eb58A01C42/transferfunds' -i -X POST \
    -H 'Content-Type: application/json' \
    -d '{
  "data" : "0x7134cc7600000000000000000000000000000000000000000000000000000000000000037eeee5471896a43026452b46182020e90b37a20af68662b326c3d8852d312bb7a08b3cbadb934ae1b036147e240a1bab0f944876551e8c153fae26b6bd8bf46d"
}'</code></pre>
</div>
</div>
</div>
<div class="sect3">
<h4 id="_transfer_pool_funds_path_parameters">Path parameters</h4>
<table class="tableblock frame-all grid-all spread">
<caption class="title">Table 1. /api/pools/{poolAddress}/transferfunds</caption>
<colgroup>
<col style="width: 50%;">
<col style="width: 50%;">
</colgroup>
<thead>
<tr>
<th class="tableblock halign-left valign-top">Parameter</th>
<th class="tableblock halign-left valign-top">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>poolAddress</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">the address of the pool</p></td>
</tr>
</tbody>
</table>
</div>
<div class="sect3">
<h4 id="_transfer_pool_funds_request_fields">Request fields</h4>
<table class="tableblock frame-all grid-all spread">
<colgroup>
<col style="width: 33%;">
<col style="width: 33%;">
<col style="width: 33%;">
</colgroup>
<thead>
<tr>
<th class="tableblock halign-left valign-top">Path</th>
<th class="tableblock halign-left valign-top">Type</th>
<th class="tableblock halign-left valign-top">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>data</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>String</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">(Optional) Hex value of the data to be included in the transfer to the destination address</p></td>
</tr>
</tbody>
</table>
</div>
<div class="sect3">
<h4 id="_transfer_pool_funds_http_response">Example response</h4>
<div class="listingblock">
<div class="content">
<pre class="highlight nowrap"><code class="language-http" data-lang="http">HTTP/1.1 200 OK
Content-Type: application/json;charset=UTF-8
Content-Length: 171

{
  "clauses" : [ {
    "to" : "0x7b0eb37e542f8d18d0e13b1144f5309d947300d9",
    "amount" : "0",
    "data" : "0xb48309da"
  } ],
  "gasPriceCoef" : "0",
  "gas" : 30000
}</code></pre>
</div>
</div>
</div>
<div class="sect3">
<h4 id="_transfer_pool_funds_response_fields">Response fields</h4>
<table class="tableblock frame-all grid-all spread">
<colgroup>
<col style="width: 33%;">
<col style="width: 33%;">
<col style="width: 33%;">
</colgroup>
<thead>
<tr>
<th class="tableblock halign-left valign-top">Path</th>
<th class="tableblock halign-left valign-top">Type</th>
<th class="tableblock halign-left valign-top">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>gas</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>Number</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">The amount of gas to be used</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>gasPriceCoef</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>String</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">The gasprice coef to be used</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>clauses[]</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>Array</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">The different clauses included in the transaction</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>clauses[].to</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>String</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">The target address of the transaction</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>clauses[].amount</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>String</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">The vet amount (not in WEI!) included in the transaction</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>clauses[].data</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>String</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">The data for the transaction</p></td>
</tr>
</tbody>
</table>
</div>
<div class="sect3">
<h4 id="_transfer_pool_funds_response_body">Response body</h4>
<div class="listingblock">
<div class="content">
<pre class="highlight nowrap"><code>{
  "clauses" : [ {
    "to" : "0x7b0eb37e542f8d18d0e13b1144f5309d947300d9",
    "amount" : "0",
    "data" : "0xb48309da"
  } ],
  "gasPriceCoef" : "0",
  "gas" : 30000
}</code></pre>
</div>
</div>
</div>
</div>
<div class="sect2">
<h3 id="_distribute_pool_funds">Distribute pool funds</h3>
<div class="paragraph">
<p>When there are funds available for the contributors, call this endpoint. This will divide the funds to all contributors (who still have to call withDrawFunds to perform the actual withdraw)</p>
</div>
<div class="sect3">
<h4 id="_distribute_pool_funds_curl_request">Example Curl request</h4>
<div class="listingblock">
<div class="content">
<pre class="highlight"><code class="language-bash" data-lang="bash">$ curl 'https://api.thorblock.io/api/pools/poolAddress/distributefunds' -i -X POST \
    -H 'Content-Type: application/json'</code></pre>
</div>
</div>
</div>
<div class="sect3">
<h4 id="_distribute_pool_funds_path_parameters">Path parameters</h4>
<table class="tableblock frame-all grid-all spread">
<caption class="title">Table 1. /api/pools/{poolAddress}/distributefunds</caption>
<colgroup>
<col style="width: 50%;">
<col style="width: 50%;">
</colgroup>
<thead>
<tr>
<th class="tableblock halign-left valign-top">Parameter</th>
<th class="tableblock halign-left valign-top">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>poolAddress</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">the address of the pool</p></td>
</tr>
</tbody>
</table>
</div>
<div class="sect3">
<h4 id="_distribute_pool_funds_http_response">Example response</h4>
<div class="listingblock">
<div class="content">
<pre class="highlight nowrap"><code class="language-http" data-lang="http">HTTP/1.1 200 OK
Content-Type: application/json;charset=UTF-8
Content-Length: 173

{
  "clauses" : [ {
    "to" : "0x7b0eb37e542f8d18d0e13b1144f5309d947300d9",
    "amount" : "0",
    "data" : "0x3a6a4d2e"
  } ],
  "gasPriceCoef" : "0",
  "gas" : 1500000
}</code></pre>
</div>
</div>
</div>
<div class="sect3">
<h4 id="_distribute_pool_funds_response_fields">Response fields</h4>
<table class="tableblock frame-all grid-all spread">
<colgroup>
<col style="width: 33%;">
<col style="width: 33%;">
<col style="width: 33%;">
</colgroup>
<thead>
<tr>
<th class="tableblock halign-left valign-top">Path</th>
<th class="tableblock halign-left valign-top">Type</th>
<th class="tableblock halign-left valign-top">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>gas</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>Number</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">The amount of gas to be used</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>gasPriceCoef</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>String</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">The gasprice coef to be used</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>clauses[]</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>Array</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">The different clauses included in the transaction</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>clauses[].to</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>String</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">The target address of the transaction</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>clauses[].amount</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>String</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">The vet amount (not in WEI!) included in the transaction</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>clauses[].data</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>String</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">The data for the transaction</p></td>
</tr>
</tbody>
</table>
</div>
<div class="sect3">
<h4 id="_distribute_pool_funds_response_body">Response body</h4>
<div class="listingblock">
<div class="content">
<pre class="highlight nowrap"><code>{
  "clauses" : [ {
    "to" : "0x7b0eb37e542f8d18d0e13b1144f5309d947300d9",
    "amount" : "0",
    "data" : "0x3a6a4d2e"
  } ],
  "gasPriceCoef" : "0",
  "gas" : 1500000
}</code></pre>
</div>
</div>
</div>
</div>
<div class="sect2">
<h3 id="_withdraw_funds">Withdraw funds</h3>
<div class="paragraph">
<p>Allows contributors to withdraw tokens / vet from the contract</p>
</div>
<div class="sect3">
<h4 id="_withdraw_funds_curl_request">Example Curl request</h4>
<div class="listingblock">
<div class="content">
<pre class="highlight"><code class="language-bash" data-lang="bash">$ curl 'https://api.thorblock.io/api/pools/0x0fcd82A10Ab3ED65f11336a1e9Fa47eb58A01C42/withdraw' -i -X POST</code></pre>
</div>
</div>
</div>
<div class="sect3">
<h4 id="_withdraw_funds_path_parameters">Path parameters</h4>
<table class="tableblock frame-all grid-all spread">
<caption class="title">Table 1. /api/pools/{poolAddress}/withdraw</caption>
<colgroup>
<col style="width: 50%;">
<col style="width: 50%;">
</colgroup>
<thead>
<tr>
<th class="tableblock halign-left valign-top">Parameter</th>
<th class="tableblock halign-left valign-top">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>poolAddress</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">the address of the pool</p></td>
</tr>
</tbody>
</table>
</div>
<div class="sect3">
<h4 id="_withdraw_funds_http_response">Example response</h4>
<div class="listingblock">
<div class="content">
<pre class="highlight nowrap"><code class="language-http" data-lang="http">HTTP/1.1 200 OK
Content-Type: application/json;charset=UTF-8
Content-Length: 238

{
  "clauses" : [ {
    "to" : "0x7b0eb37e542f8d18d0e13b1144f5309d947300d9",
    "amount" : "100",
    "data" : "0x73e888fd0000000000000000000000002cfc414feaca3f073768e61cdfcaaad75db2b773"
  } ],
  "gasPriceCoef" : "0",
  "gas" : 100000
}</code></pre>
</div>
</div>
</div>
<div class="sect3">
<h4 id="_withdraw_funds_response_fields">Response fields</h4>
<table class="tableblock frame-all grid-all spread">
<colgroup>
<col style="width: 33%;">
<col style="width: 33%;">
<col style="width: 33%;">
</colgroup>
<thead>
<tr>
<th class="tableblock halign-left valign-top">Path</th>
<th class="tableblock halign-left valign-top">Type</th>
<th class="tableblock halign-left valign-top">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>gas</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>Number</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">The amount of gas to be used</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>gasPriceCoef</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>String</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">The gasprice coef to be used</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>clauses[]</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>Array</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">The different clauses included in the transaction</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>clauses[].to</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>String</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">The target address of the transaction</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>clauses[].amount</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>String</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">The vet amount (not in WEI!) included in the transaction</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>clauses[].data</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>String</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">The data for the transaction</p></td>
</tr>
</tbody>
</table>
</div>
<div class="sect3">
<h4 id="_withdraw_funds_response_body">Response body</h4>
<div class="listingblock">
<div class="content">
<pre class="highlight nowrap"><code>{
  "clauses" : [ {
    "to" : "0x7b0eb37e542f8d18d0e13b1144f5309d947300d9",
    "amount" : "100",
    "data" : "0x73e888fd0000000000000000000000002cfc414feaca3f073768e61cdfcaaad75db2b773"
  } ],
  "gasPriceCoef" : "0",
  "gas" : 100000
}</code></pre>
</div>
</div>
</div>
</div>
<div class="sect2">
<h3 id="_withdrawal_balance">Withdrawal balance</h3>
<div class="paragraph">
<p>See the amount of VET/tokens you can withdraw</p>
</div>
<div class="sect3">
<h4 id="_withdrawal_balance_curl_request">Example Curl request</h4>
<div class="listingblock">
<div class="content">
<pre class="highlight"><code class="language-bash" data-lang="bash">$ curl 'https://api.thorblock.io/api/pools/0x0fcd82A10Ab3ED65f11336a1e9Fa47eb58A01C42/contributions/0x7f547f2f6b90f52011b2366f4febd558ddd56db4/withdrawalbalance' -i -X GET</code></pre>
</div>
</div>
</div>
<div class="sect3">
<h4 id="_withdrawal_balance_path_parameters">Path parameters</h4>
<table class="tableblock frame-all grid-all spread">
<caption class="title">Table 1. /api/pools/{poolAddress}/contributions/{contributor}/withdrawalbalance</caption>
<colgroup>
<col style="width: 50%;">
<col style="width: 50%;">
</colgroup>
<thead>
<tr>
<th class="tableblock halign-left valign-top">Parameter</th>
<th class="tableblock halign-left valign-top">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>poolAddress</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">the address of the pool</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>contributor</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">the contributor to show the withdrawal balance for</p></td>
</tr>
</tbody>
</table>
</div>
<div class="sect3">
<h4 id="_withdrawal_balance_http_response">Example response</h4>
<div class="listingblock">
<div class="content">
<pre class="highlight nowrap"><code class="language-http" data-lang="http">HTTP/1.1 200 OK
Content-Type: application/json;charset=UTF-8
Content-Length: 91

{
  "tokensToWithdraw" : 100000000000000000000,
  "weiToWithdraw" : 100000000000000000000
}</code></pre>
</div>
</div>
</div>
<div class="sect3">
<h4 id="_withdrawal_balance_response_fields">Response fields</h4>
<table class="tableblock frame-all grid-all spread">
<colgroup>
<col style="width: 33%;">
<col style="width: 33%;">
<col style="width: 33%;">
</colgroup>
<thead>
<tr>
<th class="tableblock halign-left valign-top">Path</th>
<th class="tableblock halign-left valign-top">Type</th>
<th class="tableblock halign-left valign-top">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>tokensToWithdraw</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>Number</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">Amount of withdrawable tokens (in WEI)</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>weiToWithdraw</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>Number</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">Amount of VET to withdraw (in WEI)</p></td>
</tr>
</tbody>
</table>
</div>
<div class="sect3">
<h4 id="_withdrawal_balance_response_body">Response body</h4>
<div class="listingblock">
<div class="content">
<pre class="highlight nowrap"><code>{
  "tokensToWithdraw" : 100000000000000000000,
  "weiToWithdraw" : 100000000000000000000
}</code></pre>
</div>
</div>
</div>
</div>
<div class="sect2">
<h3 id="_update_whitelist">Update whitelist</h3>
<div class="sect3">
<h4 id="_update_whitelist_curl_request">Example Curl request</h4>
<div class="listingblock">
<div class="content">
<pre class="highlight"><code class="language-bash" data-lang="bash">$ curl 'https://api.thorblock.io/api/pools/0x0fcd82A10Ab3ED65f11336a1e9Fa47eb58A01C42/whitelist' -i -X POST \
    -H 'Content-Type: application/json' \
    -d '{
  "contributors" : [ "0x7f547f2f6b90f52011b2366f4febd558ddd56db4" ],
  "allowed" : true
}'</code></pre>
</div>
</div>
</div>
<div class="sect3">
<h4 id="_update_whitelist_path_parameters">Path parameters</h4>
<table class="tableblock frame-all grid-all spread">
<caption class="title">Table 1. /api/pools/{poolAddress}/whitelist</caption>
<colgroup>
<col style="width: 50%;">
<col style="width: 50%;">
</colgroup>
<thead>
<tr>
<th class="tableblock halign-left valign-top">Parameter</th>
<th class="tableblock halign-left valign-top">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>poolAddress</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">the address of the pool</p></td>
</tr>
</tbody>
</table>
</div>
<div class="sect3">
<h4 id="_update_whitelist_request_fields">Request fields</h4>
<table class="tableblock frame-all grid-all spread">
<colgroup>
<col style="width: 33%;">
<col style="width: 33%;">
<col style="width: 33%;">
</colgroup>
<thead>
<tr>
<th class="tableblock halign-left valign-top">Path</th>
<th class="tableblock halign-left valign-top">Type</th>
<th class="tableblock halign-left valign-top">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>contributors</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>Array</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">List of contributors to update in the whitelist</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>allowed</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>Boolean</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">True to add to whitelist, false to remove</p></td>
</tr>
</tbody>
</table>
</div>
<div class="sect3">
<h4 id="_update_whitelist_http_response">Example response</h4>
<div class="listingblock">
<div class="content">
<pre class="highlight nowrap"><code class="language-http" data-lang="http">HTTP/1.1 200 OK
Content-Type: application/json;charset=UTF-8
Content-Length: 428

{
  "clauses" : [ {
    "to" : "0x7b0eb37e542f8d18d0e13b1144f5309d947300d9",
    "amount" : "0",
    "data" : "0x6560f8db0000000000000000000000000000000000000000000000000000000000000040000000000000000000000000000000000000000000000000000000000000000100000000000000000000000000000000000000000000000000000000000000010000000000000000000000002cfc414feaca3f073768e61cdfcaaad75db2b773"
  } ],
  "gasPriceCoef" : "0",
  "gas" : 100000
}</code></pre>
</div>
</div>
</div>
<div class="sect3">
<h4 id="_update_whitelist_response_fields">Response fields</h4>
<table class="tableblock frame-all grid-all spread">
<colgroup>
<col style="width: 33%;">
<col style="width: 33%;">
<col style="width: 33%;">
</colgroup>
<thead>
<tr>
<th class="tableblock halign-left valign-top">Path</th>
<th class="tableblock halign-left valign-top">Type</th>
<th class="tableblock halign-left valign-top">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>gas</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>Number</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">The amount of gas to be used</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>gasPriceCoef</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>String</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">The gasprice coef to be used</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>clauses[]</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>Array</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">The different clauses included in the transaction</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>clauses[].to</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>String</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">The target address of the transaction</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>clauses[].amount</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>String</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">The vet amount (not in WEI!) included in the transaction</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>clauses[].data</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>String</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">The data for the transaction</p></td>
</tr>
</tbody>
</table>
</div>
<div class="sect3">
<h4 id="_update_whitelist_response_body">Response body</h4>
<div class="listingblock">
<div class="content">
<pre class="highlight nowrap"><code>{
  "clauses" : [ {
    "to" : "0x7b0eb37e542f8d18d0e13b1144f5309d947300d9",
    "amount" : "0",
    "data" : "0x6560f8db0000000000000000000000000000000000000000000000000000000000000040000000000000000000000000000000000000000000000000000000000000000100000000000000000000000000000000000000000000000000000000000000010000000000000000000000002cfc414feaca3f073768e61cdfcaaad75db2b773"
  } ],
  "gasPriceCoef" : "0",
  "gas" : 100000
}</code></pre>
</div>
</div>
</div>
</div>
<div class="sect2">
<h3 id="_whitelist_count">Whitelist count</h3>
<div class="paragraph">
<p>Returns the number of contributors in the whitelist</p>
</div>
<div class="sect3">
<h4 id="_whitelist_count_curl_request">Example Curl request</h4>
<div class="listingblock">
<div class="content">
<pre class="highlight"><code class="language-bash" data-lang="bash">$ curl 'https://api.thorblock.io/api/pools/0x0fcd82A10Ab3ED65f11336a1e9Fa47eb58A01C42/whitelist' -i -X GET</code></pre>
</div>
</div>
</div>
<div class="sect3">
<h4 id="_whitelist_count_path_parameters">Path parameters</h4>
<table class="tableblock frame-all grid-all spread">
<caption class="title">Table 1. /api/pools/{poolAddress}/whitelist</caption>
<colgroup>
<col style="width: 50%;">
<col style="width: 50%;">
</colgroup>
<thead>
<tr>
<th class="tableblock halign-left valign-top">Parameter</th>
<th class="tableblock halign-left valign-top">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>poolAddress</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">the address of the pool</p></td>
</tr>
</tbody>
</table>
</div>
<div class="sect3">
<h4 id="_whitelist_count_http_response">Example response</h4>
<div class="listingblock">
<div class="content">
<pre class="highlight nowrap"><code class="language-http" data-lang="http">HTTP/1.1 200 OK
Content-Type: application/json;charset=UTF-8
Content-Length: 18

{
  "result" : 1
}</code></pre>
</div>
</div>
</div>
<div class="sect3">
<h4 id="_whitelist_count_response_fields">Response fields</h4>
<table class="tableblock frame-all grid-all spread">
<colgroup>
<col style="width: 33%;">
<col style="width: 33%;">
<col style="width: 33%;">
</colgroup>
<thead>
<tr>
<th class="tableblock halign-left valign-top">Path</th>
<th class="tableblock halign-left valign-top">Type</th>
<th class="tableblock halign-left valign-top">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>result</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>Number</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">The number of contributors in the whitelist</p></td>
</tr>
</tbody>
</table>
</div>
<div class="sect3">
<h4 id="_whitelist_count_response_body">Response body</h4>
<div class="listingblock">
<div class="content">
<pre class="highlight nowrap"><code>{
  "result" : 1
}</code></pre>
</div>
</div>
</div>
</div>
<div class="sect2">
<h3 id="_whitelist_check">Whitelist check</h3>
<div class="sect3">
<h4 id="_whitelist_check_curl_request">Example Curl request</h4>
<div class="listingblock">
<div class="content">
<pre class="highlight"><code class="language-bash" data-lang="bash">$ curl 'https://api.thorblock.io/api/pools/0x0fcd82A10Ab3ED65f11336a1e9Fa47eb58A01C42/whitelist/0x7f547f2f6b90f52011b2366f4febd558ddd56db4' -i -X GET</code></pre>
</div>
</div>
</div>
<div class="sect3">
<h4 id="_whitelist_check_path_parameters">Path parameters</h4>
<table class="tableblock frame-all grid-all spread">
<caption class="title">Table 1. /api/pools/{poolAddress}/whitelist/{contributor}</caption>
<colgroup>
<col style="width: 50%;">
<col style="width: 50%;">
</colgroup>
<thead>
<tr>
<th class="tableblock halign-left valign-top">Parameter</th>
<th class="tableblock halign-left valign-top">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>poolAddress</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">the address of the pool</p></td>
</tr>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>contributor</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">the address of the contributor to check if whitelisted or not</p></td>
</tr>
</tbody>
</table>
</div>
<div class="sect3">
<h4 id="_whitelist_check_http_response">Example response</h4>
<div class="listingblock">
<div class="content">
<pre class="highlight nowrap"><code class="language-http" data-lang="http">HTTP/1.1 200 OK
Content-Type: application/json;charset=UTF-8
Content-Length: 21

{
  "result" : true
}</code></pre>
</div>
</div>
</div>
<div class="sect3">
<h4 id="_whitelist_check_response_fields">Response fields</h4>
<table class="tableblock frame-all grid-all spread">
<colgroup>
<col style="width: 33%;">
<col style="width: 33%;">
<col style="width: 33%;">
</colgroup>
<thead>
<tr>
<th class="tableblock halign-left valign-top">Path</th>
<th class="tableblock halign-left valign-top">Type</th>
<th class="tableblock halign-left valign-top">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>result</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock"><code>Boolean</code></p></td>
<td class="tableblock halign-left valign-top"><p class="tableblock">True if whitelisted, false otherwise</p></td>
</tr>
</tbody>
</table>
</div>
<div class="sect3">
<h4 id="_whitelist_check_response_body">Response body</h4>
<div class="listingblock">
<div class="content">
<pre class="highlight nowrap"><code>{
  "result" : true
}</code></pre>
</div>
</div>
</div>
</div>
</div>
</div>
</div>
<div id="footer">
<div id="footer-text">
Version 1.0<br>
Last updated 2018-09-25 15:40:38 CEST
</div>
</div>
<script data-cfasync="false" src="/cdn-cgi/scripts/5c5dd728/cloudflare-static/email-decode.min.js"></script></body>
</html>
