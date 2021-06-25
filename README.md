# Web Components the Right Way

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of awesome Web Components resources.

[Web Components](https://developer.mozilla.org/en-US/docs/Web/Web_Components) — a suite of different technologies allowing you to create reusable custom elements — with their functionality encapsulated away from the rest of your code — and utilize them in your web apps.

## Contents

- [Introduction](#introduction)
- [Standards](#standards)
  - [Custom Elements](#custom-elements)
  - [Shadow DOM](#shadow-dom)
  - [HTML Templates](#html-templates)
  - [CSS Shadow Parts](#css-shadow-parts)
- [Polyfills](#polyfills)
  - [Custom Elements polyfills](#custom-elements-polyfills)
  - [Customized Built-in Elements polyfills](#customized-built-in-elements-polyfills)
  - [Shadow DOM shims](#shadow-dom-shims)
  - [HTML Templates polyfills](#html-templates-polyfills)
- [Guides](#guides)
  - [Accessibility](#accessibility)
  - [Best Practices](#best-practices)
  - [Codelabs](#codelabs)
  - [Examples](#examples)
- [Articles](#articles)
  - [Architecture](#architecture)
  - [Interoperability](#interoperability)
  - [Limitations](#limitations)
  - [Styling](#styling)
- [Real World](#real-world)
  - [Case Studies](#case-studies)
  - [Components](#components)
  - [Component Libraries](#component-libraries)
  - [Design Systems](#design-systems)
  - [Use Cases](#use-cases)
- [Libraries](#libraries)
  - [Class Based](#class-based)
  - [Functional](#functional)
  - [Integrations](#integrations)
  - [Benchmarks](#benchmarks)
- [Frameworks](#frameworks)
  - [Angular](#angular)
  - [React](#react)
  - [Vue](#vue)
  - [Svelte](#svelte)
- [Ecosystem](#ecosystem)
  - [Starter Kits](#starter-kits)
  - [Tools](#tools)
- [Books](#books)
- [Tutorials](#tutorials)
- [Insights](#insights)
  - [Podcasts](#podcasts)
  - [Presentations](#presentations)
  - [Talks](#talks)
- [Usage Metrics](#usage-metrics)
- [Proposals](#proposals)
  - [Form-associated Custom Elements](#form-associated-custom-elements)
  - [Constructable Stylesheet Objects](#constructable-stylesheet-objects)
  - [Custom State Pseudo Class](#custom-state-pseudo-class)
- [Miscellaneous](#miscellaneous)
- [History](#history)
- [Who to follow](#who-to-follow)
- [License](#license)

> Web Components the Right Way was made with love by [Mateus Ortiz](https://twitter.com/mteusortiz) and maintained by [Serhii Kulykov](https://twitter.com/serhiikulykov)

## Introduction

- [Web Components 101](https://nhswd.com/blog/web-components-101-what-are-web-components/)
- [Intro to Web Components](https://developer.salesforce.com/blogs/2020/01/intro-to-web-components.html)
- [MDN - Web Components](https://developer.mozilla.org/en-US/docs/Web/Web_Components)
- [The Holy Grail Of Reusable Components: Custom Elements, Shadow DOM, And NPM](https://www.smashingmagazine.com/2018/07/reusable-components-custom-elements-shadow-dom-npm/)
- [The Power of Web Components](https://hacks.mozilla.org/2018/11/the-power-of-web-components/)

## Standards

### Custom Elements

Custom Elements provide a way for authors to build their own fully-featured DOM elements.

- [HTML Living Standard: Custom elements](https://html.spec.whatwg.org/multipage/custom-elements.html)
- [A Guide to Custom Elements for React Developers](https://css-tricks.com/a-guide-to-custom-elements-for-react-developers/)
- [All about HTML Custom Elements](https://github.com/shawnbot/custom-elements)
- [Custom Elements v1: Reusable Web Components](https://developers.google.com/web/fundamentals/web-components/customelements)
- [Handy Custom Elements' Patterns](https://gist.github.com/WebReflection/ec9f6687842aa385477c4afca625bbf4)
- [MDN - Using Custom Elements](https://developer.mozilla.org/en-US/docs/Web/Web_Components/Using_custom_elements)
- [web-platform-tests](https://github.com/web-platform-tests/wpt/tree/master/custom-elements)

### Shadow DOM

Shadow DOM describes a method of combining multiple DOM trees into one hierarchy and how these trees interact with each other within a document, thus enabling better composition of the DOM.

- [DOM Living Standard: Interface `ShadowRoot`](https://dom.spec.whatwg.org/#interface-shadowroot)
- [DOM Living Standard: Shadow tree](https://dom.spec.whatwg.org/#shadow-trees)
- [MDN - Using Shadow DOM](https://developer.mozilla.org/en-US/docs/Web/Web_Components/Using_shadow_DOM)
- [Open vs. Closed Shadow DOM](https://blog.revillweb.com/open-vs-closed-shadow-dom-9f3d7427d1af)
- [Shadow DOM in depth](https://github.com/praveenpuglia/shadow-dom-in-depth)
- [Shadow DOM v1: Self-Contained Web Components](https://developers.google.com/web/fundamentals/web-components/shadowdom)
- [The Rise of Shadow DOM](https://medium.com/front-end-hacking/the-rise-of-shadow-dom-84aa1f731e82)
- [Understanding Slot Updates with Web Components](https://coryrylan.com/blog/understanding-slot-updates-with-web-components)
- [What is the Shadow DOM?](https://bitsofco.de/what-is-the-shadow-dom/)
- [web-platform-tests](https://github.com/web-platform-tests/wpt/tree/master/shadow-dom)

### HTML Templates

`<template>` element is used to declare fragments of HTML that can be cloned and inserted in the document by script.

- [HTML Living Standard: The `template` element](https://html.spec.whatwg.org/multipage/scripting.html#the-template-element)
- [MDN - &lt;template&gt;: The Content Template element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/template)
- [MDN - Using templates and slots](https://developer.mozilla.org/en-US/docs/Web/Web_Components/Using_templates_and_slots)
- [web-platform-tests](https://github.com/web-platform-tests/wpt/tree/master/html/semantics/scripting-1/the-template-element)

### CSS Shadow Parts

CSS Shadow Parts allow developers to expose certain elements inside Shadow DOM for styling purposes.

- [W3C First Public Working Draft](https://www.w3.org/TR/css-shadow-parts-1/)
- [CSS Shadow Parts are coming!](https://dev.to/webpadawan/css-shadow-parts-are-coming-mi5)
- [MDN - `::part()` CSS pseudo element](https://developer.mozilla.org/en-US/docs/Web/CSS/::part)
- [MDN - `part` global attribute](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/part)
- [::part and ::theme, an ::explainer](https://meowni.ca/posts/part-theme-explainer/)
- [web-platform-tests](https://github.com/web-platform-tests/wpt/tree/master/css/css-shadow-parts)

### Polyfills

### Custom Elements polyfills

- [@webcomponents/custom-elements](https://github.com/webcomponents/polyfills/tree/master/packages/custom-elements) - Custom Elements polyfill by Polymer team.
- [document-register-element](https://github.com/WebReflection/document-register-element) - Custom Elements polyfill by Andrea Giammarchi.

### Customized Built-in Elements polyfills

- [@corpuscule/custom-builtin-elements](https://github.com/corpusculejs/custom-builtin-elements) - Customized built-in elements polyfill by [CorpusculeJS](https://github.com/corpusculejs).
- [@ungap/custom-elements-builtin](https://github.com/ungap/custom-elements-builtin) - Customized built-in elements polyfill by [ungap project](https://ungap.github.io).

### Shadow DOM shims

- [@webcomponents/shadydom](https://github.com/webcomponents/polyfills/tree/master/packages/shadydom) - ShadowDOM v1 shim.
- [@webcomponents/shadycss](https://github.com/webcomponents/polyfills/tree/master/packages/shadycss) - ShadowDOM style encapsulation shim.
- [@lwc/synthetic-shadow](https://github.com/salesforce/lwc/blob/master/packages/@lwc/synthetic-shadow) - Shadow DOM polyfill by [LWC](https://lwc.dev).

### HTML Templates polyfills

- [@webcomponents/template](https://github.com/webcomponents/polyfills/tree/master/packages/template) - Minimal polyfill for `<template>`.
- [@ungap/import-node](https://github.com/ungap/import-node) - An `importNode` polyfill for IE11 by [ungap project](https://ungap.github.io).

## Guides

### Accessibility

- [Accessibility for Web Components](https://developer.salesforce.com/blogs/2020/01/accessibility-for-web-components.html)
- [How to Make Accessible Web Components — a Brief Guide](https://www.sitepoint.com/accessible-web-components/)
- [The future of accessibility for custom elements](https://robdodson.me/the-future-of-accessibility-for-custom-elements/)
- [The Guide to Accessible Web Components](https://www.erikkroes.nl/blog/accessibility/the-guide-to-accessible-web-components-draft/)
- [Web Components and the Accessibility Object model (AOM)](https://www.24a11y.com/2019/web-components-and-the-aom/)
- [Web Components punch list](https://www.tpgi.com/web-components-punch-list/)
- [Web components still need to be accessible](https://www.24a11y.com/2018/web-components-still-need-to-be-accessible/)

### Best Practices

- [Custom Element Best Practices](https://developers.google.com/web/fundamentals/web-components/best-practices)
- [Developing Components: Publishing](https://open-wc.org/guides/developing-components/publishing/)
- [Gold Standard Checklist for Web Components](https://github.com/webcomponents/gold-standard/wiki)
- [Guidelines for creating web platform compatible components](https://w3ctag.github.io/webcomponents-design-guidelines/)
- [How to Publish Web Components to NPM](https://justinfagnani.com/2019/11/01/how-to-publish-web-components-to-npm/)
- [Open Web Components Recommendations](https://open-wc.org)

### Codelabs

- [Build a Story Web Component with LitElement](https://dev.to/straversi/build-a-story-web-component-with-litelement-e59)
- [Building Custom Elements with Web Components for the 2020 Elections](https://medium.com/stories-from-upstatement/building-custom-elements-with-web-components-for-the-2020-elections-f767ff9e9c6a)
- [Building Web Components with Vanilla JavaScript](https://dev.to/aspittel/building-web-components-with-vanilla-javascript--jho)
- [Creating a Reusable Avatar Web Component](https://marcoslooten.com/blog/creating-a-reusable-avatar-web-component/)
- [Creating Web Components with Stencil](https://auth0.com/blog/creating-web-components-with-stencil/)
- [From Web Component to Lit Element](https://codelabs.developers.google.com/codelabs/the-lit-path)
- [Getting started with LitElement and TypeScript](https://labs.thisdot.co/blog/getting-started-with-litelement-and-typescript)
- [Handling data with Web Components](https://itnext.io/handling-data-with-web-components-9e7e4a452e6e)
- [How to use D3js with WebComponents](https://towardsdatascience.com/how-to-use-d3js-with-webcomponents-a75ae4f980de)
- [Introduction to Storybook for Web Components](https://sinhapiyush.hashnode.dev/introduction-to-storybook-for-web-components)
- [Navigation Lifecycle using Vaadin Router, LitElement and TypeScript](https://labs.thisdot.co/blog/navigation-lifecycle-using-vaadin-router-litelement-and-typescript)
- [Open Web Components: Codelabs](https://open-wc.org/guides/developing-components/codelabs/)
- [Recreating The Arduino Pushbutton Using SVG And `<lit-element>`](https://www.smashingmagazine.com/2020/01/recreating-arduino-pushbutton-svg/)
- [Routing Management with LitElement and TypeScript](https://labs.thisdot.co/blog/routing-management-with-litelement)
- [Snake-Eating Game Making with Web Components of Omi and MVP Architecture](https://dev.to/dntzhang/snake-eating-game-making-with-web-components-of-omi-and-mvp-architecture-206)
- [Storybook for web components on steroids](https://dev.to/open-wc/storybook-for-web-components-on-steroids-4h29)
- [Testing Workflow for Web Components](https://dev.to/open-wc/testing-workflow-for-web-components-g73)
- [Web Components Tools: A Comparison](https://www.nexmo.com/blog/2020/05/20/web-components-tools-a-comparison)

### Examples

- [generic-components](https://github.com/thepassle/generic-components) - Collection of generic web components with a focus on accessibility, and ease of use.
- [howto-components](https://github.com/GoogleChromeLabs/howto-components) - Collection of web components that implement common web UI patterns.
- [open-wc code examples](https://open-wc.org/guides/developing-components/code-examples/) - Collection of best practices and design patterns for developing web components.
- [vanilla-retro-js](https://github.com/martine-dowden/vanilla-retro-js) - Vanilla JS UI component library of HTML deprecated tags.
- [web-components-examples](https://github.com/mdn/web-components-examples) - Series of web components examples, related to the MDN web components documentation.

## Articles

### Architecture

- [A deep analysis into isomorphic, autonomous cross-framework usage #MicroFrontends](https://itnext.io/a-deep-analysis-into-isomorphic-autonomous-cross-framework-usage-microfrontends-364271dc5fa9)
- [Frankenstein Migration: Framework-Agnostic Approach (Part 1)](https://www.smashingmagazine.com/2019/09/frankenstein-migration-framework-agnostic-approach-part-1/)
- [Frankenstein Migration: Framework-Agnostic Approach (Part 2)](https://www.smashingmagazine.com/2019/09/frankenstein-migration-framework-agnostic-approach-part-2/)
- [Generating Config driven Dynamic Forms using Web Components](https://codeburst.io/generating-config-driven-dynamic-forms-using-web-components-7c8d400f7f2e)
- [Hiding internal framework methods and properties from web component APIs](https://component.kitchen/blog/posts/hiding-internal-framework-methods-and-properties-from-web-component-apis)
- [How to deliver Custom Elements](https://medium.com/@WebReflection/how-to-deliver-custom-elements-702fae32d25c)
- [Making Web Components for Different Contexts](https://css-tricks.com/making-web-components-for-different-contexts/)
- [Supporting both automatic and manual registration of custom elements](https://component.kitchen/blog/posts/supporting-both-automatic-and-manual-registration-of-custom-elements)
- [Web Components — the right way](https://equinusocio.dev/blog/web-components-the-right-way/)

### Interoperability

- [Custom Elements Everywhere](https://custom-elements-everywhere.com)
- [Custom Elements That Work Anywhere](https://robdodson.me/interoperable-custom-elements/)
- [JavaScript frameworks, meet Web Components](https://www.voorhoede.nl/nl/blog/javascript-frameworks-meet-web-components/)
- [Web Components aren't a framework replacement - they're better than that](https://lamplightdev.com/blog/2020/01/18/web-components-arent-a-framework-replacement-theyre-better-than-that/)
- [Web Components: Seamlessly interoperable](https://medium.com/@sergicontre/web-components-seamlessly-interoperable-82efd6989ca4)

### Limitations

- [Beyond the polyfills: how Web Components affect us today?](https://dev.to/webpadawan/beyond-the-polyfills-how-web-components-affect-us-today-3j0a)
- [Custom elements, shadow DOM and implicit form submission](https://www.hjorthhansen.dev/shadow-dom-and-forms/)
- [Form-associated custom elements](https://www.hjorthhansen.dev/shadow-dom-form-participation/)
- [You might not need shadow DOM](https://www.hjorthhansen.dev/you-might-not-need-shadow-dom/)

### Styling

- [Options for styling web components](https://nolanlawson.com/2021/01/03/options-for-styling-web-components/)
- [Styling a Web Component](https://css-tricks.com/styling-a-web-component/)
- [Styling in the Shadow DOM With CSS Shadow Parts](https://css-tricks.com/styling-in-the-shadow-dom-with-css-shadow-parts/)
- [Styling is critical to web component reuse, but may prove difficult in practice](https://component.kitchen/blog/posts/styling-is-critical-to-web-component-reuse-but-may-prove-difficult-in-practice)
- [Thinking Through Styling Options for Web Components](https://css-tricks.com/thinking-through-styling-options-for-web-components/)
- [Web Standards Meet User-Land: Using CSS-in-JS to Style Custom Elements](https://css-tricks.com/web-standards-meet-user-land-using-css-in-js-to-style-custom-elements/)

## Real World

### Case Studies

- [Apple Just Shipped Web Components to Production and You Probably Missed It](https://dev.to/ionic/apple-just-shipped-web-components-to-production-and-you-probably-missed-it-57pf)
- [Bringing Order to Web Design Chaos (with Web Components)](https://dev.to/thatjoemoore/bringing-order-to-web-design-chaos--3fhb)
- [Get moving with Microsoft’s FAST web components](https://www.infoworld.com/article/3618410/get-moving-with-microsofts-fast-web-components.html)
- [How Web Components Are Used at GitHub and Salesforce](https://thenewstack.io/how-web-components-are-used-at-github-and-salesforce/)
- [How we use Web Components at GitHub](https://github.blog/2021-05-04-how-we-use-web-components-at-github/)
- [Implementing a Design Language System with Stencil.js](https://medium.com/@Danetag/implementing-a-design-language-system-with-stencil-js-515432918eb5)
- [ING ❤ Web Components](https://dev.to/thepassle/ing--web-components-aef)
- [ING Open-Sources Lion, Its White-Label Web Component Library – Q&A with Thomas Allmer](https://www.infoq.com/articles/ing-open-sources-lion-web-component/)
- [Lessons Learned, making our app with Web Components](https://medium.com/samsung-internet-dev/lessons-learned-making-our-app-with-web-components-bf55379cfcda)
- [Looking back on five years of web components](https://bitworking.org/news/2019/07/looking-back-on-five-years-of-web-components)
- [Shipping Web Components in 2020](https://dev.to/joe8bit/shipping-web-components-in-2020-2h54)
- [The Firefox UI is now built with Web Components](https://briangrinstead.com/blog/firefox-webcomponents/)
- [Using web components to encapsulate CSS and resolve design system conflicts](https://about.gitlab.com/blog/2021/05/03/using-web-components-to-encapsulate-css-and-resolve-design-system-conflicts/)
- [Web Components at GitHub - Web Components SF Meetup](https://www.infoq.com/news/2020/08/web-components-sf-meetup-2020/)
- [Web Components at Scale at Salesforce: Challenges Encountered, Lessons Learnt](https://www.infoq.com/news/2020/03/web-components-salesforce-lwc/)
- [Web Development At Scale: Composable Applications With Web Components](https://medium.com/@jarrodek/composable-applications-with-web-components-ebe5158387be)
- [web.dev engineering blog #1: How we build the site and use Web Components](https://web.dev/how-we-build-webdev-and-use-web-components/)

### Components

- [`<api-viewer>`](https://github.com/web-padawan/api-viewer-element) - API documentation and live playground for Web Components.
- [`<chess-board>`](https://github.com/justinfagnani/chessboard-element) - Standalone chess board web component.
- [`<css-doodle>`](https://github.com/css-doodle/css-doodle) - Web component for drawing patterns with CSS.
- [`<dark-mode-toggle>`](https://github.com/GoogleChromeLabs/dark-mode-toggle) - Custom element that allows to create a dark mode toggle or switch.
- [`<emoji-picker>`](https://github.com/nolanlawson/emoji-picker-element) - Lightweight emoji picker, distributed as a web component.
- [`<fg-modal>`](https://github.com/filamentgroup/fg-modal) - Accessible modal dialog web component.
- [`<file-viewer>`](https://github.com/avipunes/file-viewer) - Web component built with Svelte to view files.
- [`<json-viewer>`](https://github.com/alenaksu/json-viewer) - Web component to visualize JSON data in a tree view.
- [`<lite-youtube>`](https://github.com/paulirish/lite-youtube-embed) - Lite YouTube embed with a focus on visual performance.
- [`<midi-player>`](https://github.com/cifkao/html-midi-player) - MIDI file player and visualizer web components.
- [`<model-viewer>`](https://github.com/google/model-viewer) - Web component for rendering interactive 3D models.
- [`<player-x>`](https://github.com/playerxo/playerx) - Media player web component.
- [`<progressive-image>`](https://github.com/andreruffert/progressive-image-element) - Custom element to progressively enhance image placeholders.
- [`<range-slider>`](https://github.com/andreruffert/range-slider-element) - Accessible range slider custom element with keyboard support.
- [`<rapi-doc>`](https://github.com/mrin9/RapiDoc) - Web component for creating documentation from OpenAPI Specification.
- [`<shader-doodle>`](https://github.com/halvves/shader-doodle) - Web component for writing and rendering shaders.
- [`<trix-editor>`](https://github.com/basecamp/trix) - Rich text editor custom element for everyday writing.
- [`<vime-player>`](https://github.com/vime-js/vime) - Customizable, extensible, accessible and framework agnostic media player.
- [`<web-vitals>`](https://github.com/stefanjudis/web-vitals-element) - Bring [web vitals](https://github.com/GoogleChrome/web-vitals) quickly into your page using custom elements.

### Component Libraries

- [AMP](https://github.com/ampproject/amphtml) - Web component framework for easily creating user-first websites, stories, ads, emails and more.
- [Apollo Elements](https://github.com/apollo-elements/apollo-elements) - Custom elements for using Apollo GraphQL with various web components libraries.
- [AXA Pattern Library](https://github.com/axa-ch/patterns-library) - AXA CH UI components library built with Web Components.
- [Blackstone UI](https://github.com/kjantzer/bui) - Web components for creating interfaces by Blackstone Publishing.
- [Blaze UI Atoms](https://github.com/BlazeSoftware/atoms) - Set of web components powered by Blaze CSS.
- [Brightspace UI core](https://github.com/BrightspaceUI/core) - Collection of web components for building Brightspace applications.
- [Clever components](https://github.com/CleverCloud/clever-components) - Collection of Web Components made by Clever Cloud.
- [DataFormsJS](https://github.com/dataformsjs/dataformsjs) - Standalone Components for SPA routing, displaying data from web services, and more.
- [elements-sk](https://github.com/google/elements-sk) - Collection of custom elements for "a la carte" web development.
- [github-elements](https://github.com/github/github-elements) - GitHub's Web Component collection.
- [Elix](https://github.com/elix/elix) - High-quality, customizable web components for common user interface patterns.
- [Immersive Custom Elements](https://github.com/MozillaReality/immersive-custom-elements) - Set of web components for embedding immersive (VR & AR) content.
- [Iooxa](https://github.com/iooxa/article) - Web components for interactive scientific writing, reactive documents and explorable explanations.
- [Joomla UI custom elements](https://github.com/joomla-projects/custom-elements) - Compilation of Joomla 4 Custom Elements.
- [Ketch.UP](https://github.com/smeup/ketchup) - Web components library for Sme.UP.
- [Lion Web Components](https://github.com/ing-bank/lion) - Set of highly performant, accessible and flexible Web Components.
- [LRNWebComponents](https://github.com/elmsln/lrnwebcomponents/) - ELMS:LN produced web components for any project.
- [Lume](https://github.com/lume/lume) - Custom elements for defining 2D or 3D scenes rendered with CSS3D or WebGL.
- [Microsoft Graph Toolkit](https://github.com/microsoftgraph/microsoft-graph-toolkit) - Collection of web components for the Microsoft Graph.
- [Nightingale](https://github.com/ebi-webcomponents/nightingale) - Data visualisation web components for the life sciences.
- [Nuxeo Elements](https://github.com/nuxeo/nuxeo-elements) - Components for building web applications with Nuxeo using Web Components.
- [Open Business Application Platform Web Components](https://github.com/openbap/obap-elements) - Collection of web components designed for business applications.
- [Pixano Elements](https://github.com/pixano/pixano-elements) - Re-usable web components dedicated to data annotation tasks.
- [Shoelace](https://github.com/shoelace-style/shoelace) - A forward-thinking library of web components.
- [Smart Web Components](https://github.com/HTMLElements/smart-webcomponents) - Web components for business applications.
- [TEI Publisher Components](https://github.com/eeditiones/tei-publisher-components) - Collection of web components used by TEI Publisher and apps generated by it.
- [Tradeshift Elements](https://github.com/Tradeshift/elements) - Reusable Tradeshift UI Components as Web Components.
- [Vaadin components](https://github.com/vaadin/web-components) - Evolving set of high-quality web components for building business web applications.
- [Warp View](https://github.com/senx/warpview) - Collection of charting web components for Warp 10.
- [Wired Elements](https://github.com/wiredjs/wired-elements) - Set of common UI elements with a hand-drawn, sketchy look.
- [Wokwi Elements](https://github.com/wokwi/wokwi-elements) - Web Components for Arduino and various electronic parts.
- [XWeather](https://github.com/kherrick/x-weather) - Collection of web components implementing portions of the OpenWeatherMap API.

### Design Systems

- [Amber Components](https://github.com/bitrockteam/amber-components) - Web Components implementation of the Amber Design System.
- [Bolt Design System](https://github.com/boltdesignsystem/bolt) - Twig and Web Component-powered UI components, reusable visual styles and tooling.
- [Calcite Components](https://github.com/Esri/calcite-components) - Shared Web Components for Esri's Calcite design framework.
- [Carbon Custom Elements](https://github.com/carbon-design-system/carbon-custom-elements) - Carbon Design System variant on top of Web Components.
- [Chameleon Web Components](https://github.com/MaritzSTL/chameleon) - Collection of framework-agnostic elements based on the Chameleon Design System.
- [Clarity Core Web Components](https://github.com/vmware/clarity/tree/master/packages/core) - Suite of web components from the Clarity Design System.
- [Crayons](https://github.com/freshdesk/crayons) - Collection of web components that adheres to the Freshworks Design System.
- [FAST Components](https://github.com/microsoft/fast/tree/master/packages/web-components/fast-components) - Library of Web Components based on the FAST design language.
- [Fluent UI Web Components](https://github.com/microsoft/fluentui/tree/master/packages/web-components) - Library of Web Components that supports Microsoft's Fluent design language.
- [GOV.UK Web Components](https://github.com/tgreyuk/govuk-webcomponents) - Set of encapsulated web components consuming the GOV.UK Design System.
- [Helix UI](https://github.com/HelixDesignSystem/helix-ui) - Web Component library for the Helix Design System.
- [Lyne Components](https://github.com/lyne-design-system/lyne-components) - Building blocks of the Lyne Design System are based on Web Components.
- [Material Web Components](https://github.com/material-components/material-components-web-components) - Material Design implemented as Web Components.
- [NuML | NUDE Elements](https://github.com/tenphi/numl) - HTML Framework and Design System based on Web Components and runtime CSS generation.
- [PatternFly Elements](https://github.com/patternfly/patternfly-elements) - Collection of flexible and lightweight Web Components based on the Unified Design Kit.
- [Pearson Web Components](https://github.com/pearson-ux/web-components) - Pearson's shareable component library implementing Gravity design system.
- [Spectrum Web Components](https://github.com/adobe/spectrum-web-components) - Adobe Spectrum design language implementation built with Web Components.
- [UI5 Web Components](https://github.com/SAP/ui5-webcomponents) - Set of reusable UI elements implementing SAP Fiori Design Guidelines.
- [U-M Library Design System](https://github.com/mlibrary/design-system) - University of Michigan Library Design System.
- [Zooplus web components](https://github.com/zooplus/zoo-web-components) - Set of web components that implement Z+ shop style guide.

### Use Cases

- [How we chose to build our Design System using StencilJS Web Components](https://medium.com/8451/how-we-chose-to-build-our-design-system-using-stenciljs-web-components-4878c36743c5)
- [How searching for a bundle-free React led me to web components](https://www.bryanbraun.com/2020/08/31/how-searching-for-a-bundle-free-react-led-me-to-web-components/)
- [Reasons Web Components are perfect for a big company](https://medium.com/@sergicontre/reasons-web-components-are-perfect-for-a-big-company-28790d712ad5)
- [5 Reasons Web Components Are Perfect for Design Systems](https://ionicframework.com/blog/5-reasons-web-components-are-perfect-for-design-systems/)
- [Web components: the secret ingredient helping power the web](https://web.dev/web-components-io-2019/)
- [Web Components for Enterprise. Part 1: Salesforce, Oracle, SAP](https://dev.to/webpadawan/web-components-for-enterprise-part-1-salesforce-oracle-sap-e70)
- [Web Components for Enterprise. Part 2: Nuxeo, Ionic, Vaadin](https://dev.to/webpadawan/web-components-for-enterprise-part-2-nuxeo-ionic-vaadin-22l7)
- [Why I use Web Components - My use cases](https://dev.to/shihn/why-i-use-web-components-my-use-cases-1nip)
- [Why we use Web Components](https://viljamis.com/2019/why-we-use-web-components/) by [@viljamis](https://twitter.com/viljamis)
- [Why we use Web Components](https://dev.to/ionic/why-we-use-web-components-2c1i) by [@maxlynch](https://twitter.com/maxlynch)

## Libraries

### Class Based

- [Corpuscule](https://github.com/corpusculejs/corpuscule) - Small Web Components framework based on decorators.
- [DNA](https://github.com/chialab/dna) - Progressive Web Components library.
- [FAST Element](https://github.com/microsoft/fast/tree/master/packages/web-components/fast-element) - Lightweight library for building performant, memory-efficient, standards-compliant Web Components.
- [LitElement](https://lit-element.polymer-project.org) - Simple base class for creating fast, lightweight web components. Part of the Polymer Project.
- [Lightning Web Components](https://github.com/salesforce/lwc) - blazing fast, enterprise-grade Web Components foundation.
- [Omi](https://github.com/Tencent/omi) - Next generation web framework in 4kb JavaScript (Web Components + JSX + Proxy + Store + Path Updating).
- [Panel](https://github.com/mixpanel/panel) - Web Components + Virtual DOM: web standards for powerful UIs.
- [Polymer](https://polymer-library.polymer-project.org) - Original web component library by the Polymer Project authors.
- [Skate](https://github.com/skatejs/skatejs) - Web component library focusing on a functional rendering pipeline and a small footprint.
- [slim.js](https://github.com/slimjs/slim.js) - Fast & Robust Front-End Micro-framework based on modern standards.
- [Stencil](https://github.com/ionic-team/stencil) - Compiler for generating Web Components.
- [Tonic](https://github.com/optoolco/tonic) - Minimalist, stable, audit friendly component framework.

### Functional

- [atomico](https://github.com/atomicojs/atomico) - Small library for the creation of interfaces based on web components using functions and hooks.
- [fuco](https://github.com/wtnbass/fuco) - Functional component like React, but for Web Components.
- [haunted](https://github.com/matthewp/haunted) - React's Hooks API implemented for web components.
- [hybrids](https://github.com/hybridsjs/hybrids) - UI library for creating Web Components with simple and functional API.
- [Solid](https://github.com/ryansolid/solid) - Declarative JavaScript library for creating user interfaces.

### Integrations

- [ember-custom-elements](https://github.com/Ravenstine/ember-custom-elements) - Render Ember and Glimmer components using custom elements.
- [preact-custom-element](https://github.com/preactjs/preact-custom-element) - Generate/register a custom element from a preact component.
- [@adobe/react-webcomponent](https://github.com/adobe/react-webcomponent) - Automate the wrapping of a React component in a custom element.
- [react-shadow](https://github.com/Wildhoney/ReactShadow) - Utilise Shadow DOM in React with all the benefits of style encapsulation.
- [reactify-wc](https://github.com/BBKolton/reactify-wc) - Use web components with React properties and functions.
- [remount](https://github.com/rstacruz/remount) - Mount React components to the DOM using custom elements.
- [@riotjs/custom-elements](https://github.com/riot/custom-elements) - Simple API to create vanilla custom elements with Riot.js.

### Benchmarks

- [All the Ways to Make a Web Component](https://webcomponents.dev/blog/all-the-ways-to-make-a-web-component/)
- [web-components-benchmark](https://vogloblinsky.github.io/web-components-benchmark/) - Benchmark Web Components technologies with various examples.
- [web-components-todo](https://wc-todo.firebaseapp.com/) - The same todo application built in different Web Components libraries for benchmark purpose.

## Frameworks

### Angular

- [Angular Elements Overview](https://angular.io/guide/elements)
- [Building and consuming Angular Elements as Web Components](https://indepth.dev/building-and-bundling-web-components/)
- [How to use Angular ngModel and ngForms with WebComponents](https://itnext.io/how-to-use-angular-ngmodel-and-ngforms-with-webcomponents-802bd9e1d3d7)
- [Using Web Components in Angular](https://coryrylan.com/blog/using-web-components-in-angular)
- [Web Components With Angular Ivy In 6 Steps](https://www.softwarearchitekt.at/post/2019/05/18/web-components-custom-elements-with-angular-ivy-in-6-steps.aspx)

### React

- [Rendering React Components With Custom Elements](https://guillaumebriday.fr/rendering-react-components-with-custom-elements)
- [How to use Web Components in React](https://www.robinwieruch.de/react-web-components)

### Vue

- [Create & Publish Web Components With Vue CLI 3](https://vuejsdevelopers.com/2018/05/21/vue-js-web-component/)
- [Get started with Vue web components](https://medium.com/@royprins/get-started-with-vue-web-components-593b3d5b3200)
- [Integrate Web Components with Your Vue.js App](https://alligator.io/vuejs/vue-integrate-web-components/)
- [Using Web Components in Vue](https://coryrylan.com/blog/using-web-components-in-vue)

### Svelte

- [Svelte Custom Element API](https://svelte.dev/docs#Custom_element_API)
- [How to Create a Web Component in Svelte](https://dev.to/silvio/how-to-create-a-web-components-in-svelte-2g4j)
- [Svelte Web Component — 5.4KB](https://itnext.io/svelte-web-component-5-4kb-4afe46590d99)

## Ecosystem

### Starter Kits

- [Create Open Web Components](https://open-wc.org/docs/development/generator/) - Web component project scaffolding.
- [custom-element-boilerplate](https://github.com/github/custom-element-boilerplate) - Boilerplate for creating a custom element.
- [hello-web-components](https://github.com/fernandopasik/hello-web-components) - Simple starter hello world web component written in TypeScript.
- [nutmeg](https://github.com/abraham/nutmeg) - Build, test, and publish vanilla Web Components with a little spice.

### Tools

- [Custom Elements Locator](https://github.com/open-wc/locator) - Chrome extension to find custom elements on a page.
- [query-selector-shadow-dom](https://github.com/Georgegriff/query-selector-shadow-dom) - querySelector that can pierce Shadow DOM roots, useful for automated testing.
- [shadow-automation-selenium](https://github.com/sukgu/shadow-automation-selenium) - Shadow DOM automation using Selenium.
- [shadow-dom-utils](https://github.com/43081j/shadow-dom-utils) - Set of useful utilities for dealing with shadow DOM, primarily for test environment.
- [@storybook/web-components](https://www.npmjs.com/package/@storybook/web-components) - UI development environment for plain web-component snippets.
- [webcomponents.dev](https://webcomponents.dev) - Component IDE for web platform developers.
- [web-component-analyzer](https://github.com/runem/web-component-analyzer) - CLI that analyzes web components and emits documentation / diagnostics.
- [Web Components Codemods](https://github.com/kcmr/web-components-codemods) - Codemods for Web Components.

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

- "**The Modern JavaScript Tutorial**" by [Ilya Kantor](https://github.com/iliakan)
  - [Part 1: From the orbital height](https://javascript.info/webcomponents-intro)
  - [Part 2: Custom Elements](https://javascript.info/custom-elements)
  - [Part 3: Shadow DOM](https://javascript.info/shadow-dom)
  - [Part 4: Template element](https://javascript.info/template-element)
  - [Part 5: Shadow DOM slots, composition](https://javascript.info/slots-composition)
  - [Part 6: Shadow DOM styling](https://javascript.info/shadow-dom-style)
  - [Part 7: Shadow DOM and events](https://javascript.info/shadow-dom-events)

- "**HowTo: Components**" by [Web Fundamentals](https://developers.google.com/web/fundamentals/)
  - [Overview](https://developers.google.com/web/fundamentals/web-components/examples)
  - [`<howto-checkbox>`](https://developers.google.com/web/fundamentals/web-components/examples/howto-checkbox)
  - [`<howto-tabs>`](https://developers.google.com/web/fundamentals/web-components/examples/howto-tabs)
  - [`<howto-tooltip>`](https://developers.google.com/web/fundamentals/web-components/examples/howto-tooltip)

- **CSS tricks** article series by [Caleb Williams](https://css-tricks.com/author/calebdwilliams/)
  - [Part 1: An Introduction to Web Components](https://css-tricks.com/an-introduction-to-web-components/)
  - [Part 2: Crafting Reusable HTML Templates](https://css-tricks.com/crafting-reusable-html-templates/)
  - [Part 3: Creating a Custom Element from Scratch](https://css-tricks.com/creating-a-custom-element-from-scratch)
  - [Part 4: Encapsulating Style and Structure with Shadow DOM](https://css-tricks.com/encapsulating-style-and-structure-with-shadow-dom/)
  - [Part 5: Advanced Tooling for Web Components](https://css-tricks.com/advanced-tooling-for-web-components/)

- **Angular Elements** article series by [Manfred Steyer](https://www.angulararchitects.io/about/)
  - [Part I: A Dynamic Dashboard In Four Steps With Web Components](https://www.angulararchitects.io/aktuelles/angular-elements-part-i/)
  - [Part II: Lazy and External Web Components](https://www.angulararchitects.io/aktuelles/angular-elements-part-ii/)
  - [Part III: Angular Elements Without Zone.Js](https://www.angulararchitects.io/aktuelles/angular-elements-part-iii/)
  - [Part IV: Content Projection with Slots in Angular Elements (>=7)](https://www.angulararchitects.io/aktuelles/content-projection-with-slots-in-angular-elements-7/)
  - [Part V: Your Options for Building Angular Elements with the CLI](https://www.angulararchitects.io/aktuelles/your-options-for-building-angular-elements/)

## Insights

### Podcasts

- [Code[ish], episode 38: Building with Web Components](https://www.heroku.com/podcasts/codeish/38-building-with-web-components)
- [Frontend Happy Hour, episode 62: Web Components - shots of shadow DOM](https://frontendhappyhour.com/episodes/web-components-shots-of-shadow-dom/)
- [Labs Talk - Web Components with Peter Muessig](https://labstalk.buzzsprout.com/993481/3932975-web-components-with-peter-muessig)
- [Real Talk JavaScript, episode 7: Custom Web Components with Rob Wormald](https://realtalkjavascript.simplecast.fm/eaf3db9e)
- [Real Talk JavaScript, episode 101: Back to Basics with Native HTML and LitElement](https://realtalkjavascript.simplecast.com/episodes/episode-101-back-to-basics-with-native-html-and-litelement)

### Presentations

- [Are Web Components the Betamax of web development?](https://noti.st/lostinbrittany/EjUZyd/are-web-components-the-betamax-of-web-development) by [@lostinbrittany](https://twitter.com/lostinbrittany)
- [Designing Standard Systems](https://drive.google.com/file/d/1ALFiWOFU0UAGUpaZPMIVnoADs9_REtL5/view) by [@stefsull](https://twitter.com/stefsull) and [@bferrua](https://twitter.com/bferrua)
- [Frontend Architecture for Scalable Design Systems](https://events.drupal.org/seattle2019/sessions/design-system-architecture-pattern-lab-twig-and-web-components) by [@salem_cobalt](https://twitter.com/salem_cobalt)
- [lit-apollo: Data-Driven Components that Use the Platform](https://apolloelements.dev/using-lit-apollo/) by [@PowersBenny](https://twitter.com/PowersBenny)
- [Mastering Shadow DOM](https://martine-dowden.github.io/portfolio/presentation/mastering-shadow-dom) by [@Martine_Dowden](https://twitter.com/Martine_Dowden)
- [Modernizing Large Frontends with Web Components](https://speakerdeck.com/samjulien/modernizing-large-frontends-with-web-components) by [@samjulien](https://twitter.com/samjulien)
- [Shadow DOM: off the beaten track](https://docs.google.com/presentation/d/1wi74YiTLtLSfgjyccKm5LxYp9k8aeJda0AekWV5mqJI/edit?usp=sharing) by [@serhiikulykov](https://twitter.com/serhiikulykov)
- [Using Web Components to Build a Framework-agnostic UI Library](https://gotochgo.com/2019/sessions/866/using-web-components-to-build-a-framework-agnostic-ui-library) by [@brianbouril](https://twitter.com/brianbouril) and [@danciupuliga](https://twitter.com/danciupuliga)
- [Web Components and the AOM](https://decks.tink.uk/2019/jsconf/index.html) by [@LeonieWatson](https://twitter.com/LeonieWatson)
- [Web Components and Styles Scoping](https://www.dropbox.com/s/wdh9uufjui5htll/Web-Components-and-Styles-Scoping-by-bashmish-FrontMania-2018.pdf) by [@bashmish](https://twitter.com/bashmish)
- [Web Components can do that?!](https://slides.com/vogloblinsky/web-components-can-do-that) by [@vogloblinsky](https://twitter.com/vogloblinsky)
- [Web Components: Introduction and State of the Art](https://webcomponents.dev/blog/web-components-slides/) by [@webcomp_dev](https://twitter.com/webcomp_dev)

### Talks

- [Better Apps: Delivering Universal UI Patterns as Web Components](https://youtu.be/mtHf7crZZIQ) by [@janmiksovsky](https://twitter.com/janmiksovsky)
- [Custom Web Shadow Elements, or Whatever…](https://vimeo.com/364370506) by [@aerotwist](https://twitter.com/aerotwist)
- [Styling and Theming Web Components](https://youtu.be/FM7ROEVPA4k) by [@justinfagnani](https://twitter.com/justinfagnani)
- [Web Components at Enterprise Scale](https://youtu.be/iFp-P2UJT_Y) by [@diervo](https://twitter.com/diervo)

## Usage Metrics

- [Chrome Platform Status: `CustomElementRegistryDefine`](https://chromestatus.com/metrics/feature/timeline/popularity/1689)
- [Chrome Platform Status: `ElementAttachShadow`](https://chromestatus.com/metrics/feature/timeline/popularity/804)
- [Chrome Platform Status: `HTMLTemplateElement`](https://chromestatus.com/metrics/feature/timeline/popularity/2769)

## Proposals

### Form-associated Custom Elements

- [Form Participation API Explained](https://docs.google.com/document/d/1JO8puctCSpW-ZYGU8lF-h4FWRIDQNDVexzHoOQ2iQmY/edit?usp=sharing) - Document by Google Chrome team.
- [Form-associated custom elements](https://www.chromestatus.com/features/4708990554472448) - Feature in Chrome platform status.
- [web-platform-tests](https://github.com/web-platform-tests/wpt/tree/master/custom-elements/form-associated)

### Custom State Pseudo class

- [Blink: Intent to implement](https://groups.google.com/a/chromium.org/forum/#!topic/blink-dev/CApU9QIu3TM)
- [`ElementInternals`'s `states` property and the `:state()` pseudo class](https://github.com/w3c/webcomponents/blob/gh-pages/proposals/custom-states-and-state-pseudo-class.md)

### Constructable Stylesheet Objects

- [Specification Draft](https://wicg.github.io/construct-stylesheets/)
- [web-platform-tests](https://github.com/web-platform-tests/wpt/blob/master/css/cssom/CSSStyleSheet-constructable.html)
- [Explainer](https://github.com/WICG/construct-stylesheets/blob/gh-pages/explainer.md)
- [Constructable Stylesheets](https://www.chromestatus.com/feature/5394843094220800) - Feature in Chrome platform status.

## Miscellaneous

- [bruck](https://github.com/Heydon/bruck) - Prototyping system built with web components and the Houdini Paint API.
- [Vaadin Directory](https://vaadin.com/directory) - Publish, discuss and rate web components
- [webcomponents.org](http://webcomponents.org/) - Discuss &amp; share web components.

## History

The articles below represent a long story of the Web Components specifications on the way towards the standardization.
Some of them refer to earlier, so-called "v0" Shadow DOM and Custom Elements specs, and abandoned HTML Imports spec.
These materials are here for historical reasons only, they are grouped by years and listed in chronological order.

### 2019

- [A history of the HTML slot element](https://component.kitchen/blog/posts/a-history-of-the-html-slot-element)
- [Web Components in 2019: An Overview of the Most Exciting Proposals for the Web Platform Related to Web Components](https://scotch.io/bar-talk/an-overview-of-the-most-exciting-proposals-for-the-web-platform-related-to-web-components)

### 2018

- [Styling Accessibility: A Web Components Approach](https://medium.com/@cfscorreia/styling-accessibility-a-web-components-approach-dc2aa8123eb2)
- [Web Components 101: An Introduction to Web Components](https://www.telerik.com/blogs/web-components-101-an-introduction-to-web-components)
- [Web Components in 2018](https://www.sitepen.com/blog/2018/07/06/web-components-in-2018/)
- [Web Components Introduction: Creating Custom HTML Elements in 2018](https://www.grapecity.com/en/blogs/web-components-introduction-creating-custom-html-elements-2018)

### 2017

- [Web Components: The Long Game](https://infrequently.org/2017/10/web-components-the-long-game/)
- [An intro to web components with otters](https://meowni.ca/posts/web-components-with-otters/)
- [The broken promise of Web Components](https://dmitriid.com/blog/2017/03/the-broken-promise-of-web-components/)
- [Regarding the broken promise of Web Components](http://robdodson.me/regarding-the-broken-promise-of-web-components/)

### 2016

- [Introducing Custom Elements](https://webkit.org/blog/7027/introducing-custom-elements/)
- [The Case for Custom Elements: Part 1](https://medium.com/dev-channel/the-case-for-custom-elements-part-1-65d807b4b439)
- [The Case for Custom Elements: Part 2](https://medium.com/dev-channel/the-case-for-custom-elements-part-2-2efe42ce9133)
- [Demythstifying Web Components](http://www.backalleycoder.com/2016/08/26/demythstifying-web-components/)
- [What's New in Shadow DOM v1 (by examples)](http://hayato.io/2016/shadowdomv1/)
- [Understanding Web Components](https://medium.com/the-ui-files/understanding-web-components-d051baa66019)

### 2015

- [Introducing Slot-Based Shadow DOM API](https://webkit.org/blog/4096/introducing-shadow-dom-api/)
- [Web Components and their role in the future of web development](http://kaytcat.github.io/web-components/)
- [Microsoft Edge and Web Components](https://blogs.windows.com/msedgedev/2015/07/15/microsoft-edge-and-web-components/)
- [Bringing componentization to the web: An overview of Web Components](https://blogs.windows.com/msedgedev/2015/07/14/bringing-componentization-to-the-web-an-overview-of-web-components/)
- [The state of Web Components](https://hacks.mozilla.org/2015/06/the-state-of-web-components/)

### 2014

- [A No-Nonsense Guide to Web Components](http://cbateman.com/blog/a-no-nonsense-guide-to-web-components-part-1-the-specs/)
- [Mozilla and Web Components: Update](https://hacks.mozilla.org/2014/12/mozilla-and-web-components/)
- [The State of the Componentised Web](https://www.leggetter.co.uk/2014/08/06/state-componentised-web.html)
- [Building an Accessible Disclosure Button – using Web Components](https://developer.paciellogroup.com/blog/2014/06/accessible-disclosure-button-using-web-components/)
- [Web Components and you – dangers to avoid](https://christianheilmann.com/2014/04/18/web-components-and-you-dangers-to-avoid/)
- [The Web's Declarative, Composable Future](https://addyosmani.com/blog/the-webs-declarative-composable-future/)
- [The Shadow DOM Diaries](https://gist.github.com/dglazkov/efd2deec54f65aa86f2e)
- [A Detailed Introduction To Custom Elements](https://www.smashingmagazine.com/2014/03/introduction-to-custom-elements/)

### 2013

- [Performance and Custom Elements](https://www.stevesouders.com/blog/2013/11/26/performance-and-custom-elements/)
- [A Guide to Web Components](https://css-tricks.com/modular-future-web-components/)
- [Creating Reusable Markup with The HTML Template Element](https://blog.teamtreehouse.com/creating-reusable-markup-with-the-html-template-element)
- [Working with Shadow DOM](https://blog.teamtreehouse.com/working-with-shadow-dom)
- [HTML's New Template Tag](https://www.html5rocks.com/en/tutorials/webcomponents/template/)

### 2012

- [The Basics of the Shadow DOM](https://www.sitepoint.com/the-basics-of-the-shadow-dom/)
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
        <a href="https://twitter.com/polymer">
          <img width="80" height="80" src="https://pbs.twimg.com/profile_images/1063502058337136640/RmlG_bbW_80x80.jpg">
          <div>Polymer</div>
        </a>
      </td>
      <td align="center">
        <a href="https://twitter.com/stenciljs">
          <img width="80" height="80" src="https://pbs.twimg.com/profile_images/1135534552137510914/5ZzvOFFp_80x80.png">
          <div>Stencil</div>
        </a>
      </td>
      <td align="center">
        <a href="https://twitter.com/openwc">
          <img width="80" height="80" src="https://pbs.twimg.com/profile_images/1101188623930662912/YKlBD7n6_80x80.png">
          <div>open-wc.org</div>
        </a>
      </td>
      <td align="center">
        <a href="https://twitter.com/webcomp_dev">
          <img width="80" height="80" src="https://pbs.twimg.com/profile_images/1169270943371407360/U-90Bxn0_80x80.jpg">
          <div>webcomponents.dev</div>
        </a>
      </td>
    </tr>
    <tr>
      <td align="center">
        <a href="https://twitter.com/justinfagnani">
          <img width="80" height="80" src="https://pbs.twimg.com/profile_images/378800000808710206/2dbdaa1cb7b0db02f997aea5b40f29b8_80x80.jpeg">
          <div>Justin Fagnani</div>
        </a>
      </td>
      <td align="center">
        <a href="https://twitter.com/viljamis">
          <img width="80" height="80" src="https://pbs.twimg.com/profile_images/671595827740086273/wCUWq-1S_80x80.png">
          <div>Viljami Salminen</div>
        </a>
      </td>
      <td align="center">
        <a href="https://twitter.com/JanMiksovsky">
          <img width="80" height="80" src="https://pbs.twimg.com/profile_images/675000078055051264/u1ZEQfeE_80x80.jpg">
          <div>Jan Miksovsky</div>
        </a>
      </td>
      <td align="center">
        <a href="https://twitter.com/serhiikulykov">
          <img width="80" height="80" src="https://pbs.twimg.com/profile_images/1028197887329685504/cM6nOHlp_80x80.jpg">
          <div>Serhii Kulykov</div>
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
