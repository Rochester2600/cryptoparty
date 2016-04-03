<!DOCTYPE html>
<html>
  <head>
      <meta charset="utf-8" />
      <title>space_diamonds</title>
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
  <body class='markdown-preview'><h1 id="openpgp-space-diamonds">OpenPGP Space Diamonds</h1>
<h2 id="description">Description</h2>
<p>Space Diamonds is a more hardened setup than the Rock Hard
where the goals are to create a Master key with various sub
keys. Your Master Key is used only for signing other
peoples&#39; keys (Confirmation) and the subkeys are for your
day to day operations. Your master key is stored in a high
security location while your subkeys can be placed in
higher risk locations like your office or car.</p>
<iframe src="https://docs.google.com/presentation/d/1M4q1UZvGTqcIbWZEQyT6JkHEnMHaDQ9UF7jJD8vUuL0/embed?start=false&amp;loop=true&amp;delayms=10000" frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

<h2 id="about-this-document">About this Document</h2>
<p><em>NEED</em> is used to refer to directions that require you to
following the directions otherwise compromising the plan.
<em>SHOULD</em> is used to refer to directions that are advised but
are not required.</p>
<h2 id="requirements">Requirements</h2>
<p>1 x Laptop to boot TAILS and will never go online
1 x Laptop that will be using your subkeys
1 x USB storage device to transfer the cards
1 x USB or DVD for TAILS
1 x USB persistent storage location for TAILS [OPTIONAL]
1 x Smart Card to store your subkeys
1 x Smart Card to store your master key [OPTIONAL]
1 x TRNG or external entropy source [OPTIONAL]</p>
<h2 id="overview">Overview</h2>
<ul>
<li>Setup air-gapped laptop</li>
<li>Generate Master Key</li>
</ul>
<h2 id="setup-air-gapped-laptop">Setup Air-Gapped Laptop</h2>
<p>You need to setup an air-gapped laptop so that your keys
are generated on secure hardware. You will need to copy the
files off of this system via encrypted USB.</p>
<ul>
<li>Download and setup a TAILS ISO to a DVD or USB[1]
(Install Media)</li>
<li>Boot the system and use it to install/clone TAILS onto a
dedicated drive. (TAILS Drive)</li>
<li>Boot the TAILS Drive.The drive needs to support &quot;Personal
Data&quot; and should include &quot;GnuPG&quot;, &quot;Apt Lists&quot;, and &quot;Apt
Packages&quot;</li>
<li>Reboot and choose &quot;Yes&quot; for advanced options to use the
persistent container and set a root password.
<em>NOTE: You have to install gpgv2 from debian. Either connect
to the Internet and install it in the directions below or
somehow install it from source.</em></li>
</ul>
<h3 id="option-1-gpg-install-via-apt-get">OPTION 1: GPG Install via Apt-Get</h3>
<ul>
<li>Configure the device to connect to the network</li>
<li>Open a terminal and run</li>
</ul>
<blockquote>
<p>sudo apt-get update</p>
</blockquote>
<pre class="editor-colors lang-text"><div class="line"><span class="text plain"><span class="meta paragraph text"><span>We&nbsp;trust&nbsp;you&nbsp;have&nbsp;received&nbsp;the&nbsp;usual&nbsp;lecture&nbsp;from&nbsp;the&nbsp;local&nbsp;System</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>Administrator.&nbsp;It&nbsp;usually&nbsp;boils&nbsp;down&nbsp;to&nbsp;these&nbsp;three&nbsp;things:</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;</span></span></div><div class="line"><span class="text plain"><span>&nbsp;&nbsp;&nbsp;&nbsp;</span><span class="meta paragraph text"><span>#1)&nbsp;Respect&nbsp;the&nbsp;privacy&nbsp;of&nbsp;others.</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;&nbsp;&nbsp;&nbsp;#2)&nbsp;Think&nbsp;before&nbsp;you&nbsp;type.</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;&nbsp;&nbsp;&nbsp;#3)&nbsp;With&nbsp;great&nbsp;power&nbsp;comes&nbsp;great&nbsp;responsibility.</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;</span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>[sudo]&nbsp;password&nbsp;for&nbsp;amnesia:</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>Reading&nbsp;package&nbsp;lists...&nbsp;Done</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>Building&nbsp;dependency&nbsp;tree&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>...</span></span></span></div></pre><ul>
<li>Install the latest available version of GnuPG (2.0.26-6 or 2.1.11-6)</li>
</ul>
<blockquote>
<p>sudo apt-get install gpgv2=2.1.11-6 --download-only</p>
</blockquote>
<h3 id="option-2-gpg-install-from-offline-copy">OPTION 2: GPG Install From Offline Copy</h3>
<ul>
<li>Good luck.</li>
</ul>
<h3 id="optional-trng">OPTIONAL: TRNG</h3>
<ul>
<li><p>Use Pee&#39;s HRNG device and install rand-tools</p>
<blockquote>
<p>sudo apt-get install rand-tools</p>
</blockquote>
<pre class="editor-colors lang-text"><div class="line"><span class="text plain"><span class="meta paragraph text"><span>Building&nbsp;dependency&nbsp;tree&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>Reading&nbsp;state&nbsp;information...&nbsp;Done</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>The&nbsp;following&nbsp;NEW&nbsp;packages&nbsp;will&nbsp;be&nbsp;installed:</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;&nbsp;</span><span class="meta paragraph text"><span>rng-tools</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>0&nbsp;upgraded,&nbsp;1&nbsp;newly&nbsp;installed,&nbsp;0&nbsp;to&nbsp;remove&nbsp;and&nbsp;5&nbsp;not&nbsp;upgraded.</span></span></span></div></pre></li>
<li>Drop to root and run<blockquote>
<p>rngd -r /dev/ttyACM0</p>
</blockquote>
</li>
</ul>
<p><em>Result</em>: Should have a fully functional air-gapped
laptop that can read your smart card reader.</p>
<h2 id="generate-master-key">Generate Master Key</h2>
<p>You need to generate a master key that will only be used to
sign other peoples&#39; keys and generate sub keys. This needs
to be generated on the laptop and can be imported to a
smartcard later.</p>
<p><em>NOTE: You should be running gpg v2.0.29 but your commands
may be gpgv2 or gpg. gpg is used below because it looks
less stupid.*</em></p>
<ul>
<li><p>Generate key using expert settings</p>
<blockquote>
<p>gpg --expert --gen-key</p>
</blockquote>
<pre class="editor-colors lang-text"><div class="line"><span class="text plain"><span class="meta paragraph text"><span>Please&nbsp;select&nbsp;what&nbsp;kind&nbsp;of&nbsp;key&nbsp;you&nbsp;want:</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;</span><span class="meta paragraph text"><span>(1)&nbsp;RSA&nbsp;and&nbsp;RSA&nbsp;(default)</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;(2)&nbsp;DSA&nbsp;and&nbsp;Elgamal</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;(3)&nbsp;DSA&nbsp;(sign&nbsp;only)</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;(4)&nbsp;RSA&nbsp;(sign&nbsp;only)</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;(7)&nbsp;DSA&nbsp;(set&nbsp;your&nbsp;own&nbsp;capabilities)</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;(8)&nbsp;RSA&nbsp;(set&nbsp;your&nbsp;own&nbsp;capabilities)</span></span></span></div></pre></li>
<li><p>Choose to set your own capabilities on an RSA certificate       </p>
<blockquote>
<p>Your selection? 8</p>
</blockquote>
<pre class="editor-colors lang-text"><div class="line"><span class="text plain"><span>&nbsp;</span><span class="meta paragraph text"><span>Possible&nbsp;actions&nbsp;for&nbsp;a&nbsp;RSA&nbsp;key:&nbsp;Sign&nbsp;Certify&nbsp;Encrypt&nbsp;Authenticate</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;Current&nbsp;allowed&nbsp;actions:&nbsp;Sign&nbsp;Certify&nbsp;Encrypt</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;</span></span></div><div class="line"><span class="text plain"><span>&nbsp;&nbsp;&nbsp;&nbsp;</span><span class="meta paragraph text"><span>(S)&nbsp;Toggle&nbsp;the&nbsp;sign&nbsp;capability</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;&nbsp;&nbsp;&nbsp;(E)&nbsp;Toggle&nbsp;the&nbsp;encrypt&nbsp;capability</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;&nbsp;&nbsp;&nbsp;(A)&nbsp;Toggle&nbsp;the&nbsp;authenticate&nbsp;capability</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;&nbsp;&nbsp;&nbsp;(Q)&nbsp;Finished</span></span></span></div></pre></li>
<li><p>Disable signing          </p>
<blockquote>
<p>Your selection? s</p>
</blockquote>
<pre class="editor-colors lang-text"><div class="line"><span class="text plain"><span class="meta paragraph text"><span>Possible&nbsp;actions&nbsp;for&nbsp;a&nbsp;RSA&nbsp;key:&nbsp;Sign&nbsp;Certify&nbsp;Encrypt&nbsp;Authenticate</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>Current&nbsp;allowed&nbsp;actions:&nbsp;Certify&nbsp;Encrypt</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;</span></span></div><div class="line"><span class="text plain"><span>&nbsp;&nbsp;&nbsp;</span><span class="meta paragraph text"><span>(S)&nbsp;Toggle&nbsp;the&nbsp;sign&nbsp;capability</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;&nbsp;&nbsp;(E)&nbsp;Toggle&nbsp;the&nbsp;encrypt&nbsp;capability</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;&nbsp;&nbsp;(A)&nbsp;Toggle&nbsp;the&nbsp;authenticate&nbsp;capability</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;&nbsp;&nbsp;(Q)&nbsp;Finished</span></span></span></div></pre></li>
<li><p>Disable encrypting</p>
<blockquote>
<p>Your selection? s</p>
</blockquote>
<pre class="editor-colors lang-text"><div class="line"><span class="text plain"><span class="meta paragraph text"><span>Possible&nbsp;actions&nbsp;for&nbsp;a&nbsp;RSA&nbsp;key:&nbsp;Sign&nbsp;Certify&nbsp;Encrypt&nbsp;Authenticate</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>Current&nbsp;allowed&nbsp;actions:&nbsp;Certify</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;</span></span></div><div class="line"><span class="text plain"><span>&nbsp;&nbsp;&nbsp;</span><span class="meta paragraph text"><span>(S)&nbsp;Toggle&nbsp;the&nbsp;sign&nbsp;capability</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;&nbsp;&nbsp;(E)&nbsp;Toggle&nbsp;the&nbsp;encrypt&nbsp;capability</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;&nbsp;&nbsp;(A)&nbsp;Toggle&nbsp;the&nbsp;authenticate&nbsp;capability</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;&nbsp;&nbsp;(Q)&nbsp;Finished</span></span></span></div></pre><blockquote>
<p>Your selection? q</p>
</blockquote>
</li>
<li><p>Choose 4096 bit keysize, valid for 1 year</p>
<pre class="editor-colors lang-text"><div class="line"><span class="text plain"><span class="meta paragraph text"><span>RSA&nbsp;keys&nbsp;may&nbsp;be&nbsp;between&nbsp;1024&nbsp;and&nbsp;4096&nbsp;bits&nbsp;long.</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>*What&nbsp;keysize&nbsp;do&nbsp;you&nbsp;want?&nbsp;(2048)&nbsp;4096*</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>Requested&nbsp;keysize&nbsp;is&nbsp;4096&nbsp;bits</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>Please&nbsp;specify&nbsp;how&nbsp;long&nbsp;the&nbsp;key&nbsp;should&nbsp;be&nbsp;valid.</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span class="meta paragraph text"><span>0&nbsp;=&nbsp;key&nbsp;does&nbsp;not&nbsp;expire</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span class="meta paragraph text"><span>&lt;n&gt;&nbsp;&nbsp;=&nbsp;key&nbsp;expires&nbsp;in&nbsp;n&nbsp;days</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt;n&gt;w&nbsp;=&nbsp;key&nbsp;expires&nbsp;in&nbsp;n&nbsp;weeks</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt;n&gt;m&nbsp;=&nbsp;key&nbsp;expires&nbsp;in&nbsp;n&nbsp;months</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt;n&gt;y&nbsp;=&nbsp;key&nbsp;expires&nbsp;in&nbsp;n&nbsp;years</span></span></span></div><div class="line"><span class="text plain"><span class="meta bullet-point star text"><span class="punctuation definition item text"><span>*</span></span><span>Key&nbsp;is&nbsp;valid&nbsp;for?&nbsp;(0)&nbsp;1y*</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>Key&nbsp;expires&nbsp;at&nbsp;Thu&nbsp;30&nbsp;Mar&nbsp;2017&nbsp;07:51:10&nbsp;PM&nbsp;UTC</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>*Is&nbsp;this&nbsp;correct?&nbsp;(y/N)&nbsp;y*</span></span></span></div></pre></li>
<li><p>Enter in your information and choose &quot;O&quot; to continue</p>
<pre class="editor-colors lang-text"><div class="line"><span class="text plain"><span class="meta paragraph text"><span>Real&nbsp;name:&nbsp;Ballsy&nbsp;Ballspants</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>Email&nbsp;address:&nbsp;ballsy@balls.com</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>Comment:</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>You&nbsp;selected&nbsp;this&nbsp;USER-ID:</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;&nbsp;&nbsp;&nbsp;</span><span class="meta paragraph text"><span>&quot;Ballsy&nbsp;Ballspants&nbsp;&lt;ballsy@balls.com&gt;&quot;</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;</span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>Change&nbsp;(N)ame,&nbsp;(C)omment,&nbsp;(E)mail&nbsp;or&nbsp;(O)kay/(Q)uit?&nbsp;o</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>You&nbsp;need&nbsp;a&nbsp;Passphrase&nbsp;to&nbsp;protect&nbsp;your&nbsp;secret&nbsp;key.</span></span></span></div></pre></li>
</ul>
<h2 id="generate-master-key-revocation-certificate">Generate Master Key Revocation Certificate</h2>
<p><em>NOTE: Make sure that when you are saving files, you&#39;re doing so
to the persistent container path or a secure lcoation.</em></p>
<ul>
<li>Generate the revoke certificate and save to a file<blockquote>
<p>gpg --gen-revoke YOURMASTERKEYID &gt; master_revocation.rev</p>
</blockquote>
</li>
<li>gpg --symmetric -a master_revocation.rev</li>
</ul>
<h2 id="generate-sub-keys">Generate Sub Keys</h2>
<ul>
<li><p>Edit the master key</p>
<blockquote>
<p>gpg --expert --edit-key MASTERKEYUID</p>
<pre class="editor-colors lang-text"><div class="line"><span class="text plain"><span class="meta paragraph text"><span>Secret&nbsp;key&nbsp;is&nbsp;available.</span></span></span></div></pre></blockquote>
<pre class="editor-colors lang-text"><div class="line"><span class="text plain"><span class="meta paragraph text"><span>pub&nbsp;&nbsp;4096R/0x30BCB69847041D67&nbsp;&nbsp;created:&nbsp;2016-03-30&nbsp;&nbsp;expires:&nbsp;2017-03-30&nbsp;&nbsp;usage:&nbsp;C&nbsp;&nbsp;&nbsp;</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span class="meta paragraph text"><span>trust:&nbsp;ultimate&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;validity:&nbsp;ultimate</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>[ultimate]&nbsp;(1).&nbsp;Ballsy&nbsp;Ballspants&nbsp;&lt;ballsy@balls.com&gt;</span></span></span></div></pre></li>
<li><p>Add a new key key</p>
<blockquote>
<p>gpg&gt; addkey</p>
<pre class="editor-colors lang-text"><div class="line"><span class="text plain"><span class="meta paragraph text"><span>Key&nbsp;is&nbsp;protected.</span></span></span></div></pre></blockquote>
<pre class="editor-colors lang-text"><div class="line"><span class="text plain"><span class="meta paragraph text"><span>You&nbsp;need&nbsp;a&nbsp;passphrase&nbsp;to&nbsp;unlock&nbsp;the&nbsp;secret&nbsp;key&nbsp;for</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>user:&nbsp;&quot;Ballsy&nbsp;Ballspants&nbsp;&lt;ballsy@balls.com&gt;&quot;</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>4096-bit&nbsp;RSA&nbsp;key,&nbsp;ID&nbsp;0x30BCB69847041D67,&nbsp;created&nbsp;2016-03-30</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;</span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>Please&nbsp;select&nbsp;what&nbsp;kind&nbsp;of&nbsp;key&nbsp;you&nbsp;want:</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;&nbsp;&nbsp;</span><span class="meta paragraph text"><span>(3)&nbsp;DSA&nbsp;(sign&nbsp;only)</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;&nbsp;&nbsp;(4)&nbsp;RSA&nbsp;(sign&nbsp;only)</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;&nbsp;&nbsp;(5)&nbsp;Elgamal&nbsp;(encrypt&nbsp;only)</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;&nbsp;&nbsp;(6)&nbsp;RSA&nbsp;(encrypt&nbsp;only)</span></span></span></div></pre></li>
<li><p>Choose 4096 encryption or signing only</p>
<blockquote>
<p>Your selection? 6</p>
<pre class="editor-colors lang-text"><div class="line"><span class="text plain"><span>&nbsp;&nbsp;&nbsp;</span><span class="meta paragraph text"><span>RSA&nbsp;keys&nbsp;may&nbsp;be&nbsp;between&nbsp;1024&nbsp;and&nbsp;4096&nbsp;bits&nbsp;long.</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;&nbsp;&nbsp;What&nbsp;keysize&nbsp;do&nbsp;you&nbsp;want?&nbsp;(2048)&nbsp;4096</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;&nbsp;&nbsp;Requested&nbsp;keysize&nbsp;is&nbsp;4096&nbsp;bits</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;&nbsp;&nbsp;Please&nbsp;specify&nbsp;how&nbsp;long&nbsp;the&nbsp;key&nbsp;should&nbsp;be&nbsp;valid.</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span class="meta paragraph text"><span>0&nbsp;=&nbsp;key&nbsp;does&nbsp;not&nbsp;expire</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span class="meta paragraph text"><span>&lt;n&gt;&nbsp;&nbsp;=&nbsp;key&nbsp;expires&nbsp;in&nbsp;n&nbsp;days</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt;n&gt;w&nbsp;=&nbsp;key&nbsp;expires&nbsp;in&nbsp;n&nbsp;weeks</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt;n&gt;m&nbsp;=&nbsp;key&nbsp;expires&nbsp;in&nbsp;n&nbsp;months</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt;n&gt;y&nbsp;=&nbsp;key&nbsp;expires&nbsp;in&nbsp;n&nbsp;years</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;&nbsp;&nbsp;</span><span class="meta paragraph text"><span>Key&nbsp;is&nbsp;valid&nbsp;for?&nbsp;(0)&nbsp;1y</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;&nbsp;&nbsp;Key&nbsp;expires&nbsp;at&nbsp;Thu&nbsp;30&nbsp;Mar&nbsp;2017&nbsp;07:56:12&nbsp;PM&nbsp;UTC</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;&nbsp;&nbsp;Is&nbsp;this&nbsp;correct?&nbsp;(y/N)&nbsp;y</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;&nbsp;&nbsp;Really&nbsp;create?&nbsp;(y/N)&nbsp;y</span></span></span></div></pre></blockquote>
</li>
<li><p>Repeat this step so that you create both an encryption, signing,
and optionally, an authentication key</p>
</li>
<li><p>When you&#39;ve created all subkeys. Backup all keys.</p>
<blockquote>
<p>gpg --export-secret-keys</p>
</blockquote>
<pre class="editor-colors lang-text"><div class="line"><span class="text plain"><span class="meta paragraph text"><span>user@debian:~$&nbsp;gpg&nbsp;--list-secret-keys</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>/media/FA21-BEC7/gnupghome/secring.gpg</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>--------------------------------------</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>sec&nbsp;&nbsp;&nbsp;3744R/1C5C4717&nbsp;2014-06-18&nbsp;[expires:&nbsp;2014-09-26]</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>uid&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Simon&nbsp;Josefsson</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>uid&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[jpeg&nbsp;image&nbsp;of&nbsp;size&nbsp;6048]</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>uid&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Simon&nbsp;Josefsson</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>ssb&gt;&nbsp;&nbsp;2048R/72D5245B&nbsp;2014-06-18</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>ssb&gt;&nbsp;&nbsp;2048R/A11F46D2&nbsp;2014-06-18</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>ssb&gt;&nbsp;&nbsp;2048R/D6987A02&nbsp;2014-06-18</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;</span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>user@debian:~$&nbsp;gpg&nbsp;-a&nbsp;--export-secret-keys&nbsp;1C5C4717&nbsp;&gt;&nbsp;$GNUPGHOME/../masterstubs.txt</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>user@debian:~$&nbsp;gpg&nbsp;-a&nbsp;--export-secret-subkeys&nbsp;1C5C4717&nbsp;&gt;&nbsp;$GNUPGHOME/../subkeysstubs.txt</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>user@debian:~$&nbsp;gpg&nbsp;-a&nbsp;--export&nbsp;1C5C4717&nbsp;&gt;&nbsp;$GNUPGHOME/../publickey.txt</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>user@debian:~$&nbsp;cp&nbsp;-a&nbsp;$GNUPGHOME&nbsp;$GNUPGHOME-backup-masterstubs</span></span></span></div></pre></li>
<li><p>Encrypt the backup so you can restore</p>
<blockquote>
<p>gpg --symmetric -a [eachfilename].txt; or something
s</p>
</blockquote>
</li>
</ul>
<h2 id="move-subkeys-to-smartcard">Move subkeys to smartcard</h2>
<p>You&#39;ll be moving <em>only</em> your subkeys to the smart card.</p>
<ul>
<li><p>Move subkeys to card</p>
<blockquote>
<p>gpg --edit-key KEYID</p>
</blockquote>
<pre class="editor-colors lang-text"><div class="line"><span class="text plain"><span class="meta paragraph text"><span>user@debian:~$&nbsp;gpg&nbsp;--edit-key&nbsp;1C5C4717</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>gpg&nbsp;(GnuPG)&nbsp;1.4.12;&nbsp;Copyright&nbsp;(C)&nbsp;2012&nbsp;Free&nbsp;Software&nbsp;Foundation,&nbsp;Inc.</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>This&nbsp;is&nbsp;free&nbsp;software:&nbsp;you&nbsp;are&nbsp;free&nbsp;to&nbsp;change&nbsp;and&nbsp;redistribute&nbsp;it.</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>There&nbsp;is&nbsp;NO&nbsp;WARRANTY,&nbsp;to&nbsp;the&nbsp;extent&nbsp;permitted&nbsp;by&nbsp;law.</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;</span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>Secret&nbsp;key&nbsp;is&nbsp;available.</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;</span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>pub&nbsp;&nbsp;3744R/1C5C4717&nbsp;&nbsp;created:&nbsp;2014-06-18&nbsp;&nbsp;expires:&nbsp;2014-09-26&nbsp;&nbsp;usage:&nbsp;SC&nbsp;&nbsp;</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span class="meta paragraph text"><span>trust:&nbsp;ultimate&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;validity:&nbsp;ultimate</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>sub&nbsp;&nbsp;2048R/72D5245B&nbsp;&nbsp;created:&nbsp;2014-06-18&nbsp;&nbsp;expires:&nbsp;2014-09-26&nbsp;&nbsp;usage:&nbsp;S&nbsp;&nbsp;&nbsp;</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>sub&nbsp;&nbsp;2048R/A11F46D2&nbsp;&nbsp;created:&nbsp;2014-06-18&nbsp;&nbsp;expires:&nbsp;2014-09-26&nbsp;&nbsp;usage:&nbsp;E&nbsp;&nbsp;&nbsp;</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>sub&nbsp;&nbsp;2048R/D6987A02&nbsp;&nbsp;created:&nbsp;2014-06-18&nbsp;&nbsp;expires:&nbsp;2014-09-26&nbsp;&nbsp;usage:&nbsp;A&nbsp;&nbsp;&nbsp;</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>[ultimate]&nbsp;(1).&nbsp;Simon&nbsp;Josefsson</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>[ultimate]&nbsp;(2)&nbsp;&nbsp;[jpeg&nbsp;image&nbsp;of&nbsp;size&nbsp;6048]</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>[ultimate]&nbsp;(3)&nbsp;&nbsp;Simon&nbsp;Josefsson</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;</span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>gpg&gt;&nbsp;toggle</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;</span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>sec&nbsp;&nbsp;3744R/1C5C4717&nbsp;&nbsp;created:&nbsp;2014-06-18&nbsp;&nbsp;expires:&nbsp;2014-09-26</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>ssb&nbsp;&nbsp;2048R/72D5245B&nbsp;&nbsp;created:&nbsp;2014-06-18&nbsp;&nbsp;expires:&nbsp;never&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>ssb&nbsp;&nbsp;2048R/A11F46D2&nbsp;&nbsp;created:&nbsp;2014-06-18&nbsp;&nbsp;expires:&nbsp;never&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>ssb&nbsp;&nbsp;2048R/D6987A02&nbsp;&nbsp;created:&nbsp;2014-06-18&nbsp;&nbsp;expires:&nbsp;never&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>(1)&nbsp;&nbsp;Simon&nbsp;Josefsson</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>(2)&nbsp;&nbsp;[jpeg&nbsp;image&nbsp;of&nbsp;size&nbsp;6048]</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>(3)&nbsp;&nbsp;Simon&nbsp;Josefsson</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;</span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>gpg&gt;&nbsp;key&nbsp;1</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;</span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>sec&nbsp;&nbsp;3744R/1C5C4717&nbsp;&nbsp;created:&nbsp;2014-06-18&nbsp;&nbsp;expires:&nbsp;2014-09-26</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>ssb*&nbsp;2048R/72D5245B&nbsp;&nbsp;created:&nbsp;2014-06-18&nbsp;&nbsp;expires:&nbsp;never&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>ssb&nbsp;&nbsp;2048R/A11F46D2&nbsp;&nbsp;created:&nbsp;2014-06-18&nbsp;&nbsp;expires:&nbsp;never&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>ssb&nbsp;&nbsp;2048R/D6987A02&nbsp;&nbsp;created:&nbsp;2014-06-18&nbsp;&nbsp;expires:&nbsp;never&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>(1)&nbsp;&nbsp;Simon&nbsp;Josefsson</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>(2)&nbsp;&nbsp;[jpeg&nbsp;image&nbsp;of&nbsp;size&nbsp;6048]</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>(3)&nbsp;&nbsp;Simon&nbsp;Josefsson</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;</span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>gpg&gt;&nbsp;keytocard</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>Signature&nbsp;key&nbsp;....:&nbsp;[none]</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>Encryption&nbsp;key....:&nbsp;[none]</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>Authentication&nbsp;key:&nbsp;[none]</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;</span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>Please&nbsp;select&nbsp;where&nbsp;to&nbsp;store&nbsp;the&nbsp;key:</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;&nbsp;&nbsp;</span><span class="meta paragraph text"><span>(1)&nbsp;Signature&nbsp;key</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;&nbsp;&nbsp;(3)&nbsp;Authentication&nbsp;key</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>Your&nbsp;selection?&nbsp;1</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;</span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>You&nbsp;need&nbsp;a&nbsp;passphrase&nbsp;to&nbsp;unlock&nbsp;the&nbsp;secret&nbsp;key&nbsp;for</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>user:&nbsp;&quot;Simon&nbsp;Josefsson&nbsp;&quot;</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>2048-bit&nbsp;RSA&nbsp;key,&nbsp;ID&nbsp;72D5245B,&nbsp;created&nbsp;2014-06-18</span></span></span></div></pre></li>
</ul>
<pre class="editor-colors lang-text"><div class="line"><span class="text plain"><span>&nbsp;&nbsp;</span><span class="meta paragraph text"><span>sec&nbsp;&nbsp;3744R/1C5C4717&nbsp;&nbsp;created:&nbsp;2014-06-18&nbsp;&nbsp;expires:&nbsp;2014-09-26</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;&nbsp;ssb*&nbsp;2048R/72D5245B&nbsp;&nbsp;created:&nbsp;2014-06-18&nbsp;&nbsp;expires:&nbsp;never&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span class="meta paragraph text"><span>card-no:&nbsp;0060&nbsp;00000042</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;&nbsp;</span><span class="meta paragraph text"><span>ssb&nbsp;&nbsp;2048R/A11F46D2&nbsp;&nbsp;created:&nbsp;2014-06-18&nbsp;&nbsp;expires:&nbsp;never&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;&nbsp;ssb&nbsp;&nbsp;2048R/D6987A02&nbsp;&nbsp;created:&nbsp;2014-06-18&nbsp;&nbsp;expires:&nbsp;never&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;&nbsp;(1)&nbsp;&nbsp;Simon&nbsp;Josefsson</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;&nbsp;(2)&nbsp;&nbsp;[jpeg&nbsp;image&nbsp;of&nbsp;size&nbsp;6048]</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;&nbsp;(3)&nbsp;&nbsp;Simon&nbsp;Josefsson</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;</span></span></div><div class="line"><span class="text plain"><span>&nbsp;&nbsp;</span><span class="meta paragraph text"><span>gpg&gt;&nbsp;key&nbsp;1</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;</span></span></div><div class="line"><span class="text plain"><span>&nbsp;&nbsp;</span><span class="meta paragraph text"><span>sec&nbsp;&nbsp;3744R/1C5C4717&nbsp;&nbsp;created:&nbsp;2014-06-18&nbsp;&nbsp;expires:&nbsp;2014-09-26</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;&nbsp;ssb&nbsp;&nbsp;2048R/72D5245B&nbsp;&nbsp;created:&nbsp;2014-06-18&nbsp;&nbsp;expires:&nbsp;never&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span class="meta paragraph text"><span>card-no:&nbsp;0060&nbsp;00000042</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;&nbsp;</span><span class="meta paragraph text"><span>ssb&nbsp;&nbsp;2048R/A11F46D2&nbsp;&nbsp;created:&nbsp;2014-06-18&nbsp;&nbsp;expires:&nbsp;never&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;&nbsp;ssb&nbsp;&nbsp;2048R/D6987A02&nbsp;&nbsp;created:&nbsp;2014-06-18&nbsp;&nbsp;expires:&nbsp;never&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;&nbsp;(1)&nbsp;&nbsp;Simon&nbsp;Josefsson</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;&nbsp;(2)&nbsp;&nbsp;[jpeg&nbsp;image&nbsp;of&nbsp;size&nbsp;6048]</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;&nbsp;(3)&nbsp;&nbsp;Simon&nbsp;Josefsson</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;</span></span></div><div class="line"><span class="text plain"><span>&nbsp;&nbsp;</span><span class="meta paragraph text"><span>gpg&gt;&nbsp;key&nbsp;2</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;</span></span></div><div class="line"><span class="text plain"><span>&nbsp;&nbsp;</span><span class="meta paragraph text"><span>sec&nbsp;&nbsp;3744R/1C5C4717&nbsp;&nbsp;created:&nbsp;2014-06-18&nbsp;&nbsp;expires:&nbsp;2014-09-26</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;&nbsp;ssb&nbsp;&nbsp;2048R/72D5245B&nbsp;&nbsp;created:&nbsp;2014-06-18&nbsp;&nbsp;expires:&nbsp;never&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span class="meta paragraph text"><span>card-no:&nbsp;0060&nbsp;00000042</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;&nbsp;</span><span class="meta paragraph text"><span>ssb*&nbsp;2048R/A11F46D2&nbsp;&nbsp;created:&nbsp;2014-06-18&nbsp;&nbsp;expires:&nbsp;never&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;&nbsp;ssb&nbsp;&nbsp;2048R/D6987A02&nbsp;&nbsp;created:&nbsp;2014-06-18&nbsp;&nbsp;expires:&nbsp;never&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;&nbsp;(1)&nbsp;&nbsp;Simon&nbsp;Josefsson</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;&nbsp;(2)&nbsp;&nbsp;[jpeg&nbsp;image&nbsp;of&nbsp;size&nbsp;6048]</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;&nbsp;(3)&nbsp;&nbsp;Simon&nbsp;Josefsson</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;</span></span></div><div class="line"><span class="text plain"><span>&nbsp;&nbsp;</span><span class="meta paragraph text"><span>gpg&gt;&nbsp;keytocard</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;&nbsp;Signature&nbsp;key&nbsp;....:&nbsp;EF34&nbsp;D1F7&nbsp;95C0&nbsp;3392&nbsp;E52A&nbsp;&nbsp;54FE&nbsp;DFF1&nbsp;6372&nbsp;72D5&nbsp;245B</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;&nbsp;Encryption&nbsp;key....:&nbsp;[none]</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;&nbsp;Authentication&nbsp;key:&nbsp;[none]</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;</span></span></div><div class="line"><span class="text plain"><span>&nbsp;&nbsp;</span><span class="meta paragraph text"><span>Please&nbsp;select&nbsp;where&nbsp;to&nbsp;store&nbsp;the&nbsp;key:</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span class="meta paragraph text"><span>(2)&nbsp;Encryption&nbsp;key</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;&nbsp;</span><span class="meta paragraph text"><span>Your&nbsp;selection?&nbsp;2</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;</span></span></div><div class="line"><span class="text plain"><span>&nbsp;&nbsp;</span><span class="meta paragraph text"><span>You&nbsp;need&nbsp;a&nbsp;passphrase&nbsp;to&nbsp;unlock&nbsp;the&nbsp;secret&nbsp;key&nbsp;for</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;&nbsp;user:&nbsp;&quot;Simon&nbsp;Josefsson&nbsp;&quot;</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;&nbsp;2048-bit&nbsp;RSA&nbsp;key,&nbsp;ID&nbsp;A11F46D2,&nbsp;created&nbsp;2014-06-18</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;</span></span></div><div class="line"><span class="text plain"><span>&nbsp;</span></span></div><div class="line"><span class="text plain"><span>&nbsp;&nbsp;</span><span class="meta paragraph text"><span>sec&nbsp;&nbsp;3744R/1C5C4717&nbsp;&nbsp;created:&nbsp;2014-06-18&nbsp;&nbsp;expires:&nbsp;2014-09-26</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;&nbsp;ssb&nbsp;&nbsp;2048R/72D5245B&nbsp;&nbsp;created:&nbsp;2014-06-18&nbsp;&nbsp;expires:&nbsp;never&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span class="meta paragraph text"><span>card-no:&nbsp;0060&nbsp;00000042</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;&nbsp;</span><span class="meta paragraph text"><span>ssb*&nbsp;2048R/A11F46D2&nbsp;&nbsp;created:&nbsp;2014-06-18&nbsp;&nbsp;expires:&nbsp;never&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span class="meta paragraph text"><span>card-no:&nbsp;0060&nbsp;00000042</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;&nbsp;</span><span class="meta paragraph text"><span>ssb&nbsp;&nbsp;2048R/D6987A02&nbsp;&nbsp;created:&nbsp;2014-06-18&nbsp;&nbsp;expires:&nbsp;never&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;&nbsp;(1)&nbsp;&nbsp;Simon&nbsp;Josefsson</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;&nbsp;(2)&nbsp;&nbsp;[jpeg&nbsp;image&nbsp;of&nbsp;size&nbsp;6048]</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;&nbsp;(3)&nbsp;&nbsp;Simon&nbsp;Josefsson</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;</span></span></div><div class="line"><span class="text plain"><span>&nbsp;&nbsp;</span><span class="meta paragraph text"><span>gpg&gt;&nbsp;key&nbsp;2</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;</span></span></div><div class="line"><span class="text plain"><span>&nbsp;&nbsp;</span><span class="meta paragraph text"><span>sec&nbsp;&nbsp;3744R/1C5C4717&nbsp;&nbsp;created:&nbsp;2014-06-18&nbsp;&nbsp;expires:&nbsp;2014-09-26</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;&nbsp;ssb&nbsp;&nbsp;2048R/72D5245B&nbsp;&nbsp;created:&nbsp;2014-06-18&nbsp;&nbsp;expires:&nbsp;never&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span class="meta paragraph text"><span>card-no:&nbsp;0060&nbsp;00000042</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;&nbsp;</span><span class="meta paragraph text"><span>ssb&nbsp;&nbsp;2048R/A11F46D2&nbsp;&nbsp;created:&nbsp;2014-06-18&nbsp;&nbsp;expires:&nbsp;never&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span class="meta paragraph text"><span>card-no:&nbsp;0060&nbsp;00000042</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;&nbsp;</span><span class="meta paragraph text"><span>ssb&nbsp;&nbsp;2048R/D6987A02&nbsp;&nbsp;created:&nbsp;2014-06-18&nbsp;&nbsp;expires:&nbsp;never&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;&nbsp;(1)&nbsp;&nbsp;Simon&nbsp;Josefsson</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;&nbsp;(2)&nbsp;&nbsp;[jpeg&nbsp;image&nbsp;of&nbsp;size&nbsp;6048]</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;&nbsp;(3)&nbsp;&nbsp;Simon&nbsp;Josefsson</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;</span></span></div><div class="line"><span class="text plain"><span>&nbsp;&nbsp;</span><span class="meta paragraph text"><span>gpg&gt;&nbsp;key&nbsp;3</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;</span></span></div><div class="line"><span class="text plain"><span>&nbsp;&nbsp;</span><span class="meta paragraph text"><span>sec&nbsp;&nbsp;3744R/1C5C4717&nbsp;&nbsp;created:&nbsp;2014-06-18&nbsp;&nbsp;expires:&nbsp;2014-09-26</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;&nbsp;ssb&nbsp;&nbsp;2048R/72D5245B&nbsp;&nbsp;created:&nbsp;2014-06-18&nbsp;&nbsp;expires:&nbsp;never&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span class="meta paragraph text"><span>card-no:&nbsp;0060&nbsp;00000042</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;&nbsp;</span><span class="meta paragraph text"><span>ssb&nbsp;&nbsp;2048R/A11F46D2&nbsp;&nbsp;created:&nbsp;2014-06-18&nbsp;&nbsp;expires:&nbsp;never&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span class="meta paragraph text"><span>card-no:&nbsp;0060&nbsp;00000042</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;&nbsp;</span><span class="meta paragraph text"><span>ssb*&nbsp;2048R/D6987A02&nbsp;&nbsp;created:&nbsp;2014-06-18&nbsp;&nbsp;expires:&nbsp;never&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;&nbsp;(1)&nbsp;&nbsp;Simon&nbsp;Josefsson</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;&nbsp;(2)&nbsp;&nbsp;[jpeg&nbsp;image&nbsp;of&nbsp;size&nbsp;6048]</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;&nbsp;(3)&nbsp;&nbsp;Simon&nbsp;Josefsson</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;</span></span></div><div class="line"><span class="text plain"><span>&nbsp;&nbsp;</span><span class="meta paragraph text"><span>gpg&gt;&nbsp;keytocard</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;&nbsp;Signature&nbsp;key&nbsp;....:&nbsp;EF34&nbsp;D1F7&nbsp;95C0&nbsp;3392&nbsp;E52A&nbsp;&nbsp;54FE&nbsp;DFF1&nbsp;6372&nbsp;72D5&nbsp;245B</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;&nbsp;Encryption&nbsp;key....:&nbsp;E24D&nbsp;5135&nbsp;C2FC&nbsp;905C&nbsp;8995&nbsp;&nbsp;ACD8&nbsp;EC96&nbsp;9E77&nbsp;A11F&nbsp;46D2</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;&nbsp;Authentication&nbsp;key:&nbsp;[none]</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;</span></span></div><div class="line"><span class="text plain"><span>&nbsp;&nbsp;</span><span class="meta paragraph text"><span>Please&nbsp;select&nbsp;where&nbsp;to&nbsp;store&nbsp;the&nbsp;key:</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span class="meta paragraph text"><span>(3)&nbsp;Authentication&nbsp;key</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;&nbsp;</span><span class="meta paragraph text"><span>Your&nbsp;selection?&nbsp;3</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;</span></span></div><div class="line"><span class="text plain"><span>&nbsp;&nbsp;</span><span class="meta paragraph text"><span>You&nbsp;need&nbsp;a&nbsp;passphrase&nbsp;to&nbsp;unlock&nbsp;the&nbsp;secret&nbsp;key&nbsp;for</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;&nbsp;user:&nbsp;&quot;Simon&nbsp;Josefsson&nbsp;&quot;</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;&nbsp;2048-bit&nbsp;RSA&nbsp;key,&nbsp;ID&nbsp;D6987A02,&nbsp;created&nbsp;2014-06-18</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;</span></span></div><div class="line"><span class="text plain"><span>&nbsp;</span></span></div><div class="line"><span class="text plain"><span>&nbsp;&nbsp;</span><span class="meta paragraph text"><span>sec&nbsp;&nbsp;3744R/1C5C4717&nbsp;&nbsp;created:&nbsp;2014-06-18&nbsp;&nbsp;expires:&nbsp;2014-09-26</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;&nbsp;ssb&nbsp;&nbsp;2048R/72D5245B&nbsp;&nbsp;created:&nbsp;2014-06-18&nbsp;&nbsp;expires:&nbsp;never&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span class="meta paragraph text"><span>card-no:&nbsp;0060&nbsp;00000042</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;&nbsp;</span><span class="meta paragraph text"><span>ssb&nbsp;&nbsp;2048R/A11F46D2&nbsp;&nbsp;created:&nbsp;2014-06-18&nbsp;&nbsp;expires:&nbsp;never&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span class="meta paragraph text"><span>card-no:&nbsp;0060&nbsp;00000042</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;&nbsp;</span><span class="meta paragraph text"><span>ssb*&nbsp;2048R/D6987A02&nbsp;&nbsp;created:&nbsp;2014-06-18&nbsp;&nbsp;expires:&nbsp;never&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span class="meta paragraph text"><span>card-no:&nbsp;0060&nbsp;00000042</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;&nbsp;</span><span class="meta paragraph text"><span>(1)&nbsp;&nbsp;Simon&nbsp;Josefsson</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;&nbsp;(2)&nbsp;&nbsp;[jpeg&nbsp;image&nbsp;of&nbsp;size&nbsp;6048]</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;&nbsp;(3)&nbsp;&nbsp;Simon&nbsp;Josefsson</span></span></span></div><div class="line"><span class="text plain"><span>&nbsp;</span></span></div><div class="line"><span class="text plain"><span>&nbsp;&nbsp;</span><span class="meta paragraph text"><span>gpg&gt;&nbsp;save</span></span></span></div><div class="line"><span class="text plain"><span class="meta paragraph text"><span>&nbsp;&nbsp;user@debian:~$</span></span></span></div></pre><h2 id="backup-master-key">Backup Master Key</h2>
<p>Backup the keys to a USB drive.</p>
<p> [1] <a href="https://tails.boum.org/">https://tails.boum.org/</a></p></body>
</html>
