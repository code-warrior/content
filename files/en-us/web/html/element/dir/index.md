---
title: '<dir>: The Directory element'
slug: Web/HTML/Element/dir
tags:
  - Directory
  - Element
  - HTML
  - HTML Lists
  - Deprecated
  - Reference
  - Web
  - dir
  - lists
browser-compat: html.elements.dir
---
<div>{{HTMLRef}}{{deprecated_header}}</div>

<p>The <strong><code>&lt;dir&gt;</code></strong> <a href="/en-US/docs/Web/HTML">HTML</a> element is used as a container for a directory of files and/or folders, potentially with styles and icons applied by the {{Glossary("user agent")}}. Do not use this obsolete element; instead, you should use the {{HTMLElement("ul")}} element for lists, including lists of files.</p>

<div class="warning"><p><strong>Warning:</strong> Do not use this element. Though present in early HTML specifications, it has been deprecated in HTML 4, and has since been removed entirely. <strong>No major browsers support this element.</strong></p></div>

<h2 id="DOM_interface">DOM interface</h2>

<p>This element implements the {{domxref("HTMLDirectoryElement")}} interface.</p>

<h2 id="Attributes">Attributes</h2>

<p>Like all other HTML elements, this element supports the <a href="/en-US/docs/Web/HTML/Global_attributes" title="HTML/Global attributes">global attributes</a>.</p>

<dl>
 <dt>{{htmlattrdef("compact")}}</dt>
 <dd>This Boolean attribute hints that the list should be rendered in a compact style. The interpretation of this attribute depends on the user agent and it doesn't work in all browsers.
 </dd>
</dl>

<h2 id="Specifications">Specifications</h2>

<p>Not part of any current specifications.</p>

<h2 id="Browser_compatibility">Browser compatibility</h2>

<p>{{Compat}}</p>

<h2 id="See_also">See also</h2>

<ul>
 <li>Other list-related HTML Elements: {{HTMLElement("ol")}}, {{HTMLElement("ul")}}, {{HTMLElement("li")}}, and {{HTMLElement("menu")}};</li>
 <li>CSS properties that may be specially useful to style the <code>&lt;dir&gt;</code> element:
  <ul>
   <li>The {{cssxref('list-style')}} property, useful to choose the way the ordinal is displayed.</li>
   <li><a href="/en-US/docs/Web/CSS/CSS_Lists_and_Counters/Using_CSS_counters">CSS counters</a>, useful to handle complex nested lists.</li>
   <li>The {{Cssxref('line-height')}} property, useful to simulate the deprecated {{htmlattrxref("compact", "dir")}} attribute.</li>
   <li>The {{cssxref('margin')}} property, useful to control the indent of the list.</li>
  </ul>
 </li>
</ul>