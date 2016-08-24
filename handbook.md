<!DOCTYPE html>
<html>
  <head>
      <meta charset="utf-8" />
      <title>handbook</title>
      <style>.markdown-preview:not([data-use-github-style]) { padding: 2em; font-size: 1.2em; color: rgb(171, 178, 191); overflow: auto; background-color: rgb(40, 44, 52); }
.markdown-preview:not([data-use-github-style]) > :first-child { margin-top: 0px; }
.markdown-preview:not([data-use-github-style]) h1, .markdown-preview:not([data-use-github-style]) h2, .markdown-preview:not([data-use-github-style]) h3, .markdown-preview:not([data-use-github-style]) h4, .markdown-preview:not([data-use-github-style]) h5, .markdown-preview:not([data-use-github-style]) h6 { line-height: 1.2; margin-top: 1.5em; margin-bottom: 0.5em; color: rgb(255, 255, 255); }
.markdown-preview:not([data-use-github-style]) h1 { font-size: 2.4em; font-weight: 300; }
.markdown-preview:not([data-use-github-style]) h2 { font-size: 1.8em; font-weight: 400; }
.markdown-preview:not([data-use-github-style]) h3 { font-size: 1.5em; font-weight: 500; }
.markdown-preview:not([data-use-github-style]) h4 { font-size: 1.2em; font-weight: 600; }
.markdown-preview:not([data-use-github-style]) h5 { font-size: 1.1em; font-weight: 600; }
.markdown-preview:not([data-use-github-style]) h6 { font-size: 1em; font-weight: 600; }
.markdown-preview:not([data-use-github-style]) strong { color: rgb(255, 255, 255); }
.markdown-preview:not([data-use-github-style]) del { color: rgb(124, 135, 156); }
.markdown-preview:not([data-use-github-style]) a, .markdown-preview:not([data-use-github-style]) a code { color: rgb(82, 139, 255); }
.markdown-preview:not([data-use-github-style]) img { max-width: 100%; }
.markdown-preview:not([data-use-github-style]) > p { margin-top: 0px; margin-bottom: 1.5em; }
.markdown-preview:not([data-use-github-style]) > ul, .markdown-preview:not([data-use-github-style]) > ol { margin-bottom: 1.5em; }
.markdown-preview:not([data-use-github-style]) blockquote { margin: 1.5em 0px; font-size: inherit; color: rgb(124, 135, 156); border-color: rgb(75, 83, 98); border-width: 4px; }
.markdown-preview:not([data-use-github-style]) hr { margin: 3em 0px; border-top-width: 2px; border-top-style: dashed; border-top-color: rgb(75, 83, 98); background: none; }
.markdown-preview:not([data-use-github-style]) table { margin: 1.5em 0px; }
.markdown-preview:not([data-use-github-style]) th { color: rgb(255, 255, 255); }
.markdown-preview:not([data-use-github-style]) th, .markdown-preview:not([data-use-github-style]) td { padding: 0.66em 1em; border: 1px solid rgb(75, 83, 98); }
.markdown-preview:not([data-use-github-style]) code { color: rgb(255, 255, 255); background-color: rgb(58, 63, 75); }
.markdown-preview:not([data-use-github-style]) pre.editor-colors { margin: 1.5em 0px; padding: 1em; font-size: 0.92em; border-radius: 3px; background-color: rgb(49, 54, 63); }
.markdown-preview:not([data-use-github-style]) kbd { color: rgb(255, 255, 255); border-width: 1px 1px 2px; border-style: solid; border-color: rgb(75, 83, 98) rgb(75, 83, 98) rgb(62, 68, 81); background-color: rgb(58, 63, 75); }
.markdown-preview[data-use-github-style] { font-family: 'Helvetica Neue', Helvetica, 'Segoe UI', Arial, freesans, sans-serif; line-height: 1.6; word-wrap: break-word; padding: 30px; font-size: 16px; color: rgb(51, 51, 51); overflow: scroll; background-color: rgb(255, 255, 255); }
.markdown-preview[data-use-github-style] > :first-child { margin-top: 0px !important; }
.markdown-preview[data-use-github-style] > :last-child { margin-bottom: 0px !important; }
.markdown-preview[data-use-github-style] a:not([href]) { color: inherit; text-decoration: none; }
.markdown-preview[data-use-github-style] .absent { color: rgb(204, 0, 0); }
.markdown-preview[data-use-github-style] .anchor { position: absolute; top: 0px; left: 0px; display: block; padding-right: 6px; padding-left: 30px; margin-left: -30px; }
.markdown-preview[data-use-github-style] .anchor:focus { outline: none; }
.markdown-preview[data-use-github-style] h1, .markdown-preview[data-use-github-style] h2, .markdown-preview[data-use-github-style] h3, .markdown-preview[data-use-github-style] h4, .markdown-preview[data-use-github-style] h5, .markdown-preview[data-use-github-style] h6 { position: relative; margin-top: 1em; margin-bottom: 16px; font-weight: bold; line-height: 1.4; }
.markdown-preview[data-use-github-style] h1 .octicon-link, .markdown-preview[data-use-github-style] h2 .octicon-link, .markdown-preview[data-use-github-style] h3 .octicon-link, .markdown-preview[data-use-github-style] h4 .octicon-link, .markdown-preview[data-use-github-style] h5 .octicon-link, .markdown-preview[data-use-github-style] h6 .octicon-link { display: none; color: rgb(0, 0, 0); vertical-align: middle; }
.markdown-preview[data-use-github-style] h1:hover .anchor, .markdown-preview[data-use-github-style] h2:hover .anchor, .markdown-preview[data-use-github-style] h3:hover .anchor, .markdown-preview[data-use-github-style] h4:hover .anchor, .markdown-preview[data-use-github-style] h5:hover .anchor, .markdown-preview[data-use-github-style] h6:hover .anchor { padding-left: 8px; margin-left: -30px; text-decoration: none; }
.markdown-preview[data-use-github-style] h1:hover .anchor .octicon-link, .markdown-preview[data-use-github-style] h2:hover .anchor .octicon-link, .markdown-preview[data-use-github-style] h3:hover .anchor .octicon-link, .markdown-preview[data-use-github-style] h4:hover .anchor .octicon-link, .markdown-preview[data-use-github-style] h5:hover .anchor .octicon-link, .markdown-preview[data-use-github-style] h6:hover .anchor .octicon-link { display: inline-block; }
.markdown-preview[data-use-github-style] h1 tt, .markdown-preview[data-use-github-style] h2 tt, .markdown-preview[data-use-github-style] h3 tt, .markdown-preview[data-use-github-style] h4 tt, .markdown-preview[data-use-github-style] h5 tt, .markdown-preview[data-use-github-style] h6 tt, .markdown-preview[data-use-github-style] h1 code, .markdown-preview[data-use-github-style] h2 code, .markdown-preview[data-use-github-style] h3 code, .markdown-preview[data-use-github-style] h4 code, .markdown-preview[data-use-github-style] h5 code, .markdown-preview[data-use-github-style] h6 code { font-size: inherit; }
.markdown-preview[data-use-github-style] h1 { padding-bottom: 0.3em; font-size: 2.25em; line-height: 1.2; border-bottom-width: 1px; border-bottom-style: solid; border-bottom-color: rgb(238, 238, 238); }
.markdown-preview[data-use-github-style] h1 .anchor { line-height: 1; }
.markdown-preview[data-use-github-style] h2 { padding-bottom: 0.3em; font-size: 1.75em; line-height: 1.225; border-bottom-width: 1px; border-bottom-style: solid; border-bottom-color: rgb(238, 238, 238); }
.markdown-preview[data-use-github-style] h2 .anchor { line-height: 1; }
.markdown-preview[data-use-github-style] h3 { font-size: 1.5em; line-height: 1.43; }
.markdown-preview[data-use-github-style] h3 .anchor { line-height: 1.2; }
.markdown-preview[data-use-github-style] h4 { font-size: 1.25em; }
.markdown-preview[data-use-github-style] h4 .anchor { line-height: 1.2; }
.markdown-preview[data-use-github-style] h5 { font-size: 1em; }
.markdown-preview[data-use-github-style] h5 .anchor { line-height: 1.1; }
.markdown-preview[data-use-github-style] h6 { font-size: 1em; color: rgb(119, 119, 119); }
.markdown-preview[data-use-github-style] h6 .anchor { line-height: 1.1; }
.markdown-preview[data-use-github-style] p, .markdown-preview[data-use-github-style] blockquote, .markdown-preview[data-use-github-style] ul, .markdown-preview[data-use-github-style] ol, .markdown-preview[data-use-github-style] dl, .markdown-preview[data-use-github-style] table, .markdown-preview[data-use-github-style] pre { margin-top: 0px; margin-bottom: 16px; }
.markdown-preview[data-use-github-style] hr { height: 4px; padding: 0px; margin: 16px 0px; border: 0px none; background-color: rgb(231, 231, 231); }
.markdown-preview[data-use-github-style] ul, .markdown-preview[data-use-github-style] ol { padding-left: 2em; }
.markdown-preview[data-use-github-style] ul.no-list, .markdown-preview[data-use-github-style] ol.no-list { padding: 0px; list-style-type: none; }
.markdown-preview[data-use-github-style] ul ul, .markdown-preview[data-use-github-style] ul ol, .markdown-preview[data-use-github-style] ol ol, .markdown-preview[data-use-github-style] ol ul { margin-top: 0px; margin-bottom: 0px; }
.markdown-preview[data-use-github-style] li > p { margin-top: 16px; }
.markdown-preview[data-use-github-style] dl { padding: 0px; }
.markdown-preview[data-use-github-style] dl dt { padding: 0px; margin-top: 16px; font-size: 1em; font-style: italic; font-weight: bold; }
.markdown-preview[data-use-github-style] dl dd { padding: 0px 16px; margin-bottom: 16px; }
.markdown-preview[data-use-github-style] blockquote { padding: 0px 15px; color: rgb(119, 119, 119); border-left-width: 4px; border-left-style: solid; border-left-color: rgb(221, 221, 221); }
.markdown-preview[data-use-github-style] blockquote > :first-child { margin-top: 0px; }
.markdown-preview[data-use-github-style] blockquote > :last-child { margin-bottom: 0px; }
.markdown-preview[data-use-github-style] table { display: block; width: 100%; overflow: auto; word-break: keep-all; }
.markdown-preview[data-use-github-style] table th { font-weight: bold; }
.markdown-preview[data-use-github-style] table th, .markdown-preview[data-use-github-style] table td { padding: 6px 13px; border: 1px solid rgb(221, 221, 221); }
.markdown-preview[data-use-github-style] table tr { border-top-width: 1px; border-top-style: solid; border-top-color: rgb(204, 204, 204); background-color: rgb(255, 255, 255); }
.markdown-preview[data-use-github-style] table tr:nth-child(2n) { background-color: rgb(248, 248, 248); }
.markdown-preview[data-use-github-style] img { max-width: 100%; box-sizing: border-box; }
.markdown-preview[data-use-github-style] .emoji { max-width: none; }
.markdown-preview[data-use-github-style] span.frame { display: block; overflow: hidden; }
.markdown-preview[data-use-github-style] span.frame > span { display: block; float: left; width: auto; padding: 7px; margin: 13px 0px 0px; overflow: hidden; border: 1px solid rgb(221, 221, 221); }
.markdown-preview[data-use-github-style] span.frame span img { display: block; float: left; }
.markdown-preview[data-use-github-style] span.frame span span { display: block; padding: 5px 0px 0px; clear: both; color: rgb(51, 51, 51); }
.markdown-preview[data-use-github-style] span.align-center { display: block; overflow: hidden; clear: both; }
.markdown-preview[data-use-github-style] span.align-center > span { display: block; margin: 13px auto 0px; overflow: hidden; text-align: center; }
.markdown-preview[data-use-github-style] span.align-center span img { margin: 0px auto; text-align: center; }
.markdown-preview[data-use-github-style] span.align-right { display: block; overflow: hidden; clear: both; }
.markdown-preview[data-use-github-style] span.align-right > span { display: block; margin: 13px 0px 0px; overflow: hidden; text-align: right; }
.markdown-preview[data-use-github-style] span.align-right span img { margin: 0px; text-align: right; }
.markdown-preview[data-use-github-style] span.float-left { display: block; float: left; margin-right: 13px; overflow: hidden; }
.markdown-preview[data-use-github-style] span.float-left span { margin: 13px 0px 0px; }
.markdown-preview[data-use-github-style] span.float-right { display: block; float: right; margin-left: 13px; overflow: hidden; }
.markdown-preview[data-use-github-style] span.float-right > span { display: block; margin: 13px auto 0px; overflow: hidden; text-align: right; }
.markdown-preview[data-use-github-style] code, .markdown-preview[data-use-github-style] tt { padding: 0.2em 0px; margin: 0px; font-size: 85%; border-radius: 3px; background-color: rgba(0, 0, 0, 0.0392157); }
.markdown-preview[data-use-github-style] code::before, .markdown-preview[data-use-github-style] tt::before, .markdown-preview[data-use-github-style] code::after, .markdown-preview[data-use-github-style] tt::after { letter-spacing: -0.2em; content: " "; }
.markdown-preview[data-use-github-style] code br, .markdown-preview[data-use-github-style] tt br { display: none; }
.markdown-preview[data-use-github-style] del code { text-decoration: inherit; }
.markdown-preview[data-use-github-style] pre > code { padding: 0px; margin: 0px; font-size: 100%; word-break: normal; white-space: pre; border: 0px; background: transparent; }
.markdown-preview[data-use-github-style] .highlight { margin-bottom: 16px; }
.markdown-preview[data-use-github-style] .highlight pre, .markdown-preview[data-use-github-style] pre { padding: 16px; overflow: auto; font-size: 85%; line-height: 1.45; border-radius: 3px; background-color: rgb(247, 247, 247); }
.markdown-preview[data-use-github-style] .highlight pre { margin-bottom: 0px; word-break: normal; }
.markdown-preview[data-use-github-style] pre { word-wrap: normal; }
.markdown-preview[data-use-github-style] pre code, .markdown-preview[data-use-github-style] pre tt { display: inline; max-width: initial; padding: 0px; margin: 0px; overflow: initial; line-height: inherit; word-wrap: normal; border: 0px; background-color: transparent; }
.markdown-preview[data-use-github-style] pre code::before, .markdown-preview[data-use-github-style] pre tt::before, .markdown-preview[data-use-github-style] pre code::after, .markdown-preview[data-use-github-style] pre tt::after { content: normal; }
.markdown-preview[data-use-github-style] kbd { display: inline-block; padding: 3px 5px; font-size: 11px; line-height: 10px; color: rgb(85, 85, 85); vertical-align: middle; border-style: solid; border-width: 1px; border-color: rgb(204, 204, 204) rgb(204, 204, 204) rgb(187, 187, 187); border-radius: 3px; box-shadow: rgb(187, 187, 187) 0px -1px 0px inset; background-color: rgb(252, 252, 252); }
.markdown-preview[data-use-github-style] a { color: rgb(51, 122, 183); }
.markdown-preview[data-use-github-style] code { color: inherit; }
.markdown-preview[data-use-github-style] pre.editor-colors { padding: 0.8em 1em; margin-bottom: 1em; font-size: 0.85em; border-radius: 4px; overflow: auto; }
.scrollbars-visible-always .markdown-preview pre.editor-colors::shadow .vertical-scrollbar, .scrollbars-visible-always .markdown-preview pre.editor-colors::shadow .horizontal-scrollbar { visibility: hidden; }
.scrollbars-visible-always .markdown-preview pre.editor-colors:hover::shadow .vertical-scrollbar, .scrollbars-visible-always .markdown-preview pre.editor-colors:hover::shadow .horizontal-scrollbar { visibility: visible; }
.bracket-matcher .region {
  border-bottom: 1px dotted lime;
  position: absolute;
}

.spell-check-misspelling .region {
  border-bottom: 2px dotted rgba(255, 51, 51, 0.75);
}

pre.editor-colors,
.host {
  background-color: #282c34;
  color: #abb2bf;
}
pre.editor-colors .line.cursor-line,
.host .line.cursor-line {
  background-color: rgba(153, 187, 255, 0.04);
}
pre.editor-colors .invisible,
.host .invisible {
  color: #abb2bf;
}
pre.editor-colors .cursor,
.host .cursor {
  border-left: 2px solid #528bff;
}
pre.editor-colors .selection .region,
.host .selection .region {
  background-color: #3e4451;
}
pre.editor-colors .bracket-matcher .region,
.host .bracket-matcher .region {
  border-bottom: 1px solid #528bff;
  box-sizing: border-box;
}
pre.editor-colors .invisible-character,
.host .invisible-character {
  color: rgba(171, 178, 191, 0.15);
}
pre.editor-colors .indent-guide,
.host .indent-guide {
  color: rgba(171, 178, 191, 0.15);
}
pre.editor-colors .wrap-guide,
.host .wrap-guide {
  background-color: rgba(171, 178, 191, 0.15);
}
pre.editor-colors .gutter .line-number,
.host .gutter .line-number {
  color: #636d83;
  -webkit-font-smoothing: antialiased;
}
pre.editor-colors .gutter .line-number.cursor-line,
.host .gutter .line-number.cursor-line {
  color: #abb2bf;
  background-color: #2c313a;
}
pre.editor-colors .gutter .line-number.cursor-line-no-selection,
.host .gutter .line-number.cursor-line-no-selection {
  background-color: transparent;
}
pre.editor-colors .gutter .line-number .icon-right,
.host .gutter .line-number .icon-right {
  color: #abb2bf;
}
pre.editor-colors .gutter:not(.git-diff-icon) .line-number.git-line-removed.git-line-removed::before,
.host .gutter:not(.git-diff-icon) .line-number.git-line-removed.git-line-removed::before {
  bottom: -3px;
}
pre.editor-colors .gutter:not(.git-diff-icon) .line-number.git-line-removed::after,
.host .gutter:not(.git-diff-icon) .line-number.git-line-removed::after {
  content: "";
  position: absolute;
  left: 0px;
  bottom: 0px;
  width: 25px;
  border-bottom: 1px dotted rgba(224, 82, 82, 0.5);
  pointer-events: none;
}
pre.editor-colors .gutter .line-number.folded,
.host .gutter .line-number.folded,
pre.editor-colors .gutter .line-number:after,
.host .gutter .line-number:after,
pre.editor-colors .fold-marker:after,
.host .fold-marker:after {
  color: #abb2bf;
}
.comment {
  color: #5c6370;
  font-style: italic;
}
.comment .markup.link {
  color: #5c6370;
}
.entity.name.type {
  color: #e5c07b;
}
.entity.other.inherited-class {
  color: #98c379;
}
.keyword {
  color: #c678dd;
}
.keyword.control {
  color: #c678dd;
}
.keyword.operator {
  color: #abb2bf;
}
.keyword.other.special-method {
  color: #61afef;
}
.keyword.other.unit {
  color: #d19a66;
}
.storage {
  color: #c678dd;
}
.storage.type.annotation,
.storage.type.primitive {
  color: #c678dd;
}
.storage.modifier.package,
.storage.modifier.import {
  color: #abb2bf;
}
.constant {
  color: #d19a66;
}
.constant.variable {
  color: #d19a66;
}
.constant.character.escape {
  color: #56b6c2;
}
.constant.numeric {
  color: #d19a66;
}
.constant.other.color {
  color: #56b6c2;
}
.constant.other.symbol {
  color: #56b6c2;
}
.variable {
  color: #e06c75;
}
.variable.interpolation {
  color: #be5046;
}
.variable.parameter {
  color: #abb2bf;
}
.string {
  color: #98c379;
}
.string.regexp {
  color: #56b6c2;
}
.string.regexp .source.ruby.embedded {
  color: #e5c07b;
}
.string.other.link {
  color: #e06c75;
}
.punctuation.definition.comment {
  color: #5c6370;
}
.punctuation.definition.method-parameters,
.punctuation.definition.function-parameters,
.punctuation.definition.parameters,
.punctuation.definition.separator,
.punctuation.definition.seperator,
.punctuation.definition.array {
  color: #abb2bf;
}
.punctuation.definition.heading,
.punctuation.definition.identity {
  color: #61afef;
}
.punctuation.definition.bold {
  color: #e5c07b;
  font-weight: bold;
}
.punctuation.definition.italic {
  color: #c678dd;
  font-style: italic;
}
.punctuation.section.embedded {
  color: #be5046;
}
.punctuation.section.method,
.punctuation.section.class,
.punctuation.section.inner-class {
  color: #abb2bf;
}
.support.class {
  color: #e5c07b;
}
.support.type {
  color: #56b6c2;
}
.support.function {
  color: #56b6c2;
}
.support.function.any-method {
  color: #61afef;
}
.entity.name.function {
  color: #61afef;
}
.entity.name.class,
.entity.name.type.class {
  color: #e5c07b;
}
.entity.name.section {
  color: #61afef;
}
.entity.name.tag {
  color: #e06c75;
}
.entity.other.attribute-name {
  color: #d19a66;
}
.entity.other.attribute-name.id {
  color: #61afef;
}
.meta.class {
  color: #e5c07b;
}
.meta.class.body {
  color: #abb2bf;
}
.meta.method-call,
.meta.method {
  color: #abb2bf;
}
.meta.definition.variable {
  color: #e06c75;
}
.meta.link {
  color: #d19a66;
}
.meta.require {
  color: #61afef;
}
.meta.selector {
  color: #c678dd;
}
.meta.separator {
  background-color: #373b41;
  color: #abb2bf;
}
.meta.tag {
  color: #abb2bf;
}
.underline {
  text-decoration: underline;
}
.none {
  color: #abb2bf;
}
.invalid.deprecated {
  color: #523d14 !important;
  background-color: #e0c285 !important;
}
.invalid.illegal {
  color: #ffffff !important;
  background-color: #e05252 !important;
}
.markup.bold {
  color: #d19a66;
  font-weight: bold;
}
.markup.changed {
  color: #c678dd;
}
.markup.deleted {
  color: #e06c75;
}
.markup.italic {
  color: #c678dd;
  font-style: italic;
}
.markup.heading {
  color: #e06c75;
}
.markup.heading .punctuation.definition.heading {
  color: #61afef;
}
.markup.link {
  color: #c678dd;
}
.markup.inserted {
  color: #98c379;
}
.markup.quote {
  color: #d19a66;
}
.markup.raw {
  color: #98c379;
}
.source.cs .keyword.operator {
  color: #c678dd;
}
.source.css .property-name,
.source.css .property-value {
  color: #828997;
}
.source.css .property-name.support,
.source.css .property-value.support {
  color: #abb2bf;
}
.source.gfm .markup {
  -webkit-font-smoothing: auto;
}
.source.gfm .link .entity {
  color: #61afef;
}
.source.ini .keyword.other.definition.ini {
  color: #e06c75;
}
.source.java .storage.modifier.import {
  color: #e5c07b;
}
.source.java .storage.type {
  color: #e5c07b;
}
.source.java-properties .meta.key-pair {
  color: #e06c75;
}
.source.java-properties .meta.key-pair > .punctuation {
  color: #abb2bf;
}
.source.js .keyword.operator {
  color: #56b6c2;
}
.source.js .keyword.operator.delete,
.source.js .keyword.operator.in,
.source.js .keyword.operator.of,
.source.js .keyword.operator.instanceof,
.source.js .keyword.operator.new,
.source.js .keyword.operator.typeof,
.source.js .keyword.operator.void {
  color: #c678dd;
}
.source.json .meta.structure.dictionary.json > .string.quoted.json {
  color: #e06c75;
}
.source.json .meta.structure.dictionary.json > .string.quoted.json > .punctuation.string {
  color: #e06c75;
}
.source.json .meta.structure.dictionary.json > .value.json > .string.quoted.json,
.source.json .meta.structure.array.json > .value.json > .string.quoted.json,
.source.json .meta.structure.dictionary.json > .value.json > .string.quoted.json > .punctuation,
.source.json .meta.structure.array.json > .value.json > .string.quoted.json > .punctuation {
  color: #98c379;
}
.source.json .meta.structure.dictionary.json > .constant.language.json,
.source.json .meta.structure.array.json > .constant.language.json {
  color: #56b6c2;
}
.source.ruby .constant.other.symbol > .punctuation {
  color: inherit;
}
.source.python .keyword.operator.logical.python {
  color: #c678dd;
}
.source.python .variable.parameter {
  color: #d19a66;
}
</style>
  </head>
  <body class='markdown-preview' data-use-github-style><h1 id="frc-team-1418">FRC Team 1418</h1>
<h3 id="student-parent-handbook-2016-2017">Student/Parent Handbook 2016-2017</h3>
<p>1418.team | twitter.com/Robotics1418 | facebook.com/robotics1418 | github.com/frc1418 &lt;-</p>
<p>====</p>
<h2 id="table-of-contents">TABLE OF CONTENTS</h2>
<h4 id="section-1-introduction-to-robotics">Section 1: Introduction to Robotics</h4>
<p>1.1: What is FIRST?</p>
<p>1.2: About Vae Victis</p>
<h4 id="section-2-team-structure-and-procedures">Section 2: Team Structure and Procedures</h4>
<p>2.1: Mentors</p>
<p>2.2: Team Captains and Sub-Team Captains</p>
<p>2.3: Selecting a Sub-Team</p>
<p>2.4: Robot Design Process</p>
<p>2.5: Other Decision Making</p>
<p>2.6: Expenditures</p>
<p>2.7: Competition Drive Team</p>
<p>2.8: Competition Pit Team</p>
<p>2.9: Fundraising and Financial Obligations</p>
<h4 id="section-3-member-and-team-expectations">Section 3: Member and Team Expectations</h4>
<p>3.1: Enjoy yourself!</p>
<p>3.2: Academic Standing</p>
<p>3.3: Group Participation</p>
<p>3.4: Attendance</p>
<p>3.5: Qualifying for Travel</p>
<p>3.6: Acceptable Behavior</p>
<p>3.7: Competitions / Events</p>
<p>3.8: Self-Motivation</p>
<p>3.9: Communication</p>
<p>3.10: What students gain by being a part of Vae Victis</p>
<p>3.11: Parental Involvement</p>
<h4 id="section-4-agreements">Section 4: Agreements</h4>
<p>4.1: Transporting your student home from a FRC 1923 event</p>
<p>4.2: Transportation with Adult Mentors</p>
<p>4.3: Publicity &amp; Public Representation</p>
<p>====</p>
<h3 id="section-1-introduction-to-robotics">Section 1: Introduction to Robotics</h3>
<p><strong>1.1 What is FIRST?</strong></p>
<p>FIRST was started in 1989 by renowned inventor Dean Kamen. The FIRST (For Inspiration and Recognition of Science and Technology) programs aim to create passion for science and technology in students. The FIRST program encourages Gracious Professionalism and Co-Opertition, sportsmanship amongst teams even in the face of competition. Through FIRST, students build technical skills, and foster teamwork and leadership skills.
[Additional Things to Mention]</p>
<ol>
<li>FIRST’s four divisions</li>
<li>(Briefly) Vae Victis’ involvement in helping other FRC/FTC/FLL/Jr.FLL teams</li>
<li>Process of how a robot is built in within FIRST’s requirements</li>
<li>(Briefly) Explain previous challenge</li>
<li>Mention the team’s website and/or social media</li>
<li>Direct to first website as well</li>
</ol>
<p><strong>1.2 About Vae Victis</strong>
[Things to Mention]</p>
<ol>
<li>History of Vae Victis (establishment, # of kids, etc)</li>
<li>How Vae Victis has grown</li>
<li>What Vae Victis does on a usual basis (mentoring/fll stuff/outreach/”days”/etc | refer to Chairman’s Essay for inspiration)</li>
<li>Awards and Achievements (w/ years)</li>
<li>Improving in the future?</li>
</ol>
<h3 id="section-2-team-structure-and-procedures">Section 2: Team Structure and Procedures</h3>
<p><strong>2.1 Mentors</strong></p>
<p>[Things to Mention]</p>
<ol>
<li>Explain mentors (what they do/who they are/their importance)</li>
<li><a href="http://www.usfirst.org/community/volunteers/get-involved">http://www.usfirst.org/community/volunteers/get-involved</a></li>
<li><a href="http://www.usfirst.org/uploadedFiles/Community/FRC/Team_Resources/Mentoring%20Gui">http://www.usfirst.org/uploadedFiles/Community/FRC/Team_Resources/Mentoring%20Gui</a> de.pdf</li>
<li>List of mentors (for FTC and FRC [possibly FLL too])</li>
</ol>
<p>FRC Mentors play a vital role in the success of their students. Mentors work extensively with team members during the build season, designing, building, and fabricating a functional robot for Competition. Their expertise is the catalyst for the team’s and students’ success. FRC Mentors are the major distinction between the FRC program and other robotic competitions as they act as a professional role model for the students.
Mentors engage and inspire students in ways far beyond science and technology. They enable both students and adults to appreciate the value of sportsmanship, teamwork, and Gracious Professionalism®.</p>
<p><strong>2.2 Team Captains and Sub-Team Leaders</strong></p>
<p>[Things to Mention]</p>
<ol>
<li>How the team is split up</li>
<li>Requirements of captains/leaders</li>
</ol>
<p><strong>2.3. Selecting a Sub-Team</strong></p>
<p>[Things to Mention]</p>
<ol>
<li>Explanation of a sub-team</li>
<li>[NOTE] I am aware that Vae Victis does not necessarily have designated &quot;sub-teams&quot; but it may be a good idea to put them in so we look a bit more official and organized than we actually are. (good for things such as Chairman&#39;s Award and presentations)</li>
</ol>
<p><strong>2.4 Robot Design Process</strong></p>
<p>[Things to Mention]</p>
<ol>
<li>Explain how the team starts with the planning of the robot</li>
<li>Explain how each member must understand the workings of the game (reading the rules must be emphasized)</li>
<li>Explain each meeting</li>
<li>Split up explanation (after general explanation) into weeks</li>
</ol>
<p><strong>2.5 Other Decision Making</strong></p>
<p>[Things to Mention]</p>
<ol>
<li>Explanation of relationships between people on the team</li>
<li>Respect must be emphasized</li>
<li>Mention responsibilities of advisors/mentors/students</li>
</ol>
<p><strong>2.6 Expenditures</strong></p>
<p>[Things to Mention]</p>
<ol>
<li>Explain how we handle costs</li>
<li>Reimbursement policies</li>
<li>Fundraising mention?</li>
</ol>
<p><strong>2.7 Competition Drive Team</strong></p>
<p>[Things to Mention]</p>
<ol>
<li>Drive team positions (with explanation)</li>
<li>Selection process</li>
<li>Responsibilities of drive team</li>
</ol>
<p><strong>2.8 Competition Pit Crew</strong></p>
<p>[Things to Mention]</p>
<ol>
<li>Selection process</li>
<li>Responsibilities of pit crew</li>
</ol>
<p><strong>2.9 Fundraising and Financial Obligations</strong></p>
<p>[Things to Mention]</p>
<ol>
<li>No fee for joining team (bc we&#39;re such a loving team and we accept people of all backgrounds/races/experience levels/sexes/age)</li>
<li>Fees that must be determined from the beginning of the year</li>
<li>St. Louis</li>
<li>Fundraising</li>
</ol>
<p></p>
<h3 id="section-3-member-and-team-expectations">Section 3: Member and Team Expectations</h3>
<p><strong>3.1 Enjoy yourself!</strong></p>
<p>“We do this for the serious fun of it” -John Ballou, Head Mentor of Vae Victis
We are a competitive team, but that doesn’t mean we don’t know how to have fun. As long as you are staying within the law, rules of the team, and follow Gracious Professionalism®, there is no problem! After all, we’re here to experience science &amp; technology teamwork in a positive and fun environment.</p>
<p>[Additional Things to Mention]</p>
<ol>
<li>Extending the horizons of students&#39; knowledge in engineering</li>
</ol>
<p><strong>3.2 Academic Standing</strong></p>
<p>Team 1418 regards academic performance and student behavior as extremely important factors in team success. Please refer to your student handbook regarding academic standing.</p>
<p>[Additional Things to Mention]</p>
<ol>
<li>Will we be creating a student handbook? If so, leave that last line in.</li>
<li>Academic performance = PRIORITY (&lt;- emphasize this)</li>
</ol>
<p><strong>3.3 Group Participation</strong></p>
<p>[Things to Mention]</p>
<ol>
<li>Goal to create an accepting atmosphere</li>
<li>Requirements of each team member</li>
<li>Importance of coopertition</li>
<li>Explanation of what is expected of a responsible team member</li>
<li>Importance of email</li>
</ol>
<p><strong>3.4 Attendance</strong></p>
<p>[Things to Mention]</p>
<ol>
<li>Attendance/sign in taken every day</li>
<li>Things that students are expected to go to</li>
<li>&quot;a student’s standing is determined by their participation when they are present&quot;</li>
<li>When season starts of this year</li>
<li>Importance of working before the build season as well as during the build season</li>
<li>Importance of communication between student(s) and advisor/mentor(s) with scheduling issues</li>
</ol>
<p><strong>3.5 Qualifying for Travel</strong></p>
<p>[Things to Mention]</p>
<ol>
<li>Required paperwork</li>
<li>Good standing</li>
<li>Difference in world competitions</li>
<li>Other requirements (academics, sports, etc)</li>
</ol>
<p><strong>3.6 Acceptable Behavior</strong></p>
<p>[Things to Mention]</p>
<ol>
<li>Importance of knowing that Vae Victis is representing George Mason and to an extent, Falls Church as a whole. Also representing our sponsors.</li>
<li>Right to be removed</li>
<li>Must be respectful to: other students, adults, the facility, the utensils, mentors, volunteers, and practice Gracious Professionanlism.</li>
<li>Emphasize importance of safety</li>
<li>Safety rules</li>
<li>Cell phone policy</li>
<li>SOCIAL MEDIA IS NOT AN EXCEPTION</li>
</ol>
<p><strong>3.7 Competitions / Events</strong></p>
<p>[Things to Mention]</p>
<ol>
<li>Dress code</li>
<li>Outfits/costumes</li>
<li>Team shirts</li>
<li>Expectations</li>
<li>Using technology</li>
<li>Clean up</li>
</ol>
<p><strong>3.8 Self-Motivation</strong></p>
<ol>
<li>You are your own best advocate</li>
<li>Stress the &quot;self-motivated&quot; part of the team</li>
</ol>
<p><strong>3.9 Communication</strong></p>
<ol>
<li>Importance of email</li>
<li>Social media</li>
<li>Website</li>
</ol>
<p><strong>3.10 What students gain by being a part of Vae Victis</strong></p>
<p>[Things to Mention]</p>
<ol>
<li>Skills</li>
<li>Time management</li>
<li>Opportunities</li>
<li>Scholarships</li>
</ol>
<p><strong>3.11 Parental Involvement</strong></p>
<p>[Things to Mention]</p>
<ol>
<li>Not a requirement, but makes it easier on participants</li>
<li>Necessity of parent volunteers (list of things PV&#39;s help w/)</li>
</ol>
<h3 id="section-4-agreements">Section 4: Agreements</h3>
<p><strong>4.1 Transporting your student home from a FRC 1418 event</strong></p>
<p>[Things to Mention]</p>
<ol>
<li>Rules regarding transportation</li>
</ol>
<p><strong>4.2 Transportation with Adult Mentors</strong></p>
<p>[Things to Mention]</p>
<ol>
<li>(TBD)</li>
</ol>
<p><strong>4.3 Publicity &amp; Public Representation</strong></p>
<p>[Things to Mention]</p>
<ol>
<li>Photographs/videos</li>
<li>Permissions associated with being on the team (Photos/videos/name and comments being publicized)</li>
</ol>
<p></p>
<h2 id="frc-team-1418-handbook-agreement-2016-2017">FRC Team 1418 Handbook Agreement 2016-2017</h2>
<p>[NOTE]
Is it necessary to have people sign the handbook?</p>
<p>Please sign &amp; return by September 30 (returning members) or October 15th (new members)
I, <strong><strong><strong><strong><strong><strong><strong><strong>___</strong></strong></strong></strong></strong></strong></strong></strong>, as a participant on FIRST Robotics Competition (FRC) Team 1418, Vae Victis, agree to abide by all the rules and consequences stated in the FRC 1418 Team Handbook. I certify that I have read the handbook and will abide by all the rules/regulations/releases therein.
Student Signature <strong><strong><strong><strong><strong><strong><strong><strong><strong>___</strong></strong></strong></strong></strong></strong></strong></strong></strong> Date <strong><strong>___</strong></strong> Student Name (Print) <strong><strong><strong><strong><strong><strong><strong><strong><strong><strong>_</strong></strong></strong></strong></strong></strong></strong></strong></strong></strong>
Student Email (Print)<strong><strong><strong><strong><strong><strong><strong><strong><strong><strong><strong><em>__</em></strong></strong></strong></strong></strong></strong></strong></strong></strong></strong></strong>
Cell Phone<strong><strong><strong><strong><strong><strong><strong><strong><strong><strong><strong><strong>_</strong></strong></strong></strong></strong></strong></strong></strong></strong></strong></strong></strong>
I, <strong><strong><strong><strong><strong><strong><strong>___</strong></strong></strong></strong></strong></strong></strong>, as a parent/guardian for a student on FRC 1418, Vae Victis, agree to abide by all the rules and consequences stated in the FRC 1418 Team Handbook. I certify that I have read the handbook and will abide by all the rules/regulations/releases therein.
Parent/Guardian Signature <strong><strong><strong><strong><strong><strong><strong><strong>_</strong></strong></strong></strong></strong></strong></strong></strong> Date <strong><strong>__</strong></strong> Parent/Guardian Name (Print) <strong><strong><strong><strong><strong><strong><strong><strong><strong><strong><strong>__</strong></strong></strong></strong></strong></strong></strong></strong></strong></strong></strong> Email<strong><strong><strong><strong><strong><strong><strong><strong><strong><strong><strong>_</strong></strong></strong></strong></strong></strong></strong></strong></strong></strong></strong>
Home Phone<strong><strong><strong><strong><strong><strong>___</strong></strong></strong></strong></strong></strong> Cell Phone:<strong><strong><strong><strong><strong>___</strong></strong></strong></strong></strong> Parent/Guardian Signature <strong><strong><strong><strong><strong><strong><strong>_</strong></strong></strong></strong></strong></strong></strong> Date <strong><strong>__</strong></strong> Parent/Guardian Name (Print) <strong><strong><strong><strong><strong><strong><strong><strong><strong><strong>__</strong></strong></strong></strong></strong></strong></strong></strong></strong></strong> Email<strong><strong><strong><strong><strong><strong><strong><strong>_</strong></strong></strong></strong></strong></strong></strong></strong>
Home Phone<strong><strong><strong><strong><strong><strong><strong>_</strong></strong></strong></strong></strong></strong></strong> Cell Phone: <strong><strong><strong><strong><em>__</em></strong></strong></strong></strong></p></body>
</html>
