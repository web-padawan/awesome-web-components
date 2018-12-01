# Web Components the Right Way

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> This is a guide intended to introduce to Web Components. Everyone can contribute here!

## Contents

- [Specifications](#specifications)
- [Introduction](#introduction)
- [Custom Elements](#custom-elements)
- [Shadow DOM](#shadow-dom)
- [HTML Templates](#html-templates)
- [Tutorials](#tutorials)
- [Polyfills](#polyfills)
- [Libraries](#libraries)
- [Frameworks](#frameworks)
- [Best Practices](#best-practices)
- [Blogs](#blogs)
- [Who to follow](#who-to-follow)
- [License](#license)

> Web Components the Right Way was made with love by [Mateus Ortiz](https://twitter.com/mteusortiz)

## Specifications

- **Custom Elements** provide a way for authors to build their own fully-featured DOM elements.
  - [HTML Living Standard](https://html.spec.whatwg.org/multipage/custom-elements.html)
  - [DOM Living Standard](https://dom.spec.whatwg.org/#concept-element)
  - [W3C HTML 5.3 Working Draft](https://www.w3.org/TR/html53/semantics-scripting.html#custom-elements-core-concepts)
  - [W3C DOM 4.1 Working Draft](https://www.w3.org/TR/dom41/#interface-element)

- **Shadow DOM** describes a method of combining multiple DOM trees into one hierarchy and how these trees interact with each other within a document, thus enabling better composition of the DOM.
  - [W3C Editor's Draft](http://w3c.github.io/webcomponents/spec/shadow/)
  - [DOM Living Standard](https://dom.spec.whatwg.org/#shadow-trees), section 4.2.2: shadow tree
  - [DOM Living Standard](https://dom.spec.whatwg.org/#interface-shadowroot), section 4.8: interface `ShadowRoot`
  - [W3C DOM 4.1 Working Draft](https://www.w3.org/TR/dom41/#shadow-trees), section 4.2.2: shadow tree
  - [W3C DOM 4.1 Working Draft](https://www.w3.org/TR/dom41/#interface-shadowroot), section 4.8: interface `ShadowRoot`

- **`<template>`** element is used to declare fragments of HTML that can be cloned and inserted in the document by script.
  - [HTML Living Standard](https://html.spec.whatwg.org/multipage/scripting.html#the-template-element)
  - [W3C HTML 5.1 2nd Edition](https://www.w3.org/TR/html51/semantics-scripting.html#the-template-element)

## Introduction

- [The Holy Grail Of Reusable Components: Custom Elements, Shadow DOM, And NPM](https://www.smashingmagazine.com/2018/07/reusable-components-custom-elements-shadow-dom-npm/)
- [The Power of Web Components](https://hacks.mozilla.org/2018/11/the-power-of-web-components/)
- [Web Components in 2018](https://www.sitepen.com/blog/2018/07/06/web-components-in-2018/)
- [Making Web Components Work](https://engineering.mixpanel.com/2018/06/12/making-web-components-work/)
- [Web Components Introduction: Creating Custom HTML Elements in 2018](https://www.grapecity.com/en/blogs/web-components-introduction-creating-custom-html-elements-2018)
- [Web Components — the right way](https://equinsuocha.io/blog/web-components-the-right-way/)
- [Lessons Learned, making our app with Web Components](https://medium.com/samsung-internet-dev/lessons-learned-making-our-app-with-web-components-bf55379cfcda)

## Custom Elements

- [Custom Elements v1: Reusable Web Components](https://developers.google.com/web/fundamentals/web-components/customelements)
- [Custom Elements Everywhere](https://custom-elements-everywhere.com)
- [All about HTML Custom Elements](https://github.com/shawnbot/custom-elements)
- [Introducing Custom Elements (WebKit)](https://webkit.org/blog/7027/introducing-custom-elements/)
- [The Case for Custom Elements: Part 1](https://medium.com/dev-channel/the-case-for-custom-elements-part-1-65d807b4b439)
- [The Case for Custom Elements: Part 2](https://medium.com/dev-channel/the-case-for-custom-elements-part-2-2efe42ce9133)
- [Custom Elements That Work Anywhere](https://robdodson.me/interoperable-custom-elements/)
- [The future of accessibility for custom elements](https://robdodson.me/the-future-of-accessibility-for-custom-elements/)
- [Using Custom Elements (MDN)](https://developer.mozilla.org/en-US/docs/Web/Web_Components/Using_custom_elements)
- [A Guide to Custom Elements for React Developers](https://css-tricks.com/a-guide-to-custom-elements-for-react-developers/)

## Shadow DOM

- [Shadow DOM v1: Self-Contained Web Components](https://developers.google.com/web/fundamentals/web-components/shadowdom)
- [The Rise of Shadow DOM](https://medium.com/front-end-hacking/the-rise-of-shadow-dom-84aa1f731e82)
- [What's New in Shadow DOM v1 (by examples)](http://hayato.io/2016/shadowdomv1/)
- [Introducing Slot-Based Shadow DOM API (WebKit)](https://webkit.org/blog/4096/introducing-shadow-dom-api/)
- [Using Shadow DOM (MDN)](https://developer.mozilla.org/en-US/docs/Web/Web_Components/Using_shadow_DOM)

## HTML Templates

- [&lt;template&gt;: The Content Template element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/template)
- [Using templates and slots (MDN)](https://developer.mozilla.org/en-US/docs/Web/Web_Components/Using_templates_and_slots)

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

## Polyfills

- [webcomponents.js](https://github.com/webcomponents/webcomponentsjs) - Suite of polyfills supporting the HTML Web Components specs.
- [custom-elements](https://github.com/webcomponents/custom-elements) - Polyfill for HTML Custom Elements v1.
- [shadydom](https://github.com/webcomponents/shadydom) - ShadowDOM v1 shim.
- [shadycss](https://github.com/webcomponents/shadycss) - ShadowDOM style encapsulation shim.
- [template](https://github.com/webcomponents/template) - Minimal polyfill for `<template>`.

## Libraries

- [LitElement](https://lit-element.polymer-project.org) - Simple base class for creating fast, lightweight web components. Part of the Polymer Project.
- [Polymer](https://polymer-library.polymer-project.org) - Original web component library by the Polymer Project authors.
- [Skate](https://github.com/skatejs/skatejs) - Web component library focusing on a functional rendering pipeline, clean property / attribute semantics and a small footprint.

## Frameworks
- [Angular Elements](https://angular.io/guide/elements)
- [Create & Publish Web Components With Vue CLI 3](https://vuejsdevelopers.com/2018/05/21/vue-js-web-component/)

## Best Practices

- [The Gold Standard Checklist for Web Components](https://github.com/webcomponents/gold-standard/wiki)
- [Custom Element Best Practices](https://developers.google.com/web/fundamentals/web-components/best-practices)
- [HowTo: Components](https://developers.google.com/web/fundamentals/web-components/examples/)
- [Open Web Components Recommendations](https://open-wc.org)

## Blogs

- [webcomponents.org](http://webcomponents.org/) - Home of the Web Components community.
- [Polymer Blog](https://www.polymer-project.org/blog/) - The latest goings-on with the Polymer project and in the community.

## Who To Follow

[![Eric Bidelman](https://2.gravatar.com/avatar/e7948aac7c52b26470be80311873a398)](https://twitter.com/ebidel) | [![Addy Osmani](https://2.gravatar.com/avatar/96270e4c3e5e9806cf7245475c00b275)](https://twitter.com/addyosmani) | [![Rob Dodson](https://2.gravatar.com/avatar/95c3a3b33ea51545229c625bef42e343)](https://twitter.com/rob_dodson) | [![Web Components](https://2.gravatar.com/avatar/cedf2a3fe1ccf53aa00f50dda79cedf3)](https://twitter.com/web_components) | [![Polymer](https://avatars0.githubusercontent.com/u/2159051?v=2&s=80)](https://twitter.com/polymer)
--- | --- | --- | --- | ---
[Eric Bidelman](https://twitter.com/ebidel) | [Addy Osmani](https://twitter.com/addyosmani) | [Rob Dodson](https://twitter.com/rob_dodson) | [Web Components](https://twitter.com/web_components) | [Polymer](https://twitter.com/polymer)

[![Alex Komoroske](https://lh5.googleusercontent.com/-WlbCSDZ9t5Y/AAAAAAAAAAI/AAAAAAAAC2M/A_HM2ovbT2o/s80-c/photo.jpg)](https://twitter.com/jkomoros) | [![Pascal](https://2.gravatar.com/avatar/b32bdb1fc9fdadeb45d7a1267fdd2fc4)](https://twitter.com/PascalPrecht) | [![Zeno Rocha](https://2.gravatar.com/avatar/e190023b66e2b8aa73a842b106920c93)](https://twitter.com/zenorocha) | [![Daniel Buchner](https://2.gravatar.com/avatar/35e22073952684192bb93702a947308c)](https://twitter.com/csuwildcat) | [![Angelina Fabbro](https://2.gravatar.com/avatar/25bb0913435212f30f2fec0eb6e60dde)](https://twitter.com/hopefulcyborg)
--- | --- | --- | --- | ---
[Alex Komoroske](https://twitter.com/jkomoros) | [Pascal Precht](https://twitter.com/PascalPrecht) | [Zeno Rocha](https://twitter.com/zenorocha) | [Daniel Buchner](https://twitter.com/csuwildcat) | [Angelina Fabbro](https://twitter.com/hopefulcyborg)

[![Eduardo](https://2.gravatar.com/avatar/42327de520e674a6d1686845b30778d0)](https://twitter.com/eduardolundgren) | [![Pascal Hartig](https://avatars0.githubusercontent.com/u/9906?v=2&s=80)](https://twitter.com/passy) | [![Sindre Sorhus](https://2.gravatar.com/avatar/d36a92237c75c5337c17b60d90686bf9)](https://twitter.com/sindresorhus) | [![Christian](https://2.gravatar.com/avatar/07fcd228af02d476b1b8367d85a903b2)](https://twitter.com/codepo8)
--- | --- | --- | ---
[Eduardo lundgren](https://twitter.com/eduardolundgren) | [Pascal Hartig](https://twitter.com/passy) | [Sindre Sorhus](https://twitter.com/sindresorhus) | [Christian Heilmann](https://twitter.com/codepo8)


## License

Copyright 2014-2018, All rights reserved.

Code licensed under the:
[MIT license](http://mateusortiz.mit-license.org)

@author Mateus Ortiz <mteusortiz@gmail.com>
