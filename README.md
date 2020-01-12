# Web Components the Right Way

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of awesome Web Components resources.

[Web Components](https://developer.mozilla.org/en-US/docs/Web/Web_Components) — a suite of different technologies allowing you to create reusable custom elements — with their functionality encapsulated away from the rest of your code — and utilize them in your web apps.

## Contents

- [Specifications](#specifications)
  - [Standards](#standards)
  - [Proposals](#proposals)
    - [CSS Shadow Parts](#css-shadow-parts)
    - [Form-associated Custom Elements](#form-associated-custom-elements)
    - [Constructable Stylesheet Objects](#constructable-stylesheet-objects)
    - [Custom State Pseudo Class](#custom-state-pseudo-class)
  - [Polyfills](#polyfills)
    - [@webcomponents](#webcomponents)
    - [@ungap](#ungap)
- [Articles](#articles)
  - [Introduction](#introduction)
  - [Custom Elements](#custom-elements)
  - [Shadow DOM](#shadow-dom)
  - [HTML Templates](#html-templates)
  - [Best Practices](#best-practices)
  - [Interoperability](#interoperability)
  - [Accessibility](#accessibility)
  - [Use Cases](#use-cases)
- [Libraries](#libraries)
  - [Class Based](#class-based)
  - [Functional](#functional)
  - [Compilers](#compilers)
  - [Other](#other)
- [Component Libraries](#component-libraries)
- [Frameworks](#frameworks)
  - [Angular](#angular)
  - [Vue](#vue)
  - [Ember](#ember)
  - [Aurelia](#aurelia)
- [Tools](#tools)
- [Books](#books)
- [Tutorials](#tutorials)
- [Podcasts](#podcasts)
- [Benchmarks](#benchmarks)
- [Miscellaneous](#miscellaneous)
- [History](#history)
- [Who to follow](#who-to-follow)
- [License](#license)

> Web Components the Right Way was made with love by [Mateus Ortiz](https://twitter.com/mteusortiz) and maintained by [Serhii Kulykov](https://twitter.com/serhiikulykov)

## Specifications

### Standards

- **Custom Elements** provide a way for authors to build their own fully-featured DOM elements.
  - [HTML Living Standard](https://html.spec.whatwg.org/multipage/custom-elements.html)
  - [DOM Living Standard](https://dom.spec.whatwg.org/#concept-element)
  - [web-platform-tests](https://github.com/web-platform-tests/wpt/tree/master/custom-elements)
  - [Chrome Platform Status metrics](https://chromestatus.com/metrics/feature/timeline/popularity/1689)

- **Shadow DOM** describes a method of combining multiple DOM trees into one hierarchy and how these trees interact with each other within a document, thus enabling better composition of the DOM.
  - [DOM Living Standard](https://dom.spec.whatwg.org/#shadow-trees), section 4.2.2: shadow tree
  - [DOM Living Standard](https://dom.spec.whatwg.org/#interface-shadowroot), section 4.8: interface `ShadowRoot`
  - [web-platform-tests](https://github.com/web-platform-tests/wpt/tree/master/shadow-dom)
  - [Chrome Platform Status metrics](https://chromestatus.com/metrics/feature/timeline/popularity/804)

- **`<template>`** element is used to declare fragments of HTML that can be cloned and inserted in the document by script.
  - [HTML Living Standard](https://html.spec.whatwg.org/multipage/scripting.html#the-template-element)
  - [Chrome Platform Status metrics](https://chromestatus.com/metrics/feature/timeline/popularity/2769)

### Proposals

#### CSS Shadow Parts

- [W3C First Public Working Draft](https://www.w3.org/TR/css-shadow-parts-1/)
- [web-platform-tests](https://github.com/web-platform-tests/wpt/tree/master/css/css-shadow-parts)
- [Explainer: CSS Shadow ::part and ::theme](https://github.com/fergald/docs/blob/master/explainers/css-shadow-parts-1.md)
- [::part and ::theme pseudo elements on shadow hosts](https://www.chromestatus.com/features/5763933658939392) - Feature in Chrome platform status.
- [Mozilla issue: Implement CSS Shadow Parts](https://bugzilla.mozilla.org/show_bug.cgi?id=1505489)
- [WebKit issue: Add the support for the CSS shadow parts](https://bugs.webkit.org/show_bug.cgi?id=149443)

#### Form-associated Custom Elements

- [Form Participation API Explained](https://docs.google.com/document/d/1JO8puctCSpW-ZYGU8lF-h4FWRIDQNDVexzHoOQ2iQmY/edit?usp=sharing) - Document by Google Chrome team.
- [Form-associated custom elements](https://www.chromestatus.com/features/4708990554472448) - Feature in Chrome platform status.
- [web-platform-tests](https://github.com/web-platform-tests/wpt/tree/master/custom-elements/form-associated)

#### Custom State Pseudo class

- [Blink: Intent to implement](https://groups.google.com/a/chromium.org/forum/#!topic/blink-dev/CApU9QIu3TM)
- [`ElementInternals`'s `states` property and the `:state()` pseudo class](https://github.com/w3c/webcomponents/blob/gh-pages/proposals/custom-states-and-state-pseudo-class.md)

#### Constructable Stylesheet Objects

- [Specification Draft](https://wicg.github.io/construct-stylesheets/)
- [web-platform-tests](https://github.com/web-platform-tests/wpt/blob/master/css/cssom/CSSStyleSheet-constructable.html)
- [Explainer](https://github.com/WICG/construct-stylesheets/blob/gh-pages/explainer.md)
- [Constructable Stylesheets](https://www.chromestatus.com/feature/5394843094220800) - Feature in Chrome platform status.

### Polyfills

#### @webcomponents

The polyfills below are maintained by Polymer team.

- [@webcomponents/custom-elements](https://github.com/webcomponents/polyfills/tree/master/packages/custom-elements) - Polyfill for HTML Custom Elements v1.
- [@webcomponents/shadydom](https://github.com/webcomponents/polyfills/tree/master/packages/shadydom) - ShadowDOM v1 shim.
- [@webcomponents/shadycss](https://github.com/webcomponents/polyfills/tree/master/packages/shadycss) - ShadowDOM style encapsulation shim.
- [@webcomponents/template](https://github.com/webcomponents/polyfills/tree/master/packages/template) - Minimal polyfill for `<template>`.

#### @ungap

The polyfills below are maintained by [ungap project](https://ungap.github.io).

- [@ungap/custom-elements-builtin](https://github.com/ungap/custom-elements-builtin) - polyfill for Custom Elements builtin extends.

## Articles

### Introduction

- [The Holy Grail Of Reusable Components: Custom Elements, Shadow DOM, And NPM](https://www.smashingmagazine.com/2018/07/reusable-components-custom-elements-shadow-dom-npm/)
- [The Power of Web Components](https://hacks.mozilla.org/2018/11/the-power-of-web-components/)
- [The Case for Web Components](https://alankent.me/2019/02/20/the-case-for-web-components/)
- [Styling a Web Component](https://css-tricks.com/styling-a-web-component/)
- [Web Components 101: An Introduction to Web Components](https://www.telerik.com/blogs/web-components-101-an-introduction-to-web-components)
- [Web Components in 2018](https://www.sitepen.com/blog/2018/07/06/web-components-in-2018/)
- [Web Components Introduction: Creating Custom HTML Elements in 2018](https://www.grapecity.com/en/blogs/web-components-introduction-creating-custom-html-elements-2018)
- [Web Components in 2019: An Overview of the Most Exciting Proposals for the Web Platform Related to Web Components](https://scotch.io/bar-talk/an-overview-of-the-most-exciting-proposals-for-the-web-platform-related-to-web-components?utm_source=scotch&utm_campaign=share&utm_medium=twitter)

### Custom Elements

- [Custom Elements v1: Reusable Web Components](https://developers.google.com/web/fundamentals/web-components/customelements)
- [Custom Elements Everywhere](https://custom-elements-everywhere.com)
- [All about HTML Custom Elements](https://github.com/shawnbot/custom-elements)
- [Introducing Custom Elements (WebKit)](https://webkit.org/blog/7027/introducing-custom-elements/)
- [The Case for Custom Elements: Part 1](https://medium.com/dev-channel/the-case-for-custom-elements-part-1-65d807b4b439)
- [The Case for Custom Elements: Part 2](https://medium.com/dev-channel/the-case-for-custom-elements-part-2-2efe42ce9133)
- [Using Custom Elements (MDN)](https://developer.mozilla.org/en-US/docs/Web/Web_Components/Using_custom_elements)
- [A Guide to Custom Elements for React Developers](https://css-tricks.com/a-guide-to-custom-elements-for-react-developers/)

### Shadow DOM

- [Shadow DOM v1: Self-Contained Web Components](https://developers.google.com/web/fundamentals/web-components/shadowdom)
- [What is the Shadow DOM?](https://bitsofco.de/what-is-the-shadow-dom/)
- [The Rise of Shadow DOM](https://medium.com/front-end-hacking/the-rise-of-shadow-dom-84aa1f731e82)
- [Shadow DOM in depth](https://github.com/praveenpuglia/shadow-dom-in-depth)
- [What's New in Shadow DOM v1 (by examples)](http://hayato.io/2016/shadowdomv1/)
- [Introducing Slot-Based Shadow DOM API (WebKit)](https://webkit.org/blog/4096/introducing-shadow-dom-api/)
- [Using Shadow DOM (MDN)](https://developer.mozilla.org/en-US/docs/Web/Web_Components/Using_shadow_DOM)
- [Open vs. Closed Shadow DOM](https://blog.revillweb.com/open-vs-closed-shadow-dom-9f3d7427d1af)

### HTML Templates

- [&lt;template&gt;: The Content Template element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/template)
- [Using templates and slots (MDN)](https://developer.mozilla.org/en-US/docs/Web/Web_Components/Using_templates_and_slots)

### Best Practices

- [Custom Element Best Practices](https://developers.google.com/web/fundamentals/web-components/best-practices)
- [Gold Standard Checklist for Web Components](https://github.com/webcomponents/gold-standard/wiki)
- [Guidelines for creating web platform compatible components](https://w3ctag.github.io/webcomponents-design-guidelines/)
- [HowTo: Components](https://developers.google.com/web/fundamentals/web-components/examples/)
- [Open Web Components Recommendations](https://open-wc.org)

### Interoperability

- [Custom Elements That Work Anywhere](https://robdodson.me/interoperable-custom-elements/)
- [JavaScript frameworks, meet Web Components](https://www.voorhoede.nl/nl/blog/javascript-frameworks-meet-web-components/)
- [Web Components: Seamlessly interoperable](https://medium.com/@sergicontre/web-components-seamlessly-interoperable-82efd6989ca4)

### Accessibility

- [Styling Accessibility: A Web Components Approach](https://medium.com/@cfscorreia/styling-accessibility-a-web-components-approach-dc2aa8123eb2)
- [The future of accessibility for custom elements](https://robdodson.me/the-future-of-accessibility-for-custom-elements/)
- [Web components still need to be accessible](https://www.24a11y.com/2018/web-components-still-need-to-be-accessible/)

### Use Cases

- [Bringing Order to Web Design Chaos (with Web Components)](https://dev.to/thatjoemoore/bringing-order-to-web-design-chaos--3fhb)
- [ING ❤ Web Components](https://dev.to/thepassle/ing--web-components-aef)
- [Lessons Learned, making our app with Web Components](https://medium.com/samsung-internet-dev/lessons-learned-making-our-app-with-web-components-bf55379cfcda)
- [Making Web Components Work](https://engineering.mixpanel.com/2018/06/12/making-web-components-work/)
- [Micro Frontends — extending the microservice idea to frontend development](https://micro-frontends.org)
- [Web Components — the right way](https://equinsuocha.io/blog/web-components-the-right-way/)
- [Reasons Web Components are perfect for a big company](https://medium.com/@sergicontre/reasons-web-components-are-perfect-for-a-big-company-28790d712ad5)
- [Why we use Web Components](https://viljamis.com/2019/why-we-use-web-components/)

## Libraries

### Class Based

- [Corpuscule](https://github.com/corpusculejs/corpuscule) - Small Web Components framework based on decorators.
- [LitElement](https://lit-element.polymer-project.org) - Simple base class for creating fast, lightweight web components. Part of the Polymer Project.
- [Lightning Web Components](https://github.com/salesforce/lwc) - blazing fast, enterprise-grade Web Components foundation.
- [Omi](https://github.com/Tencent/omi) - Next generation web framework in 4kb JavaScript (Web Components + JSX + Proxy + Store + Path Updating).
- [Polymer](https://polymer-library.polymer-project.org) - Original web component library by the Polymer Project authors.
- [readymade](https://github.com/readymade-ui/readymade) - JavaScript microlibrary for developing Web Components with decorators.
- [Skate](https://github.com/skatejs/skatejs) - Web component library focusing on a functional rendering pipeline and a small footprint.
- [slim.js](https://github.com/slimjs/slim.js) - Fast & Robust Front-End Micro-framework based on modern standards.
- [Smart Custom Element](https://github.com/HTMLElements/smart-custom-element) - UI library for creating custom elements with simple API.

### Functional

- [atomico](https://github.com/atomicojs/atomico) - Small library for the creation of interfaces based on web components using functions and hooks.
- [functional-web-component](https://github.com/wtnbass/functional-web-component) - Functional component like React, but for Web Components.
- [haunted](https://github.com/matthewp/haunted) - React's Hooks API implemented for web components.
- [hybrids](https://github.com/hybridsjs/hybrids) - UI library for creating Web Components with simple and functional API.
- [reLift-HTML](https://github.com/mardix/relift-html) - Small (3kb) view library allowing to create Web Components and to make HTML pages reactive.
- [osagai](https://github.com/HenriqueLimas/osagai) - Tiny library for creating Web Components in a functional way.
- [Switzerland](https://github.com/Wildhoney/Switzerland) - Library allowing to create Web Components in a functional way via middleware functions.
- [ullr](https://github.com/aggre/ullr) - Library for building Web Components with functional programming.

### Compilers

- [Stencil](https://stenciljs.com) - Compiler that generates Web Components.
- [Svelte](https://svelte.dev) - Cybernetically enhanced web apps (can optionally generate Web Components).

### Other

- [custom-element-ts](https://github.com/geocine/custom-elements-ts) - Create native custom elements using Typescript without using any third party libraries.
- [preact-custom-element](https://github.com/bspaulding/preact-custom-element) - Generate/register a custom element from a preact component.
- [remount](https://github.com/rstacruz/remount) - Mount React components to the DOM using custom elements.
- [@riotjs/custom-elements](https://github.com/riot/custom-elements) - Simple API to create vanilla custom elements with Riot.js.

## Component Libraries

- [Amber Components](https://github.com/bitrockteam/amber-components) - Web Components implementation of the Amber Design System.
- [AMP HTML](https://github.com/ampproject/amphtml) - Web component library for building web pages that render with reliable and fast performance.
- [Bronconents](https://github.com/marius2502/bronconents) - Modern Web Components built with Lit-Element.
- [Carbon Custom Elements](https://github.com/carbon-design-system/carbon-custom-elements) - Experimental variant of Carbon Design System built with Web Components.
- [Clever components](https://github.com/CleverCloud/clever-components) - Collection of Web Components made by Clever Cloud.
- [Elix](https://github.com/elix/elix) - High-quality, customizable web components for common user interface patterns.
- [LRNWebComponents](https://github.com/elmsln/lrnwebcomponents/) - ELMS:LN produced web components for any project.
- [Material Web Components](https://github.com/material-components/material-components-web-components) - Material Design implemented as Web Components.
- [Microsoft Graph Toolkit](https://github.com/microsoftgraph/microsoft-graph-toolkit) - Collection of web components for the Microsoft Graph.
- [PatternFly Elements](https://github.com/patternfly/patternfly-elements) - Collection of flexible and lightweight Web Components, and the tools to build them.
- [UI5 Web Components](https://github.com/SAP/ui5-webcomponents) - Components library providing the enterprise-flavored sugar on top of native APIs.
- [Vaadin components](https://github.com/vaadin/vaadin) - Evolving set of high-quality web components for building business web applications.
- [Wired Elements](https://github.com/wiredjs/wired-elements) - Set of common UI elements with a hand-drawn, sketchy look.

## Frameworks

### Angular

- [Angular Elements Overview](https://angular.io/guide/elements)
- [Angular Elements, Part I: A Dynamic Dashboard In Four Steps With Web Components](https://www.softwarearchitekt.at/post/2018/07/13/angular-elements-part-i-a-dynamic-dashboard-in-four-steps-with-web-components.aspx)
- [Angular Elements, Part II: Lazy And External Web Components](https://www.softwarearchitekt.at/post/2018/07/29/angular-elements-part-ii-lazy-and-external-web-components.aspx)
- [Angular Elements, Part III: Angular Elements Without Zone.Js](https://www.softwarearchitekt.at/post/2018/07/06/angular-elements-without-zone-js.aspx)
- [Angular Elements, Part IV: Content Projection with Slots in Angular Elements (>=7)](https://www.softwarearchitekt.at/post/2018/10/31/content-projection-with-slots-in-angular-elements-7.aspx)
- [Angular Elements, Part V: Your Options For Building Angular Elements With The CLI](https://www.softwarearchitekt.at/post/2019/01/27/building-angular-elements-with-the-cli.aspx)
- [Building Custom Elements / Web Components with Angular 6](https://medium.com/@tomsu/building-web-components-with-angular-elements-746cd2a38d5b)
- [Web Components With Angular Ivy In 6 Steps](https://www.softwarearchitekt.at/post/2019/05/18/web-components-custom-elements-with-angular-ivy-in-6-steps.aspx)

### Vue

- [Create & Publish Web Components With Vue CLI 3](https://vuejsdevelopers.com/2018/05/21/vue-js-web-component/)
- [Get started with Vue web components](https://medium.com/@royprins/get-started-with-vue-web-components-593b3d5b3200)

### Ember

- [ember-shadow-dom](https://github.com/knownasilya/ember-shadow-dom)

### Aurelia

- [Aurelia Web Components plugin](https://github.com/aurelia/web-components)

## Tools

- [Cypress Daywalker](https://github.com/JaySunSyn/cypress-daywalker) - Web Components and Shadow DOM support for Cypress.
- [web-component-analyzer](https://github.com/runem/web-component-analyzer) - CLI that analyzes web components and emits documentation / diagnostics.

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
  - [Part 7: Hybrids](https://dev.to/bennypowers/lets-build-web-components-part-7-hybrids-187l)

- "**Web components: from zero to hero**" by [Pascal Schilp](https://github.com/thepassle)
  - [Part 1: An introduction to writing raw Web Components](https://dev.to/thepassle/web-components-from-zero-to-hero-4n4m)
  - [Part 2: Supercharging Web Components with lit-html](https://dev.to/thepassle/web-components-from-zero-to-hero-part-two-38p4)
  - [Part 3: Web Components hero with LitElement](https://dev.to/thepassle/web-components-from-zero-to-hero-part-three-3c5h)

- **CSS tricks** article series by [Caleb Williams](https://css-tricks.com/author/calebdwilliams/)
  - [Part 1: An Introduction to Web Components](https://css-tricks.com/an-introduction-to-web-components/)
  - [Part 2: Crafting Reusable HTML Templates](https://css-tricks.com/crafting-reusable-html-templates/)
  - [Part 3: Creating a Custom Element from Scratch](https://css-tricks.com/creating-a-custom-element-from-scratch)
  - [Part 4: Encapsulating Style and Structure with Shadow DOM](https://css-tricks.com/encapsulating-style-and-structure-with-shadow-dom/)
  - [Part 5: Advanced Tooling for Web Components](https://css-tricks.com/advanced-tooling-for-web-components/)

## Podcasts

- [Frontend Happy Hour, episode 62: Web Components - shots of shadow DOM](https://frontendhappyhour.com/episodes/web-components-shots-of-shadow-dom/)
- [Real Talk JavaScript, episode 7: Custom Web Components with Rob Wormald](https://realtalkjavascript.simplecast.fm/eaf3db9e)

## Benchmarks

- [web-components-benchmark](https://vogloblinsky.github.io/web-components-benchmark/) - Benchmark Web Components technologies with various examples.
- [web-components-todo](https://wc-todo.firebaseapp.com/) - The same todo application built in different Web Components libraries for benchmark purpose.

## Miscellaneous

- [bruck](https://github.com/Heydon/bruck) - Prototyping system built with web components and the Houdini Paint API.
- [Vaadin Directory](https://vaadin.com/directory) - Publish, discuss and rate web components
- [webcomponents.dev](https://webcomponents.dev) - Your studio for Web Components.
- [webcomponents.org](http://webcomponents.org/) - Discuss &amp; share web components.
- [webcomponents.news](http://webcomponents.news) - Collection of articles, tutorials, micro-libraries and websites that showcase Web Components.
- [web-components-examples](https://github.com/mdn/web-components-examples) - Series of web components examples, related to the MDN web components documentation.

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
