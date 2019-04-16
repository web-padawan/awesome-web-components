# Web Components the Right Way

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of awesome Web Components resources.

[Web Components](https://developer.mozilla.org/en-US/docs/Web/Web_Components) — a suite of different technologies allowing you to create reusable custom elements — with their functionality encapsulated away from the rest of your code — and utilize them in your web apps.

## Contents

- [Specifications](#specifications)
- [Introduction](#introduction)
- [Custom Elements](#custom-elements)
- [Shadow DOM](#shadow-dom)
- [HTML Templates](#html-templates)
- [Polyfills](#polyfills)
- [Best Practices](#best-practices)
- [Use Cases](#use-cases)
- [Accessibility](#accessibility)
- [Discover](#discover)
- [Libraries](#libraries)
  - [Class Based](#class-based)
  - [Functional](#functional)
  - [Other](#other)
- [Component Libraries](#component-libraries)
- [Frameworks](#frameworks)
  - [Overview](#overview)
  - [Angular](#angular)
  - [Vue](#vue)
- [Compilers](#compilers)
- [Books](#books)
- [Tutorials](#tutorials)
- [Blogs](#blogs)
- [History](#history)
- [Future](#future)
  - [CSS Shadow Parts](#css-shadow-parts)
  - [Form-associated Custom Elements](#form-associated-custom-elements)
  - [Constructable Stylesheet Objects](#constructable-stylesheet-objects)
- [Who to follow](#who-to-follow)
- [License](#license)

> Web Components the Right Way was made with love by [Mateus Ortiz](https://twitter.com/mteusortiz) and maintained by [Serhii Kulykov](https://twitter.com/serhiikulykov)

## Specifications

- **Custom Elements** provide a way for authors to build their own fully-featured DOM elements.
  - [HTML Living Standard](https://html.spec.whatwg.org/multipage/custom-elements.html)
  - [DOM Living Standard](https://dom.spec.whatwg.org/#concept-element)
  - [W3C HTML 5.3 Working Draft](https://www.w3.org/TR/html53/semantics-scripting.html#custom-elements-core-concepts)
  - [W3C DOM 4.1 Working Draft](https://www.w3.org/TR/dom41/#interface-element)
  - [web-platform-tests](https://github.com/web-platform-tests/wpt/tree/master/custom-elements)

- **Shadow DOM** describes a method of combining multiple DOM trees into one hierarchy and how these trees interact with each other within a document, thus enabling better composition of the DOM.
  - [W3C Editor's Draft](http://w3c.github.io/webcomponents/spec/shadow/)
  - [DOM Living Standard](https://dom.spec.whatwg.org/#shadow-trees), section 4.2.2: shadow tree
  - [DOM Living Standard](https://dom.spec.whatwg.org/#interface-shadowroot), section 4.8: interface `ShadowRoot`
  - [W3C DOM 4.1 Working Draft](https://www.w3.org/TR/dom41/#shadow-trees), section 4.2.2: shadow tree
  - [W3C DOM 4.1 Working Draft](https://www.w3.org/TR/dom41/#interface-shadowroot), section 4.8: interface `ShadowRoot`
  - [web-platform-tests](https://github.com/web-platform-tests/wpt/tree/master/shadow-dom)

- **`<template>`** element is used to declare fragments of HTML that can be cloned and inserted in the document by script.
  - [HTML Living Standard](https://html.spec.whatwg.org/multipage/scripting.html#the-template-element)
  - [W3C HTML 5.1 2nd Edition](https://www.w3.org/TR/html51/semantics-scripting.html#the-template-element)

## Introduction

- [The Holy Grail Of Reusable Components: Custom Elements, Shadow DOM, And NPM](https://www.smashingmagazine.com/2018/07/reusable-components-custom-elements-shadow-dom-npm/)
- [The Power of Web Components](https://hacks.mozilla.org/2018/11/the-power-of-web-components/)
- [The Case for Web Components](https://alankent.me/2019/02/20/the-case-for-web-components/)
- [Styling a Web Component](https://css-tricks.com/styling-a-web-component/)
- [Web Components 101: An Introduction to Web Components](https://www.telerik.com/blogs/web-components-101-an-introduction-to-web-components)
- [Web Components in 2018](https://www.sitepen.com/blog/2018/07/06/web-components-in-2018/)
- [Web Components Introduction: Creating Custom HTML Elements in 2018](https://www.grapecity.com/en/blogs/web-components-introduction-creating-custom-html-elements-2018)
- [Web Components in 2019: An Overview of the Most Exciting Proposals for the Web Platform Related to Web Components](https://scotch.io/bar-talk/an-overview-of-the-most-exciting-proposals-for-the-web-platform-related-to-web-components?utm_source=scotch&utm_campaign=share&utm_medium=twitter)

## Custom Elements

- [Custom Elements v1: Reusable Web Components](https://developers.google.com/web/fundamentals/web-components/customelements)
- [Custom Elements Everywhere](https://custom-elements-everywhere.com)
- [All about HTML Custom Elements](https://github.com/shawnbot/custom-elements)
- [Introducing Custom Elements (WebKit)](https://webkit.org/blog/7027/introducing-custom-elements/)
- [The Case for Custom Elements: Part 1](https://medium.com/dev-channel/the-case-for-custom-elements-part-1-65d807b4b439)
- [The Case for Custom Elements: Part 2](https://medium.com/dev-channel/the-case-for-custom-elements-part-2-2efe42ce9133)
- [Custom Elements That Work Anywhere](https://robdodson.me/interoperable-custom-elements/)
- [Using Custom Elements (MDN)](https://developer.mozilla.org/en-US/docs/Web/Web_Components/Using_custom_elements)
- [A Guide to Custom Elements for React Developers](https://css-tricks.com/a-guide-to-custom-elements-for-react-developers/)

## Shadow DOM

- [Shadow DOM v1: Self-Contained Web Components](https://developers.google.com/web/fundamentals/web-components/shadowdom)
- [What is the Shadow DOM?](https://bitsofco.de/what-is-the-shadow-dom/)
- [The Rise of Shadow DOM](https://medium.com/front-end-hacking/the-rise-of-shadow-dom-84aa1f731e82)
- [Shadow DOM in depth](https://github.com/praveenpuglia/shadow-dom-in-depth)
- [What's New in Shadow DOM v1 (by examples)](http://hayato.io/2016/shadowdomv1/)
- [Introducing Slot-Based Shadow DOM API (WebKit)](https://webkit.org/blog/4096/introducing-shadow-dom-api/)
- [Using Shadow DOM (MDN)](https://developer.mozilla.org/en-US/docs/Web/Web_Components/Using_shadow_DOM)
- [Open vs. Closed Shadow DOM](https://blog.revillweb.com/open-vs-closed-shadow-dom-9f3d7427d1af)

## HTML Templates

- [&lt;template&gt;: The Content Template element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/template)
- [Using templates and slots (MDN)](https://developer.mozilla.org/en-US/docs/Web/Web_Components/Using_templates_and_slots))

## Polyfills

- [webcomponents.js](https://github.com/webcomponents/webcomponentsjs) - Suite of polyfills supporting the HTML Web Components specs.
- [custom-elements](https://github.com/webcomponents/custom-elements) - Polyfill for HTML Custom Elements v1.
- [shadydom](https://github.com/webcomponents/shadydom) - ShadowDOM v1 shim.
- [shadycss](https://github.com/webcomponents/shadycss) - ShadowDOM style encapsulation shim.
- [template](https://github.com/webcomponents/template) - Minimal polyfill for `<template>`.

## Best Practices

- [Custom Element Best Practices](https://developers.google.com/web/fundamentals/web-components/best-practices)
- [Gold Standard Checklist for Web Components](https://github.com/webcomponents/gold-standard/wiki)
- [Guidelines for creating web platform compatible components](https://w3ctag.github.io/webcomponents-design-guidelines/)
- [HowTo: Components](https://developers.google.com/web/fundamentals/web-components/examples/)
- [Open Web Components Recommendations](https://open-wc.org)

## Accessibility

- [Styling Accessibility: A Web Components Approach](https://medium.com/@cfscorreia/styling-accessibility-a-web-components-approach-dc2aa8123eb2)
- [The future of accessibility for custom elements](https://robdodson.me/the-future-of-accessibility-for-custom-elements/)
- [Web components still need to be accessible](https://www.24a11y.com/2018/web-components-still-need-to-be-accessible/)

## Use Cases

- [Bringing Order to Web Design Chaos (with Web Components)](https://dev.to/thatjoemoore/bringing-order-to-web-design-chaos--3fhb)
- [ING ❤ Web Components](https://dev.to/thepassle/ing--web-components-aef)
- [Lessons Learned, making our app with Web Components](https://medium.com/samsung-internet-dev/lessons-learned-making-our-app-with-web-components-bf55379cfcda)
- [Making Web Components Work](https://engineering.mixpanel.com/2018/06/12/making-web-components-work/)
- [Micro Frontends — extending the microservice idea to frontend development](https://micro-frontends.org)
- [Web Components — the right way](https://equinsuocha.io/blog/web-components-the-right-way/)

## Discover

- [webcomponents.org](http://webcomponents.org/) - Discuss &amp; share web components.
- [web-components-benchmark](https://github.com/vogloblinsky/web-components-benchmark) - Benchmark for a Todo list application with various Web Components technologies.
- [web-components-examples](https://github.com/mdn/web-components-examples) - Series of web components examples, related to the MDN web components documentation.
- [web-components-todo](https://github.com/shprink/web-components-todo) - Simple todo list built with various Web Components technologies.

## Libraries

### Class Based

- [Corpuscule](https://github.com/corpusculejs/corpuscule) - Small Web Components framework based on decorators.
- [LitElement](https://lit-element.polymer-project.org) - Simple base class for creating fast, lightweight web components. Part of the Polymer Project.
- [Omi](https://github.com/Tencent/omi) - Next generation web framework in 4kb JavaScript (Web Components + JSX + Proxy + Store + Path Updating).
- [Polymer](https://polymer-library.polymer-project.org) - Original web component library by the Polymer Project authors.
- [Skate](https://github.com/skatejs/skatejs) - Web component library focusing on a functional rendering pipeline and a small footprint.
- [slim.js](https://github.com/slimjs/slim.js) - Fast & Robust Front-End Micro-framework based on modern standards.
- [Smart Custom Element](https://github.com/HTMLElements/smart-custom-element) - UI library for creating custom elements with simple API.

### Functional

- [hybrids](https://github.com/hybridsjs/hybrids) - UI library for creating Web Components with simple and functional API.
- [osagai](https://github.com/HenriqueLimas/osagai) - Tiny library for creating Web Components in a functional way.
- [Switzerland](https://github.com/Wildhoney/Switzerland) - Library allowing to create Web Components in a functional way via middleware functions.
- [ullr](https://github.com/aggre/ullr) - Library for building Web Components with functional programming.

### Other

- [custom-element-ts](https://github.com/geocine/custom-elements-ts) - Create native custom elements using Typescript without using any third party libraries.
- [preact-custom-element](https://github.com/bspaulding/preact-custom-element) - Generate/register a custom element from a preact component.
- [remount](https://github.com/rstacruz/remount) - Mount React components to the DOM using custom elements.

## Component Libraries

- [Elix](https://github.com/elix/elix) - High-quality, customizable web components for common user interface patterns.
- [Material Web Components](https://github.com/material-components/material-components-web-components) - Material Design implemented as Web Components.
- [Vaadin components](https://github.com/vaadin/vaadin) - Evolving set of high-quality web components for building business web applications.
- [Wired Elements](https://github.com/wiredjs/wired-elements) - Set of common UI elements with a hand-drawn, sketchy look.

## Frameworks

### Overview

- [JavaScript frameworks, meet Web Components](https://www.voorhoede.nl/nl/blog/javascript-frameworks-meet-web-components/)

### Angular

- [Angular Elements Overview](https://angular.io/guide/elements)
- [Angular Elements, Part I: A Dynamic Dashboard In Four Steps With Web Components](https://www.softwarearchitekt.at/post/2018/07/13/angular-elements-part-i-a-dynamic-dashboard-in-four-steps-with-web-components.aspx)
- [Angular Elements, Part II: Lazy And External Web Components](https://www.softwarearchitekt.at/post/2018/07/29/angular-elements-part-ii-lazy-and-external-web-components.aspx)
- [Angular Elements, Part III: Angular Elements Without Zone.Js](https://www.softwarearchitekt.at/post/2018/07/06/angular-elements-without-zone-js.aspx)
- [Angular Elements, Part IV: Content Projection with Slots in Angular Elements (>=7)](https://www.softwarearchitekt.at/post/2018/10/31/content-projection-with-slots-in-angular-elements-7.aspx)
- [Angular Elements, Part V: Your Options For Building Angular Elements With The CLI](https://www.softwarearchitekt.at/post/2019/01/27/building-angular-elements-with-the-cli.aspx)
- [Building Custom Elements / Web Components with Angular 6](https://medium.com/@tomsu/building-web-components-with-angular-elements-746cd2a38d5b)

### Vue

- [Create & Publish Web Components With Vue CLI 3](https://vuejsdevelopers.com/2018/05/21/vue-js-web-component/)
- [Get started with Vue web components](https://medium.com/@royprins/get-started-with-vue-web-components-593b3d5b3200)

## Compilers

- [Stencil](https://stenciljs.com/docs/introduction/) - compiler that generates web components.
- [Svelte](https://svelte.technology/guide#custom-elements) - compiler which can be configured to generate custom elements.

## Books

- [Web Components in Action](https://www.manning.com/books/web-components-in-action) - Book by Ben Farrell, available at Manning early release program.
- [Web Component Essentials](https://leanpub.com/web-component-essentials) - Book by Cory Rylan, early preview edition available at Leanpub.

## Tutorials

- "**Let's Build Web Components!**" by [Benny Powers](https://github.com/bennypowers)
  - [Part 1: The Standards](https://dev.to/bennypowers/lets-build-web-components-part-1-the-standards-3e85)
  - [Part 2: The Polyfills](https://dev.to/bennypowers/lets-build-web-components-part-2-the-polyfills-dkh)
  - [Part 3: Vanilla Components](https://dev.to/bennypowers/lets-build-web-components-part-3-vanilla-components-4on3)
  - [Part 4: Polymer Library](https://dev.to/bennypowers/lets-build-web-components-part-4-polymer-library-4dk2)
  - [Part 5: LitElement](https://dev.to/bennypowers/lets-build-web-components-part-5-litelement-906)
  - [Part 6: Gluon](https://dev.to/bennypowers/lets-build-web-components-part-6-gluon-27ll)

- "**Web components: from zero to hero**" by [Pascal Schilp](https://github.com/thepassle)
  - [Part 1: An introduction to writing raw Web Components](https://dev.to/thepassle/web-components-from-zero-to-hero-4n4m)
  - [Part 2: Supercharging Web Components with lit-html](https://dev.to/thepassle/web-components-from-zero-to-hero-part-two-38p4)
  - [Part 3: Web Components hero with LitElement](https://dev.to/thepassle/web-components-from-zero-to-hero-part-three-3c5h)

## Blogs

- [Polymer Blog](https://www.polymer-project.org/blog/) - The latest goings-on with the Polymer project and in the community.

## History

The articles below represent a long story of the Web Components specifications on the way towards the standardization.
Some of them refer to earlier, so-called "v0" Shadow DOM and Custom Elements specs, and abandoned HTML Imports spec.
These materials are here for historical reasons only, they are grouped by years and listed in chronological order.

### 2017

- [Web Components: The Long Game](https://infrequently.org/2017/10/web-components-the-long-game/)
- [The broken promise of Web Components](https://dmitriid.com/blog/2017/03/the-broken-promise-of-web-components/)
- [Regarding the broken promise of Web Components](http://robdodson.me/regarding-the-broken-promise-of-web-components/)

### 2016

- [Demythstifying Web Components](http://www.backalleycoder.com/2016/08/26/demythstifying-web-components/)
- [Understanding Web Components](https://medium.com/the-ui-files/understanding-web-components-d051baa66019)

### 2015

- [Web Components and their role in the future of web development](http://kaytcat.github.io/web-components/)
- [Microsoft Edge and Web Components](https://blogs.windows.com/msedgedev/2015/07/15/microsoft-edge-and-web-components/)
- [Bringing componentization to the web: An overview of Web Components](https://blogs.windows.com/msedgedev/2015/07/14/bringing-componentization-to-the-web-an-overview-of-web-components/)
- [The state of Web Components](https://hacks.mozilla.org/2015/06/the-state-of-web-components/)

### 2014

- [A No-Nonsense Guide to Web Components](http://cbateman.com/blog/a-no-nonsense-guide-to-web-components-part-1-the-specs/)
- [Mozilla and Web Components: Update](https://hacks.mozilla.org/2014/12/mozilla-and-web-components/)
- [The State of the Componentised Web](https://www.leggetter.co.uk/2014/08/06/state-componentised-web.html)
- [Web Components and you – dangers to avoid](https://christianheilmann.com/2014/04/18/web-components-and-you-dangers-to-avoid/)
- [The Web's Declarative, Composable Future](https://addyosmani.com/blog/the-webs-declarative-composable-future/)

### 2013

- [A Guide to Web Components](https://css-tricks.com/modular-future-web-components/)

### 2012

- [Notes on Web Components + ARIA](https://developer.paciellogroup.com/blog/2012/07/notes-on-web-components-aria/)
- [Introduction to Web Components](https://www.w3.org/TR/2012/WD-components-intro-20120522/)

### 2011

- [Web Components and Model Driven Views by Alex Russell](https://fronteers.nl/congres/2011/sessions/web-components-and-model-driven-views-alex-russell)
- [What the Heck is Shadow DOM?](https://glazkov.com/2011/01/14/what-the-heck-is-shadow-dom/)

## Future

### CSS Shadow Parts

- [W3C First Public Working Draft](https://www.w3.org/TR/css-shadow-parts-1/)
- [web-platform-tests](https://github.com/web-platform-tests/wpt/tree/master/css/css-shadow-parts)
- [Explainer: CSS Shadow ::part and ::theme](https://github.com/fergald/docs/blob/master/explainers/css-shadow-parts-1.md)
- [::part and ::theme pseudo elements on shadow hosts](https://www.chromestatus.com/features/5763933658939392) - Feature in Chrome platform status.
- [Intent to Ship: CSS shadow parts](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/DAmfw08GGis/-0OyBbTmBgAJ) - Blink implementation update, 10.12.2018.
- [Mozilla issue: Implement CSS Shadow Parts](https://bugzilla.mozilla.org/show_bug.cgi?id=1505489)
- [WebKit issue: Add the support for the CSS shadow parts](https://bugs.webkit.org/show_bug.cgi?id=149443)

### Form-associated Custom Elements

- [GitHub issue](https://github.com/w3c/webcomponents/issues/187)
- [Intent to Implement: Form-associated custom elements](https://groups.google.com/a/chromium.org/forum/#!topic/blink-dev/HW8j_JLLiPo) - Blink implementation update, 16.11.2018.
- [Form Participation API Explained](https://docs.google.com/document/d/1JO8puctCSpW-ZYGU8lF-h4FWRIDQNDVexzHoOQ2iQmY/edit?usp=sharing) - Document by Google Chrome team.
- [Form-associated custom elements](https://www.chromestatus.com/features/4708990554472448) - Feature in Chrome platform status.

### Constructable Stylesheet Objects

- [GitHub issue](https://github.com/w3c/webcomponents/issues/468)
- [Specification Draft](https://wicg.github.io/construct-stylesheets/)
- [web-platform-tests](https://github.com/web-platform-tests/wpt/blob/master/css/cssom/CSSStyleSheet-constructable.html)
- [Explainer](https://github.com/WICG/construct-stylesheets/blob/gh-pages/explainer.md)
- [Intent to Ship: Constructable Stylesheet Objects](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/gL2EVBzO5og/YfId9-vqBAAJ) - Blink implementation update, 13.12.2018.
- [Constructable Stylesheets](https://www.chromestatus.com/feature/5394843094220800) - Feature in Chrome platform status.
- [GitHub issue for Polymer integration](https://github.com/Polymer/polymer/issues/5456)
- [GitHub issue for lit-html integration](https://github.com/Polymer/lit-html/issues/689)

## Who To Follow

<table>
  <tbody>
    <tr>
      <td align="center">
        <a href="https://twitter.com/ChromiumDev">
          <img width="80" height="80" src="https://pbs.twimg.com/profile_images/1065986962467647489/Qrc3K-jZ_80x80.jpg">
          <div>Chrome Developers</div>
        </a>
      </td>
      <td align="center">
        <a href="https://twitter.com/polymer">
          <img width="80" height="80" src="https://pbs.twimg.com/profile_images/1063502058337136640/RmlG_bbW_80x80.jpg">
          <div>Polymer</div>
        </a>
      </td>
      <td align="center">
        <a href="https://twitter.com/MSEdgeUpdates">
          <img width="80" height="80" src="https://pbs.twimg.com/profile_images/984976713351356416/YtUr94vb_80x80.jpg">
          <div>Edge Platform Updates</div>
        </a>
      </td>
      <td align="center">
        <a href="https://twitter.com/web_components">
          <img width="80" height="80" src="https://pbs.twimg.com/profile_images/836671393844572160/eRcwt6Fw_80x80.jpg">
          <div>Web Components</div>
        </a>
      </td>
    </tr>
    <tr>
      <td align="center">
        <a href="https://twitter.com/shadow_hayato">
          <img width="80" height="80" src="https://pbs.twimg.com/profile_images/448411087294046208/Nd6c9fr-_80x80.png">
          <div>Hayato Ito</div>
        </a>
      </td>
      <td align="center">
        <a href="https://twitter.com/rob_dodson">
          <img width="80" height="80" src="https://pbs.twimg.com/profile_images/1031947699019427840/xl6p8ZBu_80x80.jpg">
          <div>Rob Dodson</div>
        </a>
      </td>
      <td align="center">
        <a href="https://twitter.com/ebidel">
          <img width="80" height="80" src="https://pbs.twimg.com/profile_images/955031454781616129/JRpZOp1l_80x80.jpg">
          <div>Eric Bidelman</div>
        </a>
      </td>
      <td align="center">
        <a href="https://twitter.com/justinfagnani">
          <img width="80" height="80" src="https://pbs.twimg.com/profile_images/378800000808710206/2dbdaa1cb7b0db02f997aea5b40f29b8_80x80.jpeg">
          <div>Justin Fagnani</div>
        </a>
      </td>
    </tr>
  <tbody>
</table>

## License

Copyright 2014-2018, All rights reserved.

Code licensed under the:
[MIT license](http://mateusortiz.mit-license.org)

@author Mateus Ortiz <mteusortiz@gmail.com>
